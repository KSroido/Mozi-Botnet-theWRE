# WRE-Botnet

This is a bot net implement. Here is [English README](https://github.com/KSroido/Mozi-Botnet-theWRE/blob/main/README_EN.md)

用于自学安全知识的一个项目,模仿mozi僵尸网络实现(md5: 849b165f28ae8b1cebe0c7430f44aff3 , SHA256: c6f6ca23761292552e6ea5f12496dc9c73374be0c5f9d0b2142ca3ae0bb8fe14)

本项目仅用于自学,请勿用于任何非法用途,任何基于本项目及其改编版本的项目进行的网络攻击与原作者无关

也正是基于以上原因, 本项目未做任何免杀与混淆,请悉知

欢迎合作，欢迎开issue和PR

# 僵尸病毒感染数据流示意图与感染流程

[![jxIz3q.png](https://s1.ax1x.com/2022/07/26/jxIz3q.png)](https://imgtu.com/i/jxIz3q)

作者可以通过p2p的僵尸网络安全的更新僵尸网络代码

因为我们难以在p2p网络中确定作者的设备是否只是一个被感染的普通设备，因为p2p网络中的数据是共享的（就像比特币的链一样，每个人都拥有相同的比特币链，但是没有人能声明这些数据属于自己，即使作者也无法声明）

# 开源协议

MIT License

Copyright (c) 2009-2017 Dave Gamble and cJSON contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

另外，感谢以下开源项目，没有他们本项目便难以实现

* https://github.com/DaveGamble/cJSON

* https://github.com/fatedier/frp

* https://github.com/embedthis/goahead

* https://github.com/mkj/dropbear

<!-- * https://gitee.com/KSroido/http-downloader -->

# TODO list

- [x] 整合goahead轻型中间件到项目中

- [ ] 整合轻型交叉编译环境到项目中

- [ ] 隧道与代理

- [ ] 去中心化的p2p平级通信协议实现

- [ ] 对僵尸网络的指令下达与指令鉴定（json数据包，GPG私钥签名）（这点会成为查杀的指纹，因此本项目不设混淆）

- [ ] 添加从网上收集的iot通杀Nday payload与攻击exp

- [ ] 利用fofa API查找未被感染的设备
