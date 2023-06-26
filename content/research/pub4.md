---
title: "The Actual Cost of Programmable SmartNICs: diving into the existing limits"
date: 2021-01-01T00:00:00-00:00
draft: false
---

**Abstract**
Programmable Data Planes is a novel paradigm that enables efficient offloading of network applications. An important enabler for this paradigm is the current available SmartNICs, which should satisfy rigid network requirements such as high throughput and low latency. Despite recent research in this field, not much attention was given to understand the costs and limitations of offloading network applications into SmartNIC devices. Existing offloading approaches either neglect the existing limitations of SmartNICs or assume that as a fixed cost – leading, therefore, to sub-optimal offloading approaches. In this work, we conduct a comprehensive evaluation of SmartNICs in order to quantify existing performance limitations. We provide insights on network performance metrics such as throughput and packet latency while considering different key building blocks of complex P4 programs (e.g., registers, cryptography functions, or packet recirculation). Results show that line-rate throughput can degrade up to 8x, while latency can increase as much as 80x when performing memory-intensive operations in the data plane.

**Published in:** [2021 AINA](https://link.springer.com/book/10.1007/978-3-030-75100-5)

[**Full Paper Link**](https://link.springer.com/chapter/10.1007/978-3-030-75100-5_17)