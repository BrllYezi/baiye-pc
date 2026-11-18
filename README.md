# 白叶零售 PC 收银端安装包

这个仓库只放安装包，不放源码。

- 下载与自动更新统一走 https://baiyepos.xyz （安装包本身在 Releases 里，由我们的服务器转发）
- Release 的 tag 形如 `pc-v0.6.67`，资产是 `BaiyePOS-<版本>-win7-11-<x64|ia32>[-portable].{zip,exe}`
- 支持 Windows 7 SP1 / 10 / 11，解压或存放请用英文路径

新版由 `docs\download\publish-pc.ps1` 上传，随后 `scripts/set-release.mjs --github BrllYezi/baiye-pc` 写发布记录。