---
title: "项目成果"
excerpt: "国家自然科学基金“大规模MIMO无线通信系统中传输优化理论和技术研究”的研究成果-1"
collection: portfolio
---
## 毫米波多用户干扰降低算法

###### 作者：丁亚迪

###### 日期：2020-01-07

本研究组在2018  IEEE  4th  International  Conference on  Computer and Communications （http://www.iccc.org/）发表论文，其核心内容如下：

在多用户毫米波大规模MIMO系统中，由于系统中存在多个用户，不同用户向基站发送的信息也不同，那么当基站同时收到多个用户发来的信息时，便会存在一定的干扰。当干扰较为严重的时候，系统容量便得不到保证。

针对这一问题，在借鉴前期相关工作的基础上，提出一种最大化最小相位差的混合波束成形算法。假设此时系统中多个单天线终端同时向一个多天线基站发送信息，基站采用混合波束成形接收信号，集中于基站端混合波束成形的设计。对于任意用户，基站端选出高于路径增益平均值的路径，然后从码本中选出与这些路径波达角角度差最小的码本，作为候选码本集合。然后将其他用户信道向量近似成码本向量的形式，将近似后的信道向量相位的正弦值分别与候选码本相位的正弦值做差，取出每次计算的最小值。这些最小值中的最大值则是干扰最小的，这个最大值对应的码本便是该用户的模拟波束成形向量。多次计算便可得到全部用户的模拟波束成形矩阵，数字波束成形矩阵根据信道矩阵与模拟波束成形矩阵采用最小均方误差准则求得。在进行混合波束成形设计前，将用户分组，有针对的降低用户间干扰，达到提高系统容量的目的。该研究发表的论文链接为[https://github.com/anzhonghu/Maximizing-minimum-phase-difference-based-hybrid-beamforming-for-multiuser-mmWave-massive-MIMO-syste](https://github.com/anzhonghu/Maximizing-minimum-phase-difference-based-hybrid-beamforming-for-multiuser-mmWave-massive-MIMO-syste)。该研究得到了国家自然科学基金“大规模MIMO无线通信系统中传输优化理论和技术研究”(编号61601152)资助。
