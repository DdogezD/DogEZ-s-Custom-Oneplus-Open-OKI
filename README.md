一加内核开源地址：[OnePlusOSS](https://github.com/OnePlusOSS/kernel_manifest)

这是一个为 Hedwig (OnePlus Open) 编译的内核。

含有以下特性：
- 使用 manual hooks 的 rksu。
- 最新的稳定版 SUSFS。
- 支持 CONFIG_TMPFS_XATTR 特性,可以使用 mountify 完成模块挂载。
- 支持以下ZRAM算法：lz4 lz4k lz4k_oplus lz4kd zstd zstdn lzo lzo-rle lz4hc 842 deflate。
- 附带一个附加脚本模块，可以使设备显示真实电量，通过一些 ZRAM 参数和 LMK 参数来优化后台性能。

已知问题：SUSFS 与 Magical 模块实现冲突，但是可以用 Mountify 来代替模块系统的挂载。

# 致谢

- **KernelSU**: 由[tiann](https://github.com/tiann)开发

- **Rissu KernelSU**: 由[rsuntk](https://github.com/rsuntk)开发

- **SUSFS**: 由[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git)开发
  
- **SUSFS Module**: 由[sidex15](https://github.com/sidex15)开发
  
- **Sultan Kernels**: 由[kerneltoast](https://github.com/kerneltoast)开发
  
特别感谢开源社区的贡献！
