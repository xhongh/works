# works
OpenWit添加
regedit
在注册表编辑器界面，依次展开“HKEY_CLASSES_ROOT\*”项，对着*项目单击鼠标右键，菜单中选择“新建”新建一个子项，并将其命名为“Shell”
对着“Shell”子项再次单击鼠标右键，仍然选择菜单中的“新建”，再新建一个“OpenWith”子项，在右侧窗口；
双击右侧窗口中的默认值，在编辑字符串界面，将数据数值设置为“打开方式”；同样方法，在“OpenWith”项下，再建一个“Command”子项，并将其默认值设置为“C：\Windows\rundll32.exe Shell32.dll，OpenAs_RunDLL %1”，确定后关闭注册表编辑器；
