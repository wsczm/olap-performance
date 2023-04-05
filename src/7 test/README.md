---
title: 7 性能测试
icon: creative
---

## 如何做好性能测试

* 对比测试：硬件环境，数据，建模等基础信息对齐 (出过很多次问题)
* 不同硬件 (核数多少，磁盘介质，出过多次问题)
* **不能只关注单并发，还要关注高并发**
* **不能只关注延迟和吞吐，还要关注资源利用率**
* **不能只关注 AVG，还要关注PT99和抖动**
* **不能只关注目标场景，各种典型 Workload 的查询都要测试**
* 要能压出系统的能力边界
* 要有丰富的，各种细粒度的监控指标
* **细致，周密，敏锐，自动化，标准化**