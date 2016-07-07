# FloorPlanCreator
破解 Floor Plan Creator.apk 方法

===================

应用名称：Floor Plan Creator.apk (中文名：创建平面图)

应用包名：pl.planmieszkania.android

备注：此应用需通过 应用内购 升级为 Pro版

破解方法：

① 首先，反编译 Floor Plan Creator.apk，然后反编译 classes.dex。

② 找到 com/ml/planik/android/o.smali 文件并打开，定位到如下代码：


.method public a()V
    .registers 4

    .prologue
    const/4 v1, 0x0     //将 0x0 修改为 0x1

    .line 68
    iget-object v0, p0, Lcom/ml/planik/android/o;->b:Landroid/content/SharedPreferences;


按照上述说明修改然后保存。

最后编译，然后安装 Floor Plan Creator Pro.apk 啦。

好了，破解到此完成！

==================

【特别声明】

→ 不保证上述破解方法永久有效！ 如果此应用开发者重新修改代码，那上述破解方法就失效！这你必须要清楚明白！

→ 开发者敲字母编写程序代码也不容易，如果你条件(不管是经济还是网络条件)允许，还是请支付美元购买原版！以支持开发者的开发工作。

→ 我破解是因为我没有上述那个条件。穷逼的破解者一个。 如果你愿意，请捐赠以支持我的破解工作。

→ 如果有问题，请 <a href=https://github.com/APK-Patched/FloorPlanCreator/issues>在此</a> 提交你的问题。
