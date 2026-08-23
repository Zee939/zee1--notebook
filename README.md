# 便签软件 (Sticky Note) | Desktop Sticky Note App

一个轻量级的桌面便签软件，支持全局快捷键唤起、系统托盘、多主题稿纸。

A lightweight desktop sticky note app with global hotkey activation, system tray support, and multiple themed paper styles.

---

## 功能特性 | Features

- 📝 **便利贴大小 | Compact Size**：小巧窗口，不占屏幕空间。Small window that doesn't take up screen space.
- 🖱️ **自由拖动 | Free Dragging**：按住标题栏即可拖动到任意位置。Drag the title bar to move the note anywhere on screen.
- ⌨️ **全局快捷键 | Global Hotkey**：`Ctrl+Alt+N` 一键唤起/隐藏便签。Press `Ctrl+Alt+N` to show or hide the note instantly.
- 💾 **自动保存 | Auto-Save**：每 3 秒自动保存内容，重启不丢失。Automatically saves content every 3 seconds; no data loss after restart.
- 📥 **系统托盘 | System Tray**：关闭时可选择缩小到任务栏托盘。Minimize to system tray when closing.
- 🎨 **多主题稿纸 | Multiple Themes**：黄色、粉色、蓝色、绿色、紫色、橙色、青色、白色共 8 种稿纸主题。8 paper themes: Yellow, Pink, Blue, Green, Purple, Orange, Cyan, and White.
- 👋 **首次欢迎页 | Welcome Page**：第一次打开显示圆角欢迎页面。Rounded welcome page shown on first launch.
- ⚙️ **设置面板 | Settings Panel**：可更换主题、调整字体大小、设置窗口置顶。Change themes, adjust font size, and toggle always-on-top.

---

## 使用说明 | User Guide

| 操作 / Operation | 说明 / Description |
|------|------|
| 拖动 / Drag | 按住顶部标题栏拖动 / Hold the title bar to drag |
| 唤起/隐藏 / Show/Hide | 按 `Ctrl+Alt+N` / Press `Ctrl+Alt+N` |
| 缩小到托盘 / Minimize to Tray | 点击最小化按钮 / Click the minimize button |
| 完全退出 / Fully Exit | 点击关闭按钮后选择"完全退出程序" / Click close and select "Fully Exit Program" |
| 更换主题 / Change Theme | 点击标题栏 ⚙ 按钮，在设置中选择主题 / Click the ⚙ button on the title bar and select a theme |
| 调整字体 / Adjust Font | 点击 ⚙ 按钮，拖动字体大小滑块 / Click the ⚙ button and drag the font size slider |

---

## 文件结构 | File Structure

```
notebook/
├── 便签.exe           # 主程序（所有功能代码）/ Main executable (all-in-one)
├── _internal          # 运行依赖 / Runtime dependencies
└── README.md          # 说明文档 / Documentation
```

---

## 配置文件 | Configuration File

运行后会在程序同目录生成 `sticky_note_config.json`，保存便签内容、主题、窗口位置等设置。

After running, a `sticky_note_config.json` file will be created in the same directory to save note content, theme, window position, and other settings.

---

## 系统要求 | System Requirements

- Windows 10/11
