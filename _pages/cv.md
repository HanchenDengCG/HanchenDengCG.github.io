---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 北京航空航天大学 2023.9 – 至今
  * 硕士 计算机学院 计算机科学与技术
  * 虚拟现实系统与技术国家重点实验室

* 北京航空航天大学 2019.9 – 2023.6
  * 本科 计算机学院 计算机科学与技术

奖项
======
* 国家奖学金 2024
* 校级学业奖学金 2023、2024

实习经历
======
* 腾讯魔方工作室 Unity客户端/引擎开发 2024.10 – 2025.2
  * 客户端方面
    * 深入IL2CPP构建的C++代码，排查并解决Smaller构建导致的泛型数据丢失问题
    * 修改构建过程中统计AssetBundle的逻辑，提升统计数据稳定性
    * 设计CI工具统计资源增长和冗余情况，设计Editor工具帮助查看资源情况
  * 引擎方面
    * 基于项目的URP管线C#代码，优化移动端性能开销，在所有档次测试机上性能提升均超过10%

* 太极图形 Unity客户端开发 2021.10 – 2022.2
  * 独立完成首个taichi编程语言在Unity上运行的demo

专业技能
======
* 编程语言: C/C++、C#、Python
* 游戏引擎: Unity、Unreal
* 图形API: OpenGL/GLSL、HLSL

科研论文
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
