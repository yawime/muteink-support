# MuteInk（默记）— 技术支持与支持文档

面向 **MuteInk / 默记** 用户的说明与反馈入口。App Store「技术支持网址」指向本仓库主页：<https://github.com/yawime/muteink-support>

---

## 中文

### 应用简介

默记是一款 **指尖书写** 工具：可在 **熄屏（近黑、低亮度）** 或 **亮屏** 下书写，适合先把脑中语句记下来、减少键盘与界面带来的干扰；支持 **回看逐笔回放**、**GIF 导出**、**复制为图** 等。系统要求：**iOS 17.0及以上**，**iPhone与 iPad**。

### 快速上手（手势）

| 操作 | 说明 |
|------|------|
| 单指书写 | 在屏幕上绘制笔画。 |
| 结束当前字 | 手指离开后，约 **0.3 秒** 内无新笔画，自动结束当前字。 |
| 双指单击 | 删除 **前一个字**。 |
| 三指单击 | **换行**，并结束当前一句（**会保存进度**）。 |
| 书写方向 | 进入前可选 **竖屏**（适合中文、日文等）或 **横屏**（适合英文等）；可随时切换，**切换后开始新的书写**。 |

**熄屏模式**：屏幕会非常暗并尽量保持常亮以便连续书写，请关注电量；**电量过低**时应用会退出该模式并通过触觉等方式提示。

**触觉反馈**：在支持的 **iPhone** 上，结束单字、结束一句、保存成功时会有不同触觉反馈；**iPad** 可能无震动，视设备而定。

### 隐私与数据

- 笔记内容保存在 **本机**，**无需账号**；应用 **不会** 将你的笔迹或笔记同步到开发者服务器。  
- 具体权限（如相册，用于保存 GIF）以系统设置与 App 内说明为准。

### 常见问题（FAQ）

**Q：写完的内容在哪里看？**  
A：打开 App 底部 **「回看」**，选择条目即可 **逐笔回放**；可删除或调整列表顺序。

**Q：导出的 GIF 在部分 App 里不动或只显示第一帧？**  
A：部分第三方客户端对 GIF/透明通道支持有限，属于对方 App 的限制；可尝试换用支持动图的分享方式或先保存到系统相册再分享。

**Q：iPad 上没有震动？**  
A：部分 iPad 无 Taptic Engine，**可能没有触觉反馈**，不影响书写与保存。

### 反馈与支持

- **问题与建议**：[GitHub Issues](https://github.com/yawime/muteink-support/issues)（推荐：便于追踪与回复）。  
- 若你希望在页面公开 **联系邮箱**，可将邮箱写在本段下方并提交到本仓库，或直接在 Issues 中说明你的联系方式策略。

---

## English

### About

**MuteInk** is a **finger-writing** app for iPhone and iPad (**iOS 17.0+**). Write in **dim (near-black) “blind” mode** or **bright mode**, replay strokes in **Review**, and export/share **GIFs** or **copy as image**.

### Quick reference (gestures)

| Action | What it does |
|--------|----------------|
| One finger | Draw strokes. |
| End current character | After you lift your finger, if no new stroke for about **0.3 s**, the character is finalized. |
| Two-finger tap | Delete the **previous** character. |
| Three-finger tap | **New line** and end the current **sentence** (**progress is saved**). |
| Orientation | Choose **portrait** (e.g. Chinese/Japanese) or **landscape** (e.g. English) before you start; you can switch anytime and **start a new session** after switching. |

**Dim mode** keeps the display very dark and awake for continuous capture—monitor battery. At **very low battery**, the app exits dim mode and uses **haptics** where available.

**Haptics** work on supported **iPhones**; many **iPads** do not vibrate.

### Privacy & data

- Notes stay **on your device**. **No account** is required, and handwriting is **not** synced to our servers.  
- Photo library access (if any) is used for features like saving GIFs, as explained in the app and system settings.

### FAQ

**Where are my notes?**  
Open the **Review** tab, pick an entry, and use **stroke replay**. You can delete or reorder items.

**GIF doesn’t animate in some apps?**  
Some third-party clients handle GIFs or transparency poorly; try another share path or save to Photos first.

**No haptics on iPad?**  
Many iPads have no Taptic Engine—this is expected.

### Support

- **Bugs & suggestions**: [GitHub Issues](https://github.com/yawime/muteink-support/issues).  
- Add a public **support email** in this README if you like, via a commit to this repo.
