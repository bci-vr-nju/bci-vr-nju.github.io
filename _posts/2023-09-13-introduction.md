---
layout: post
title:  脑机接口(BCI)与VR技术的融合与应用-大创项目介绍 
date:   2023-09-13 22:08:00 
description: 项目启动介绍 
tags:  
categories: project
featured: true
giscus_comments: true
related_posts: false
---

# 什么是脑机接口? 脑机接口与VR能够产生怎样的化学反应?

脑机接口(Brain Computer Interface)一直以来都是科幻小说、动漫与科幻电影的热点话题。不仅如此, 从马斯克创办Neuralink, 到米哈游入局投资脑机接口, 在现实生活中, BCI也获得了越来越多的注意力.

相信不少人都看过《刀剑神域》这部动漫。在这部动漫中主角们通过脑机接口技术与虚拟现实技术前往游戏世界中进行冒险。依托于脑电信号的输出和头戴式设备提供的视觉输入, 动漫里的人物能够身临其境地沉浸于游戏世界. 这样的技术在现实中也存在该有多好! 

好的消息是, 得益于VR技术的日趋成熟和脑机接口的初步发展, 已经有不少科研团队和初创公司开始在脑机接口以及"脑机+VR"领域进行尝试, 如下图所示, 国外Galea公司就研发了集成了读取脑电信号的VR头戴设备, 能够获取实时的脑电信号来增强交互体验. 然而, 不得不指出的是, 在2023年的今天, 脑机接口的潜力还远没有被开发出来, 人们对大脑的诸多期待, 例如实现真正的脑-机沟通、将大脑数据上传电脑、实现数字永生等等, 还需要科研人员长期的努力.


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/djsy.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/galea.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    从动漫到现实: 我们所想象的一切, 正在变为现实.
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://player.bilibili.com/player.html?aid=658284353&bvid=BV1Bh4y1Z7kb&cid=1192479953&p=1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.youtube.com/embed/uhLxggasiqE?si=b8VQAoCYKgE8VwUs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

看完上面的两个视频, 相信你会对脑机和"BCI-VR"产生更多的理解. 可以预见的是, 这项前沿技术正在快速崛起, 就像历史上的AI技术一样, 在多年后将会给人类生活的方方面面带来颠覆性的革命. 

为了让脑机接口技术落地, 与人们的日常生活产生更多的联系, 也得益于学校的硬件支持, 本大创项目选择将BCI与VR联系起来, 以脑机和虚拟现实两大前沿科技的交叉口作为出发点, 

- 一方面, 让脑机交互为虚拟现实技术赋能, 实现人脑直接与虚拟场景的交互, 让脑机技术作为人机交互的新渠道.
- 另一方面, 让虚拟现实作为脑机技术的落脚点, 为脑机接口技术提供应用场景, 让脑机接口技术不仅助力残疾人士, 而是成为人人都能体验到的新兴技术.

具体来说, 本大创项目计划实现的两条路线: 

1. [运动意图识别]目前, 在虚拟现实场景中的移动主要依赖用户在真实世界中的走动. 然而在真实世界中, 头戴VR设备的移动往往受限, 同时也不适合长时间走动. 通过读取大脑信号识别运动方向(前后左右)[已经有前辈同学的经验积累👏], 从而实现通过大脑发出运动意图来直接操纵虚拟场景中的移动, 获得身处梦境的沉浸感.
2. [情感识别]情感脑机接口能够实现读取用户实时的心理状态(如积极/中立/消极, 以及专注/放松程度), 将实时读取的脑电信号解码为情感状态, 探索VR的全新交互维度.


最后, 一句话介绍项目: 通过非侵入式设备读取脑电信号, 使用机器学习算法进行意图识别, 将结果输入VR, 从而实现人机交互模式上的探索与创新.