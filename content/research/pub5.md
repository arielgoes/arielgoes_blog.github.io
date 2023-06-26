---
title: "Towards Efficient Selective In-Band Network Telemetry Report using SmartNICs"
date: 2022-01-01T00:00:00-00:00
draft: false
---

**Abstract**
In-band Network Telemetry (INT) is a promising network monitoring approach that allows broad and fine-grained network visibility. However, when a massive volume of telemetry data is reported to an INT collector, there might overload the whole network infrastructure, while still degrading the performance of packet processing at the INT sink node. As previously reported in the literature, programmable devices – in particular, SmartNICs – have strict constraints in terms of processing and memory. In this work, we propose to design and implement a lightweight Exponentially Weighted Moving Average based mechanism inside the SmartNIC data plane in order to assist the decision-making process of reporting INT data. By evaluating our solution in state-of-the-art SmartNICs, we show that our proposal can decrease the number of nonessential telemetry data sent to INT collectors by up to 16X compared to the de-facto INT approach while presenting minor overhead in terms of packet latency.

**Published in:** [AINA 2022](https://link.springer.com/book/10.1007/978-3-030-99584-3)

[**Full Paper Link**](https://link.springer.com/chapter/10.1007/978-3-030-99584-3_24)