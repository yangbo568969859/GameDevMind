
<p align="center">
  <img src="images/GLTOP_logo_circle_512x512.png" height="128">
  <h2 align="center">游戏开发图谱（技术侧）</h2>
  <p align="center">
    一起来解决游戏研运中各种技术相关的问题
  </p>
</p>

*[中文](https://github.com/gonglei007/GameDevMind/blob/main/README.md)* | *[English](https://github.com/gonglei007/GameDevMind/blob/main/README-en.md)*

```cpp
#include <iostream>
int main(){
    std::cout << "Hello, Game Development World!" << std::endl;
    return 0;
}
```

<br/>
<br/>

## 介绍
<p>
&emsp;&emsp;中国的游戏行业已走过几十个春秋，但时至今日，游戏开发者们每天还是要花大把时间重复的去做着别人做过的事情。<br/>
</p>
<p>
&emsp;&emsp;我们整理了一套技术侧的《游戏开发图谱》，希望能帮助游戏开发者们在处理问题的时候，能快速地看到的要考虑到哪些技术和问题。
<br/>
<p>
&emsp;&emsp;我们无法让所有做过的事情不再重复，但我们尝试共同分享，让更多游戏开发者在已知的事情上尽量节省时间。留出更多的精力投入到更有创造性的工作中去。
<br/>
</p>


<div align="center">
    <table style="width:640px;">
        <thead style="font-weight: bold; font-style: italic;">
            <tr>
                <td>&emsp;&emsp;✅ “有”什么？&emsp;&emsp;</td>
                <td>&emsp;&emsp;❌ “没有”什么？&emsp;&emsp;</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&emsp;&emsp; ✓ 用的到的知识点。&emsp;&emsp;</td>
                <td>&emsp;&emsp; × <strike>系统的知识讲解。</strike>&emsp;&emsp;</td>
            </tr>
            <tr>
                <td>&emsp;&emsp; ✓ 技术的应用和经验。&emsp;&emsp;</td>
                <td>&emsp;&emsp; × <strike>具体的实现细节。</strike>&emsp;&emsp;</td>
            </tr>
            <tr>
                <td>&emsp;&emsp; ✓ 要考虑的要点或方法。&emsp;&emsp;</td>
                <td>&emsp;&emsp; × <strike>完整的解决方案。</strike>&emsp;&emsp;</td>
            </tr>
        </tbody>
    </table>
</div>

## 总览
<p>
&emsp;&emsp;游戏研运团队在技术上需要具备几大能力：基础能力、研发能力、管理能力、商品化能力。<br/>
&emsp;&emsp;这些能力不是要每个成员都具备，但团队是需要这些能力来支撑研运游戏产品的。
</p>
<br/>

![图1、这是知识树的框架，展开的知识树可以点击下面的github链接查看。](https://github.com/gonglei007/GameDevMind/blob/main/exports/0.总览.png?raw=true)
<br/>

## 目录

### 基础能力
<p>

```cpp
团队中的技术人员都需要的具备的基本功。
这些基本功越强，整个产品的开发过程就会越稳健、高效。
```

</p>

* [1.开发技术](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.开发技术.md)
    * [1.1.客户端技术](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.客户端技术.md)
        * [1.1.1.图形与渲染](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.1.图形与渲染.md)
        * [1.1.2.物理](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.2.物理.md)
        * [1.1.3.UI](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.3.UI.md)
        * [1.1.4.声音](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.4.声音.md)
        * [1.1.5.动画与特效](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.5.动画与特效.md)
        * [1.1.6.游戏引擎](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.6.游戏引擎.md)
        * [1.1.7.平台开发](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.1.7.平台开发.md)
    * [1.2.服务端技术](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.2.服务端技术.md)
        * [1.2.1.网络与通信](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.2.1.网络与通信.md)
        * [1.2.2.数据库](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.2.2.数据库.md)
    * [1.3.通用基础](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.3.通用基础.md)
        * [1.3.1.数学](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.3.1.数学.md)
        * [1.3.2.人工智能](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.3.2.人工智能.md)
        * [1.3.4.内存管理](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.3.4.内存管理.md)
    * [1.x.开发者工具箱](https://github.com/gonglei007/GameDevMind/blob/main/mds/1.x.开发者工具箱.md)
* [2.编程语言](https://github.com/gonglei007/GameDevMind/blob/main/mds/2.编程语言.md)
    * [2.1.编程语言共通概念](https://github.com/gonglei007/GameDevMind/blob/main/mds/2.1.编程语言共通概念.md)
    * [2.2.C++语言](https://github.com/gonglei007/GameDevMind/blob/main/mds/2.2.C++语言.md)
    * [2.3.C#语言](https://github.com/gonglei007/GameDevMind/blob/main/mds/2.3.C%23%E8%AF%AD%E8%A8%80.md)
    * [2.4.JS语言](https://github.com/gonglei007/GameDevMind/blob/main/mds/2.4.JS语言.md)
* [3.程序设计](https://github.com/gonglei007/GameDevMind/blob/main/mds/3.程序设计.md)
    * [3.1.设计模式](https://github.com/gonglei007/GameDevMind/blob/main/mds/3.1.设计模式.md)
    * [3.2.数据结构](https://github.com/gonglei007/GameDevMind/blob/main/mds/3.2.数据结构.md)
    * [3.3.算法](https://github.com/gonglei007/GameDevMind/blob/main/mds/3.3.算法.md)
<br/>

### 研发能力
<p>

```cpp
游戏是一种有艺术成分的商品，它是由数字内容和互动功能构建起来的。
开发一款游戏产品，要有跟其它软件产品不同的一系列的技术、方法、流程。
```

</p>

* [4.产品研发](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.产品研发.md)
    * [4.1.客户端产品研发](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.1.客户端产品研发.md)
        * [4.1.1.客户端底层通用系统](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.1.1.客户端底层通用系统.md)
        * [4.1.2.客户端3D场景开发](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.1.2.客户端3D场景开发.md)
        * [4.1.3.客户端优化](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.1.3.客户端优化.md)
    * [4.2.服务端产品研发](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.2.服务端产品研发.md)
        * [4.2.1.服务端架构](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.2.1.服务端架构.md)
        * [4.2.2.网游网络同步](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.2.2.网游网络同步.md)
        * [4.2.3.服务端优化](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.2.3.服务端优化.md)
    * [4.3.业务层功能系统](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.3.业务层功能系统.md)
    * [4.4.游戏生产线](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.4.游戏生产线.md)
        * [4.4.1.数字内容生产线](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.4.1.数字内容生产线.md)
        * [4.4.2.系统开发生产线](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.4.2.系统开发生产线.md)
        * [4.4.3.持续交付](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.4.3.持续交付.md)
    * [4.5.技术中台](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.5.技术中台.md)
        * [4.5.1.游戏开发支持](https://github.com/gonglei007/GameDevMind/blob/main/mds/4.5.1.游戏开发支持.md)
<br/>

### 管理能力
<p>

```cpp
管理中最具挑战的是尺度、分寸与随机应变。
火候少一分，生了；火候多一分，焦了。
追求的是复杂的事情简单化，面对的也可能是简单的事情复杂化。
```

</p>

* [5.项目管理](https://github.com/gonglei007/GameDevMind/blob/main/mds/5.项目管理.md)
    * [5.1.研发过程管理](https://github.com/gonglei007/GameDevMind/blob/main/mds/5.1.研发过程管理.md)
    * [5.2.版本管理](https://github.com/gonglei007/GameDevMind/blob/main/mds/5.2.版本管理.md)
    * [5.3.质量保证](https://github.com/gonglei007/GameDevMind/blob/main/mds/5.3.质量保证.md)
    * [5.4.团队与组织](https://github.com/gonglei007/GameDevMind/blob/main/mds/5.4.团队与组织.md)
<br/>

### 商品化能力
<p>

```cpp
作为一个组织，不论你有什么样的技术或能力，一个最重要的目标是——赚钱。
在当下的市场环境下，一款好玩的游戏做出来了不一定就能够赚钱。
还需要有一系列商品化能力，才能让产品运转和盈利，让团队持续存活。

/* 这里只展示跟技术有关的那些事情 */
```

</p>

* [6.运维技术](https://github.com/gonglei007/GameDevMind/blob/main/mds/6.运维技术.md)
    * [6.1.网络维护](https://github.com/gonglei007/GameDevMind/blob/main/mds/6.1.网络维护.md)
    * [6.2.数据存储](https://github.com/gonglei007/GameDevMind/blob/main/mds/6.2.数据存储.md)
    * [6.3.资产管理](https://github.com/gonglei007/GameDevMind/blob/main/mds/6.3.资产管理.md)
    * [6.4.Linux系统](https://github.com/gonglei007/GameDevMind/blob/main/mds/6.4.Linux系统.md)
* [7.产品运营支持](https://github.com/gonglei007/GameDevMind/blob/main/mds/7.产品运营支持.md)
    * [7.1.GM后台](https://github.com/gonglei007/GameDevMind/blob/main/mds/7.1.GM后台.md)
    * [7.2.数据统计分析](https://github.com/gonglei007/GameDevMind/blob/main/mds/7.2.数据统计分析.md)
    * [7.3.产品热更新](https://github.com/gonglei007/GameDevMind/blob/main/mds/7.3.产品热更新.md)
    * [7.4.产品本地化](https://github.com/gonglei007/GameDevMind/blob/main/mds/7.4.产品本地化.md)
* [8.产品商业化](https://github.com/gonglei007/GameDevMind/blob/main/mds/8.产品商业化.md)
    * [8.1.游戏安全](https://github.com/gonglei007/GameDevMind/blob/main/mds/8.1.游戏安全.md)
    * [8.2.帐号与支付](https://github.com/gonglei007/GameDevMind/blob/main/mds/8.2.帐号与支付.md)
<br/>

## 交流讨论
欢迎进群、进讨论区交流和分享游戏开发中遇到的问题或者解决方案。

|  |  |
| --- | -------- |
| QQ群: | 242500383 [![GLTOP游戏研发与技术1群](https://pub.idqqimg.com/wpa/images/group.png)](https://qm.qq.com/cgi-bin/qm/qr?k=fy4Z65nE-5Jd1ay8FkJpDc9iPJyW3d38&jump_from=webapi) |
|  |  |
| 讨论区: | [https://github.com/gonglei007/GameDevMind/discussions](https://github.com/gonglei007/GameDevMind/discussions) |

<br/>

## 联系我们

[-微信扫码-]<br/>

<img src="https://github.com/gonglei007/GameDevMind/blob/main/images/联系人-G.L.png?raw=true" alt="drawing" width="96"/>

<br/><br/>

## 缩略预览
![图2、这个知识图谱还在持续的补充扩展中](https://github.com/gonglei007/GameDevMind/blob/main/overview/overview.png?raw=true)
<br/>

## 编辑与查看
* 资料库使用XMind编辑内容（/xminds/目录）。<br/>
* 也可以简单的查看导出图（/exports/目录）。
<br/>

## 贡献者


| [公雷(发起者)](https://github.com/gonglei007),&emsp; [Game Atom](https://github.com/gameatom),&emsp; [管仲才](https://github.com/guanzhongcai),&emsp; [王栋](https://github.com/wangdng),&emsp; ... |
| :---: |

【虚席以待...】 诚挚的邀请更多参与者来一起完善资料库。
<br/>

## 支持者
### Stargazers
[![Stargazers repo roster for @gonglei007/GameDevMind](https://reporoster.com/stars/gonglei007/GameDevMind)](https://github.com/gonglei007/GameDevMind/stargazers)
<br/>
### Forkers
[![Forkers repo roster for @gonglei007/GameDevMind](https://reporoster.com/forks/gonglei007/GameDevMind)](https://github.com/gonglei007/GameDevMind/network/members)
<br/>

## 历史
2022-06-22
第一个版本的资料库提交到了github。
<br/>

