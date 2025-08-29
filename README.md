一加内核开源地址：[OnePlusOSS](https://github.com/OnePlusOSS/kernel_manifest)

这是一个为 Hedwig (OnePlus Open) 编译的内核。

含有以下特性：
- 使用 manual scope-minimized hooks 的 KernelSU Next。
- 支持 CONFIG_TMPFS_XATTR 特性,可以使用 mountify 完成模块挂载。
- 默认伪装成最新 Oneplus Open NA 的内核名称。

已知问题：SUSFS 与 Magical 模块实现冲突，但是可以用 Mountify 来代替模块系统的挂载。

# 致谢

- [KernelSU](https://github.com/tiann/KernelSU)

- [KernelSU Next](https://github.com/KernelSU-Next/KernelSU-Next)
  
- [KernelSU Coccinelle](https://github.com/devnoname120/kernelsu-coccinelle)
  
特别感谢开源社区的贡献！
