# 简介

一个完整的emsdk，解决在安装 emscripten 的时候遇到的网络问题：无法访问；下载失败；下载慢。


# emsdk

emsdk是一个工具，用来安装 emscripten ，emscripten 是一个WebAssembly的一个完整的编译器工具链。可以用来将 c 代码编译为 wasm 并提供给 Javascript 调用。


* emsdk 的github地址：https://github.com/emscripten-core/emsdk
* emscripten 官网：https://emscripten.org/
* emscripten 安装教程：https://developer.mozilla.org/zh-CN/docs/WebAssembly/C_to_wasm

然而在使用 emsdk 安装 emscripten 的时候总会遇到各种各样的网络问题，并且全网没有一个完整版本的 emsdk ，能够找到的资料都是编写的各种python脚本，这种只能简化emscripten的安装，无法规避网络问题。此仓库提供一个完整版本的 emsdk 的安装程序，下载此安装程序后就可以得到一个完整版本的 emscripten （v3.1.54）。配置环境变量后就可以直接使用了。

# 如何获取完整的 emsdk

emsdk编译好的完整版太大了，无法放在github中，本仓库并不存，可以通过如下方式获取：

* 关注微信公众号“TechnologyRamble”并回复“emsdk”关键词获取
* 发送邮件，收信之后私发

  
# 其它版本

需要其它版本请提交Issues，或者邮箱联系我。
