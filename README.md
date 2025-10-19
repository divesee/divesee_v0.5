# divesee_v0.5
# Divesee 潜读 工具（网页和插件双端） v0.5

> 中文沉浸式阅读引擎 · 让你“一眼看清重点”


## 关于这个仓库

本仓库用于 **发布 Divesee 潜读 的 Release 版本**，以及通过 **GitHub Issues 收集与跟进用户反馈**。

> 说明：*Divesee 潜读* 当前 **并非开源软件**，本仓库 **不包含源代码**。旧版开源尝试仅作存档参考，不再维护。

---

## 链接

* **用户帮助**：[https://www.divesee.com](https://www.divesee.com)
* **插件下载**（网盘离线包）：**Divesee-v0.4.2**
  链接：[https://pan.baidu.com/s/1GhyS5tmCBNbVlKRUzlu3dw?pwd=nb5w](https://pan.baidu.com/s/1GhyS5tmCBNbVlKRUzlu3dw?pwd=nb5w)
  提取码：`nb5w`
* **GitHub 更新**：[https://github.com/divesee/Divesee-v0.4.2/](https://github.com/divesee/Divesee-v0.5/)
* **双 Demo 演示视频**：[https://cloud.189.cn/web/share?code=uUrqmmNziyum](https://cloud.189.cn/web/share?code=uUrqmmNziyum)（访问码：`kf0f`）
* **网页端 Demo**：[https://demo.divesee.com:9080](https://demo.divesee.com:9080)
* **AI 服务端点**：
  * 滴水湖 ECS：`https://api.divesee.com:9443`
* **推荐测试站点**（蒙特卡洛模拟）：[https://wangzhefeng.com/post/2023/07/30/montecarlo/](https://wangzhefeng.com/post/2023/07/30/montecarlo/)

---

## 可以体验网页端及浏览器插件版

> 网页端与扩展版共享核心能力，适合不同场景：无安装快速试用 / 浏览器内沉浸式阅读。

---

## 浏览器插件 v0.5 安装教程（开发者模式）

1. 打开 Chrome，地址栏输入 `chrome://extensions`。
2. 右上角开启 **开发者模式**。
3. 点击 **“加载已解压的扩展程序”**，选择本插件文件夹。

> Firefox/Edge 的安装方式类似；若遇到“来自未知来源”提示，请确认安装包来自本仓库的 [Releases](../../releases)。

---

## 使用说明（要点）

* 页面 **左下角** 默认出现圆形 **“D”** 按钮，点击展开控制台。
* 拖动按钮到任一角落松开，会 **自动贴边**；面板展开方向也随之调整。
* 点击页面任意处或按 `Esc` 可 **收起面板**。
* **“无声阅读”** 关闭时，速度条可调但不滚动；开启后即时生效。
* **AI 模式**：页面首次刷新时会请求 `apiEndpoint` 的 `/api/analyze`；结果缓存于 **会话存储**。

---

## 视频介绍

* 双 Demo 演示视频：[https://cloud.189.cn/web/share?code=uUrqmmNziyum](https://cloud.189.cn/web/share?code=uUrqmmNziyum)（访问码：`kf0f`）

---

## 反馈与建议

请至本仓库的 [Issues](../../issues) 提交：

* **Bug 反馈**：复现步骤 / 实际结果 / 期望结果 / 浏览器与版本 / 插件版本 / 截图或录屏（如有）。
* **功能请求**：使用场景 / 解决的问题 / 期望交互。

> 建议附上 `chrome://version` 或 `about:support` 的环境信息，便于定位。

---

## 隐私与安全

* 本地算法：文本处理默认在本地执行；除非你主动上报问题，否则不会上传你的阅读内容。
* AI算法：数据将脱敏经过api服务器，我们不会主动储存文件
* 详细说明见 `PRIVACY.md`（占位）。

---

## 许可证

商业闭源（专有许可）。使用受最终用户许可协议（EULA）约束。
商务合作与授权请联系：`team@divesee.com`（占位）。

---

## 版本信息

* 当前：**v0.5**（本 README 所述）
* 历史版本与下载：见 [Releases](../../releases)

---

> —— Divesee Team Demo · v0.5
