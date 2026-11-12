# Illustrator Live Link + Surface Pen

Illustrator 2022–2026 与 Blender 4.0–5.2 的纹理联动、UV 传输和贴面钢笔插件，适用于 Windows 10/11 x64。

[下载最新版](https://github.com/Linbainuo/Illustrator-Live-Link/releases/latest)

## 1.2.3 热修

- 修复重启、多文档关闭后的连接等待和旧材质缓存。
- 自动创建并连接缺少的材质、图像纹理和输出节点。
- 支持联动中切换 1024/2048/4096，以及长方形画板。
- 修复带填充剪切蒙版漏色、钢笔节点和手柄回折。
- “显示画板”在 Illustrator 2026 跟随背景色和透明状态；旧版 AI 使用白色/透明背景。

## 安装与更新

1. 下载并解压 `Illustrator-Live-Link-1.2.3-Windows.zip`。
2. 保存 AI 画稿，运行 Illustrator 文件夹中的“安装 Illustrator-Live Link.exe”。
3. 安装器自动选择对应宿主 AIP，并等待 Illustrator 正常退出后替换文件。
4. Blender 使用“从磁盘安装”选择 `Illustrator-Live-Link-Blender-1.2.3.zip` 并启用。
5. 选中带 UV 的模型，在 Live Link 面板选择文档并开启联动。钢笔已合并，无需另装旧版独立钢笔。

两端插件应同时更新到同一版本。插件不会替你保存或覆盖 AI 画稿。

手动安装时，从对应年份目录取出一份 `Illustrator-Live Link.aip`，与核心目录中的 Renderer、Updater 和 Licenses 一起放入目标 Illustrator 的专用插件目录：

| Illustrator | AIP 来源目录 |
| --- | --- |
| 2022–2024 | Illustrator 2022-2024 |
| 2025 | Illustrator 2025 |
| 2026 | Illustrator 2026 |

## 验证范围

Blender 4.0.2、4.5.8 LTS、5.2.0 共 39 项功能回归通过；三个版本的 ZIP 启动、文件加载及原生更新器的三种 AIP 分流均已验证。5.2 另完成实际侧栏绘制测试。

Illustrator 2022/2026 已有开发版功能实机记录。2023、2024、2025 为对应 SDK 构建适配，尚未完成独立宿主实机测试。复杂外观使用 Adobe 兼容渲染，刷新速度取决于文档复杂度。

## English

Version 1.2.3 fixes reconnection, automatic material binding, live resolution changes, rectangular artboards, painted clipping masks, and Surface Pen editing stability.

Install both plug-ins at the same version. Extract the Windows bundle, save your artwork, and run the native Illustrator installer. Then install the Blender ZIP from disk. The installer selects the 2022–2024, 2025, or 2026 AIP for the target host.

Blender 4.0.2, 4.5.8 LTS, and 5.2.0 passed 39 functional regression checks. Illustrator 2022/2026 have development-build runtime verification; 2023–2025 have SDK build compatibility but no individual host runtime verification. Artboard color following requires Illustrator 2026; older hosts support white/transparent backgrounds.

