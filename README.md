# 质粒组装器 · Windows 安装版

[下载 Windows x64 安装程序](https://github.com/xietiansong/PlasmidAssembler-Windows/releases/latest)

## 安装与使用

1. 在发布页面的 **Assets** 下下载 `PlasmidAssembler_Setup_Windows_x64_v1.0.1.exe`。
2. 双击安装程序，按向导完成安装。从开始菜单或桌面快捷方式启动「质粒组装器」。
3. 选择 `.fastq`、`.fq`、`.fastq.gz` 或 `.fq.gz` 测序文件，粘贴覆盖完整一圈的质粒模板序列或 FASTA。
4. 点击「开始组装」。完成后可保存共识 FASTA 和报告。

软件在本机离线运行，无需另装 Python 或 WSL。它根据读段和模板生成质粒共识序列。请结合覆盖度、未解决位点和环状连接处的读段支持检查结果。

安装程序适用于 Windows x64。目前没有代码签名，Windows 可能显示未知发布者提示。

## SHA-256

`96f4afb094f4a188a5f1c9d5729ab7f06386cc3901b20ed5d1e4af0a11917664`
