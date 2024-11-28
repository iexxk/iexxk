## butane自动话
#### 需求说明
通过该方式，就不用在本地安装butane，然后直接可以在线配置，并转换成在线系统用的json配置
运行butane将YAML文件转换为JSON Ignition配置。
#### 步骤
1. 点击`Actions->执行butane转换->run workflow`会将fedora-core-config.yaml文件转成fedora-core-config.ign
2. 然后获得ign的链接[https://raw.githubusercontent.com/iexxk/iexxk/refs/heads/main/fedora-core-config.ign](https://raw.githubusercontent.com/iexxk/iexxk/refs/heads/main/fedora-core-config.ign)，就可以通过该链接的配置进行安装fedora-coreos的系统了。
#### 扩展说明
如果还需要其他配置文件，在当前仓库新建一个yaml，在`run workflow`步骤的将路径参数里面的值修改为新建的文件名，然后就会生成对应的ign配置。
<!---
iexxk/iexxk is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
