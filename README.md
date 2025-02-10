# DirectX 12 黑魔法教程：从 Simple Triangle 到 3A 级渲染 —— RTX 9090 Ti Super：我燃尽了！

### 持续更新中！阅读过程中有任何问题留个 Issue 一起交流！

## 阅读前提示

早在远古时期，还是萌新宝宝的作者就想要学习 DX12 开发，然而陡峭的学习曲线却让他差点夭折，虽然他一直苦中作乐、溺于其中，但是这种经历也让他深知一个教程对初学者的重要性，为此他开始整理本仓库，希望这个项目能够：(1) 提供一站式的入门体验；(2) 以最直观的方式介绍 DX12 的开发流程；(3) 让初学者的前进之路不再崎岖坎坷！

## 0. Simple Triangle

### 0.1. (建议) 配置 DirectXShaderCompiler
### 0.2. (可选) 配置 DirectX 12 Agility SDK
### 0.3. (建议) 配置 D14UIKit 用于图形交互

## 1. Colorful Cube

## 附录1：推荐书籍

<table><tr>
<td><img src="https://media.githubusercontent.com/media/yiyaowen/DX12-Tutorial/main/images/Computer Graphics, 3rd Edition.jpg"/></td>
<td>Computer Graphics, 3rd Edition<br><br>计算机图形学众多经典教程之一</td>
</tr><tr>
<td><img src="https://media.githubusercontent.com/media/yiyaowen/DX12-Tutorial/main/images/Introduction to 3D Game Programming with DirectX 12.jpg"/></td>
<td>Introduction to 3D Game Programming with DirectX 12<br><br>Frank D. Luna 大叔力作，从当年的 DirectX 9 (红龙封面) 到如今的 DirectX 12，本本都是经典教程</td>
</tr><tr>
<td><img src="https://media.githubusercontent.com/media/yiyaowen/DX12-Tutorial/main/images/Introduction to 3D Game Programming with DirectX 12_zh-CN.jpg"/></td>
<td>DirectX 12 3D 游戏开发实战<br><br>上书的中文翻译版，被广大开发者亲切地称为 (DX12 龙书)，可见其内容质量和影响力</td>
</tr><tr>
<td><img src="https://media.githubusercontent.com/media/yiyaowen/DX12-Tutorial/main/images/Real-Time Rendering, Fourth Edition.jpg"/></td>
<td>Real-Time Rendering, Fourth Edition<br><br>实时渲染，深入浅出地介绍实时渲染领域的各种细节，据说正在进行中文版的翻译工作</td>
</tr><tr>
<td><img src="https://media.githubusercontent.com/media/yiyaowen/DX12-Tutorial/main/images/Physically Based Rendering, Third Edition.jpg"/></td>
<td>Physically Based Rendering, Third Edition<br><br>基于物理的渲染，主要介绍一个离线光追渲染器的实现，被简称为 pbrt3 (2016出版)，pbrt4 即将成书，参见<a href="https://github.com/mmp/pbrt-v4">Github-pbrt4</a></td>
</tr></table>

## 附录2：在线教程

[vulkan-tutorial：入门 DX12 后再看 Vulkan 就很简单了，可以配合 Khronos 文档了解 API 细节](https://vulkan-tutorial.com/)

[Ray Tracing in One Weekend：学习离线光追的原理，更好地理解和使用实时光追（硬件加速）](https://raytracing.github.io/)
