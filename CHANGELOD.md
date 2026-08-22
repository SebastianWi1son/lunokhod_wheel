# Changelog

## v0.1.0 (2026-08-22)
- LPF / Ramp / SmoothPlanner（dsp 工具集移植）
- PID（工业级：微分先行/梯形积分/积分分离/抗饱和/输出斜坡开关，Config 聚合配置）
- Wheel（SmoothPlanner + PID + 函数指针回调，单位无关接口）
- 五组件锚点测试 + 电机模型闭环仿真（0.7s 收敛 ±5%）