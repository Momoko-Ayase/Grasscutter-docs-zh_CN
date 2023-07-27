# ⌨ 指令

## 基础指令列表

<table><thead><tr><th width="164">Command</th><th>Description</th></tr></thead><tbody><tr><td>account</td><td>创建或删除账号</td></tr><tr><td>announce</td><td>向所有在线玩家发送公告，或者管理服务器的公告</td></tr><tr><td>ban</td><td>封禁玩家</td></tr><tr><td>clear</td><td>从你的背包中删除所有未装备且已解锁的物品，包括稀有物品</td></tr><tr><td>coop</td><td>强制传送指定玩家到他人的世界。如果没有指定玩家，则会使你进入多人游戏状态</td></tr><tr><td>enter_dungeon</td><td>进入指定秘境</td></tr><tr><td>give</td><td>向你或指定的玩家给予物品。比如可以给予全部武器，角色和/或材料，也可以给予自定义圣遗物</td></tr><tr><td>heal</td><td>治疗当前队伍的角色</td></tr><tr><td>help</td><td>发送帮助信息或显示指定命令的信息</td></tr><tr><td>kick</td><td>从服务器内踢出指定玩家</td></tr><tr><td>killall</td><td>杀死所有怪物</td></tr><tr><td>killCharacter</td><td>杀死玩家当前角色</td></tr><tr><td>language</td><td>显示或切换当前语言</td></tr><tr><td>list</td><td>查看所有玩家</td></tr><tr><td>permission</td><td>添加或移除指定玩家的权限</td></tr><tr><td>position</td><td>获取所在位置和旋转信息</td></tr><tr><td>quest</td><td>添加或完成任务</td></tr><tr><td>reload</td><td>重载配置文件和数据</td></tr><tr><td>resetConst</td><td>重置当前角色的命之座，执行命令后需重新登录以生效</td></tr><tr><td>resetShopLimit</td><td>重置指定玩家的商店刷新时间</td></tr><tr><td>sendMail</td><td>向指定用户发送邮件。此命令的用法会根据撰写阶段而改变</td></tr><tr><td>sendMessage</td><td>向玩家以服务器的身份发送消息。如果没有指定目标，则向服务器的全部玩家发送</td></tr><tr><td>setConst</td><td>为当前活跃角色设置命座等级</td></tr><tr><td>setFetterLevel</td><td>设置当前角色的好感度等级</td></tr><tr><td>setProp</td><td>设置账号的状态。比如可以通过此命令启用godmode，也可以解锁深渊或更改纪行等级</td></tr><tr><td>setStats</td><td>设置当前角色的属性</td></tr><tr><td>spawn</td><td>在你附近生成实体</td></tr><tr><td>stop</td><td>停止服务器</td></tr><tr><td>talent</td><td>设置当前角色的天赋等级</td></tr><tr><td>team</td><td>手动修改你的队伍</td></tr><tr><td>teleport</td><td>改变指定玩家的位置</td></tr><tr><td>teleportAll</td><td>将你世界中的所有玩家传送到你所在的位置</td></tr><tr><td>unban</td><td>取消玩家的封禁</td></tr><tr><td>unlockall</td><td>为玩家解锁全部开放状态</td></tr><tr><td>weather</td><td>更改天气ID和气候类型。</td></tr></tbody></table>

{% hint style="info" %}
**SetProp**

可更改的状态列表：godmode(上帝模式)|nostamina(无限体力)|unlimitedenergy(无限能量)|abyss(深渊)|worldlevel(世界等级)|bplevel(纪行等级)

查看PlayerPropertyenum以获得其他数值，格式为`PROP_MAX_SPRING_VOLUME->max_spring_volume`

**SetStats**

可更改的属性列表：hp(生命值)|maxhp(最大生命值)|def(防御力)|atk(攻击力)|em(元素精通)|er(元素充能效率)|crate(暴击率)|cdmg(暴击伤害)|cdr(冷却缩减)|heal(治疗加成)|heali(受治疗加成)|shield(护盾强效)|defi(无视防御)

元素增伤：epyro(火)|ecryo(冰)|ehydro(水)|egeo(岩)|edendro(草)|eelectro(雷)|ephys(物理)

元素抗性：respyro(火)|rescryo(冰)|reshydro(水)|resgeo(岩)|resdendro(草)|reselectro(雷)|resphys(物理)

**Weather**

天气ID可以在`./Resources/ExcelBinOutput/WeatherExcelConfigData.json`中找到。

气候类型：sunny(晴天),cloudy(多云),rain(雨),thunderstorm(雷雨),snow(雪),mist(雾)
{% endhint %}
