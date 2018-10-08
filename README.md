# NJULabReport
**文献综述的模板在`\template_windows.tex`，下载这一个文件即可，Build步骤同下，也要使用XeLaTex。**

LabReport模板，从[南理工实验报告模板](https://github.com/DocF/NjustLabReport)Fork,由Shaloc修改。

推荐使用Windows 10系统完成以下操作，否则某些字体可能无法正确编译/显示。

## Requirments
- [TexLive](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images)
- [TexStudio](https://www.texstudio.org/)

## Build
选项 - 设置TexStudio - 构建 - 默认编译器，选择XeLaTex，然后点击构建并查看![Build](https://i.loli.net/2018/10/08/5bbb16ea17c4e.png)即可。

## Fixups: 如果没出现可以忽略
- Package minted Error: You must invoke LaTeX with the -shell-escape flag.
* 在选项 - 设置TexStudio - 命令 - XeLaTex 中加入 `-shell-escape`
- Package minted Error: You must have pygmentize installed to use this package. 
* 安装Python, 然后`pip install -i https://pypi.tuna.tsinghua.edu.cn/simple Pygments`

## 推荐阅读
- [Begin-Latex-in-minutes](https://github.com/luongvo209/Begin-Latex-in-minutes/blob/master/Translation:Chinese.md#%E5%88%97%E8%A1%A8)


