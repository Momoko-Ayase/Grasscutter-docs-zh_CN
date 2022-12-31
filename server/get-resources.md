# 📦 获取资源文件

在Grasscutter目录下运行以下指令：

{% tabs %}
{% tab title="Windows CMD" %}
```batch
git clone https://gitlab.com/yukiz/GrasscutterResources.git
mklink /J Resources GrasscutterResources\Resources
```
{% endtab %}

{% tab title="Windows Powershell" %}
```powershell
git clone https://gitlab.com/yukiz/GrasscutterResources.git
cmd /c mklink /J Resources GrasscutterResources\Resources
```
{% endtab %}

{% tab title="Linux" %}
```bash
git clone https://gitlab.com/yukiz/GrasscutterResources.git
ln -s ./GrasscutterResources/Resources Resources
```
{% endtab %}
{% endtabs %}
