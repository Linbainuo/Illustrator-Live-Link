# Illustrator-Live Link

Illustrator 2022–2026 与 Blender 4.0–5.2 的实时纹理链接插件（Windows）。

[下载最新版](https://github.com/Linbainuo/Illustrator-Live-Link/releases/latest)

1.1.0：修复 Blender 重开后的旧帧与图像保存提示，并在两端插件版本不一致时
提示需要更新的一端。Illustrator 应用内更新现在显示下载进度，并使用原生
Updater 完成重启安装，不再调用 PowerShell。

1.1.0 fixes stale frames and image-save prompts in Blender, and reports which
plug-in needs updating when the Illustrator and Blender versions differ.
Illustrator in-app updates now show download progress and use a native updater
for restart installation without invoking PowerShell.

## 中文安装

1. 下载并解压 `Illustrator-Live-Link-1.1.0-Windows.zip`。
2. 如果安装了多个 Illustrator，可先打开需要安装的版本。
3. 运行 Illustrator 文件夹内的安装脚本。安装器会检测已安装版本和现有插件，
   并自动选择正在运行的 Illustrator。
4. 保存并退出选中的 Illustrator；安装器完成更新后可直接重新打开它。
5. 在 Blender 的 `Preferences > Add-ons > Install from Disk` 中安装 Blender 文件夹内的 ZIP。

Illustrator 与 Blender 两端插件都需要安装。

如果 Illustrator 自动安装失败，把 Illustrator 安装包内整个
`Illustrator-Live Link` 文件夹复制到 Illustrator 的 `Plug-ins` 文件夹。
`.aip`、Renderer 与 Updater 必须保留在同一文件夹中。

## English Installation

1. Download and extract `Illustrator-Live-Link-1.1.0-Windows.zip`.
2. If multiple Illustrator versions are installed, open the version you want.
3. Run the installer inside the Illustrator folder. It detects installed hosts
   and the existing plug-in, then selects the running Illustrator automatically.
4. Save and quit the selected Illustrator. The installer finishes the update
   and can reopen that exact version.
5. In Blender, open `Preferences > Add-ons > Install from Disk` and select the ZIP inside the Blender folder.

Both the Illustrator and Blender plug-ins are required.

If automatic Illustrator installation fails, copy the complete
`Illustrator-Live Link` folder from the package into Illustrator's `Plug-ins`
folder. Keep the `.aip`, Renderer, and Updater together in that folder.

Tested with Illustrator 2022/2026 and Blender 4.0.2/4.5.8/5.2.0.
