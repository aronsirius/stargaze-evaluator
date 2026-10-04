# 开发日志索引 · stargaze-evaluator

> 本目录按日期记录项目迭代，每日文件命名 `YYYY-MM-DD.md`。每日自动开发日志已于 2026-10-04 暂停，改为手动记录。

## 里程碑

- **2026-09-16** 项目初始化：本地评估器初版（Open-Meteo 天气 + 手动 Bortle 滑块 + 保存地点）。同日修复天文接口失效（内联 SunCalc 1.9.0 本地算法，天文部分彻底离线）。新增 📍 定位按钮。
- **2026-10-04** 升级：未来两天（今晚 + 明晚）观星条件预告，结果用标签页切换；光污染改为「天文通一键核对」+ 手动滑块（无稳定免费自动 Bortle API）。每日自动日志暂停，改为手动记录。同日开启 GitHub Pages（https://aronsirius.github.io/stargaze-evaluator/），定位按钮在 https 下可用。

## 数据源

- 天气：Open-Meteo（免费、无需密钥、CORS 友好）
- 天文（黑夜窗口 / 月相）：SunCalc 1.9.0 本地算法（离线，永不掉链子）
- 光污染：天文通 DarkMap 地图人工核对（无自动 API，见 2026-10-04 日志说明）

## 待办

- [ ] 视宁度真实值接入（Clear Outside 等，待国内可直连）
- [ ] 常用拍摄点预设（一键评估）
- [x] GitHub Pages 已开启（https://aronsirius.github.io/stargaze-evaluator/，定位功能在 https 下可用）
