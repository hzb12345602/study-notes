# 学习思考随笔 · Notes on Systems

> 一个学习者的知识图谱：从信号处理到系统底层。
> A learner's knowledge graph — from signal processing to the bare metal.

记录我在学习过程中的思考、比喻和笔记。中文原创，英文翻译持续进行中。
Thoughts, analogies, and study notes from my learning journey. Chinese originals, English translations in progress.

## 目录结构 · Repository Layout

```
zh/        中文原稿 Chinese originals
en/        英文翻译 English translations（翻译进行中 in progress）
exports/   发布产物（docx 等）Published artifacts
assets/    图片资源 Images
```

## 中文笔记索引 · Index (zh)

### 信号处理与数字滤波 · Signal Processing & Digital Filters

- [傅里叶告诉我的事：秩序不是目标，信噪比才是](zh/数字信号26.8.20.md)
- [MATLAB 把滤波器设计变成了一个按钮：便利、代价与思维差异](zh/MATLAB26.8.23.md)
- [滤波器量化误差笔记：位数截断后的每一步](zh/量化误差笔记26.8.23.md)
- [FIR 是复习，IIR 是思考：滤波器里藏着两种学习方式](zh/26.8.28滤波器.md)

### 语言与抽象 · Languages & Abstraction

- [从 UART 到语言：所有通信都是"预先约定"](zh/26.9.8通信协议和语言.md)
- [自举：一门语言的成人礼](zh/rust初学有感26.9.16.md)

### 系统与内存 · Systems & Memory

- [内存：从硬件到虚拟内存](zh/26.9.17内存硬件和虚拟内存.md)
- [PC/嵌入式：内存与寄存器](zh/26.9.27PC嵌入式内存和寄存器.md)
- [FreeRTOS 与 PC 端：静态 vs 动态内存](zh/26.9.28freeRTOS和PC端静态和动态差异.md)
- [单片机内存、计算机内存与存储区分](zh/26.11.19单片机内存计算机内存及存储区分.md)

### 底层与逆向 · Low-level & Reverse Engineering

- [逆向工程入门：读懂汇编与链接产物](zh/26.10.12逆向工程.md)
- [反汇编基础速记](zh/反汇编基础速记.md)

### 体系与历史 · Architecture & History

- [软件、操作系统与硬件：三条线的互相推动](zh/26.10.13软件操作系统和硬件.md)

### 并行计算 · Parallel Computing

- [CUDA 概念复习：Block / Warp / Tile / SM](zh/26.10.21CUDA概念复习.md)

## 英文翻译进度 · Translation Progress

| 状态 | 数量 |
| :--- | :--- |
| 已翻译 Translated | 0 |
| 待翻译 Pending | 14 |

> 翻译计划：保持中文原稿不动，在 `en/` 下建立同名英文版，边翻译边打磨专业英语术语。
> Translation plan: keep the Chinese originals intact, mirror them under `en/`, and sharpen technical-English terminology along the way.

## 说明 · Notes

- 所有内容为个人学习笔记，可能存在理解偏差，欢迎指正。
- These are personal study notes and may contain misunderstandings — corrections are welcome.
