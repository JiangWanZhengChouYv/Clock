# Clock

轻量级网页时钟（版本 1.0.0）。

直接打开根目录下的 index.html 即可查看时钟界面。

## 功能
- 实时显示当前时间（小时:分钟:秒）
- 可切换 12/24 小时制（如实现）
- 支持显示日期（年-月-日）
- 支持本地时区显示，部分实现可切换时区
- 响应式界面，适配桌面与移动设备

## 快速开始
1. 克隆仓库或下载 ZIP：
   ```bash
   git clone https://github.com/JiangWanZhengChouYv/Clock.git
   ```
2. 在本地直接打开 `index.html`（双击或在浏览器中打开文件）即可使用。
   - 若浏览器对本地文件有权限限制，可使用静态服务器：
     ```bash
     python -m http.server 8000
     # 然后在浏览器打开 http://localhost:8000/index.html
     ```

## 演示
（这里建议放置界面截图或演示 GIF，便于用户直观了解外观与功能）

## 支持的浏览器
- 现代浏览器：Chrome、Firefox、Edge、Safari

## 文件结构（简要）
- index.html — 主界面（运行时直接打开）
- css/ 或 styles/ — 样式文件（若存在）
- js/ — 脚本文件（若存在）
- README.md — 项目说明（本文件）

## 贡献
欢迎提交 issue 和 PR：
- 提交 bug 报告请说明重现步骤与浏览器信息。
- 提交新功能建议请描述预期行为与用例。

## 许可证
本项目使用 MIT 许可证，见仓库根目录的 LICENSE 文件。

## 作者
JiangWanZhengChouYv

## 版本历史
- 1.0.0 — 初始版本（包含基础时钟功能）
