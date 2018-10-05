# NJULabReport

LabReport模板，从[南理工实验报告模板](https://github.com/DocF/NjustLabReport)Fork,由Shaloc修改。

推荐使用Windows 10系统完成以下操作，否则某些字体可能无法正确编译/显示。

## Requirments
- Python
- [TexLive](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images)
- [TexStudio](https://www.texstudio.org/)

## Make
选项 - 设置TexStudio - 构建 - 默认编译器，选择XeLaTex

## FAQS
- Package minted Error: You must invoke LaTeX with the -shell-escape flag.
-- 在选项 - 设置TexStudio - 命令 - XeLaTex 中加入 `-shell-escape`
- Package minted Error: You must have pygmentize installed to use this package. 
-- 安装Python, 然后`pip install -i https://pypi.tuna.tsinghua.edu.cn/simple` Pygments

## 推荐阅读
- [Begin-Latex-in-minutes](https://github.com/luongvo209/Begin-Latex-in-minutes)


