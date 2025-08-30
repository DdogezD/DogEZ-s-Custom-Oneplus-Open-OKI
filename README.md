一加内核开源地址：[OnePlusOSS](https://github.com/OnePlusOSS/kernel_manifest)

这是一个为 Hedwig (OnePlus Open) 编译的内核。

含有以下特性：
- 使用 manual scope-minimized hooks 的 KernelSU Next。

- 尝试整合 KernelSU Next KPM 分支的内容。

- 支持 CONFIG_TMPFS_XATTR 特性,可以使用 mountify 完成模块挂载。
  - 使用方法：启用 Magic_Mount，然后安装Mountify。
  - 配置完成后，在 "/data/adb/ksu/" 下创建 ".notmpfs" 和 ".nomount" 文件。
  
- 默认伪装成最新 Oneplus Open NA 的内核Linux version, 在版本号上与官方版只有构建时间区别。

# 致谢

- [KernelSU](https://github.com/tiann/KernelSU)

- [KernelSU Next](https://github.com/KernelSU-Next/KernelSU-Next)
  
- [KernelSU Coccinelle](https://github.com/devnoname120/kernelsu-coccinelle)
  
特别感谢开源社区的贡献！
