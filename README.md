# 防止iPhone被黑：iOS安全

* 最新版本：`v0.6`
* 更新时间：`20210525`

## 简介

介绍iOS安全，防止你的iPhone被黑。先介绍iOS安全的概览。再介绍iOS操作系统层面的安全机制。再整理iOS的安全和破解相关的工具和技术，包括Mac的逆向工具Hopper Disassembler；Linux的编译套件LLVM及相关的LLDB和Obfuscator-LLVM；Linux的调试器lldb-server、逆向工具Miasm、radare2及相关的Cutter；以及iOS的各种工具，包括正向的混淆工具ios-class-guard；破解方面，调试器debugserver，插件开发的MonkeyDev，苹果二进制格式Mach-O的处理工具class-dump、MachOView、jtool、otool等；砸壳工具bfinject、Clutch、Dumpdecrypted、frida-ios-dump；越狱工具Cydia Substrate、frida、Electra、unc0ver。最后给出参考资料。

## 源码+浏览+下载

本书的各种源码、在线浏览地址、多种格式文件下载如下：

### Gitbook源码

* [crifan/prevent_iphone_hacked_ios_security: 防止iPhone被黑：iOS安全](https://github.com/crifan/prevent_iphone_hacked_ios_security)

#### 如何使用此Gitbook源码去生成发布为电子书

详见：[crifan/gitbook_template: demo how to use crifan gitbook template and demo](https://github.com/crifan/gitbook_template)

### 在线浏览

* [防止iPhone被黑：iOS安全 book.crifan.com](http://book.crifan.com/books/prevent_iphone_hacked_ios_security/website)
* [防止iPhone被黑：iOS安全 crifan.github.io](https://crifan.github.io/prevent_iphone_hacked_ios_security/website)

### 离线下载阅读

* [防止iPhone被黑：iOS安全 PDF](http://book.crifan.com/books/prevent_iphone_hacked_ios_security/pdf/prevent_iphone_hacked_ios_security.pdf)
* [防止iPhone被黑：iOS安全 ePub](http://book.crifan.com/books/prevent_iphone_hacked_ios_security/epub/prevent_iphone_hacked_ios_security.epub)
* [防止iPhone被黑：iOS安全 Mobi](http://book.crifan.com/books/prevent_iphone_hacked_ios_security/mobi/prevent_iphone_hacked_ios_security.mobi)

## 版权说明

此电子书教程的全部内容，如无特别说明，均为本人原创和整理。其中部分内容参考自网络，均已备注了出处。如有发现侵犯您版权，请通过邮箱联系我 `admin 艾特 crifan.com`，我会尽快删除。谢谢合作。

## 鸣谢

感谢我的老婆**陈雪**的包容理解和悉心照料，才使得我`crifan`有更多精力去专注技术专研和整理归纳出这些电子书和技术教程，特此鸣谢。

## 更多其他电子书

本人`crifan`还写了其他`100+`本电子书教程，感兴趣可移步至：

[crifan/crifan_ebook_readme: Crifan的电子书的使用说明](https://github.com/crifan/crifan_ebook_readme)
