# 首次运行测试情况

测试例40,成功9,失败31

[完整输出日志](./.assest/part3-output.1.log)

测试成功项：

* oe_test_IOaccess_100Mfile
* oe_test_net_cmd_ping
* oe_test_kernel_module_operation
* oe_test_kernel_sysctl
* oe_test_IOaccess_500Mfile
* oe_test_man
* oe_test_group_access
* oe_test_IOaccess_1Gfile
* oe_test_net_cmd_telnet

翻阅输出日志，发现存在一系列依赖项问题，遂安装部分依赖项后重新对测试失败项进行测试

## 第二次测试运行情况


--------

目前遇到的问题：
运行到某个测试例后系统崩溃无法响应，怀疑是依赖环境的问题。
