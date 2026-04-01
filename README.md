# CmdPal-list
PowerToys command-palette插件整理收集

---

# [EverythingCommandPalette](https://github.com/lin-ycv/EverythingCommandPalette)      
EverythingCommandPalette（ECP）是 PowerToys Command Palette（CmdPal）程序的一个扩展。 
ECP 增加了使用 CmdPal 内的 Everything 在计算机中搜索文件和文件夹的功能

# [CmdPal-WebSearchShortcut](https://github.com/Daydreamer-riri/CmdPal-WebSearchShortcut)      
这是一个简单的 PowerToys CmdPal 插件，可快速选择特定搜索引擎通过关键词前缀进行搜索。

# [CmdPalExtensions](https://github.com/zadjii/CmdPalExtensions)      
<table><thead>
  <tr>
    <th>Extension</th>
    <th>x64 Link</th>
    <th>Description</th>
  </tr></thead>
<tbody>
  <tr>
    <td>TMDB Search</td>
    <td>

[v0.0.4](https://github.com/zadjii/CmdPalExtensions/releases/download/tmdb%2Fv0.0.4/TmdbExtension_0.0.4.0_x64.msix)
    </td>
    <td>Search for movies, and find out what streaming services they're available on.</td>
  </tr>
  <tr>
    <td>Obsidian</td>
    <td>

[v0.0.5](https://github.com/zadjii/CmdPalExtensions/releases/download/obsidian%2Fv0.0.5/ObsidianExtension_0.0.5.0_x64.msix)
    </td>
    <td>Search your notes in Obsidian. View them in the palette & make quick edits</td>
  </tr>
  <tr>
    <td>Mastodon</td>
    <td>

[v0.0.4](https://github.com/zadjii/CmdPalExtensions/releases/download/mastodon%2Fv0.0.4/MastodonExtension_0.0.4.0_x64.msix)
    </td>
    <td>View posts on mastodon.social. You should be able to sign in and view your home timeline & favorite posts too. I haven't tested other servers yet (_I know, I'm a bad fediverse citizen_)
</td>
  </tr>
  <tr>
    <td>Segoe Icons</td>
    <td>

[v0.0.3](https://github.com/zadjii/CmdPalExtensions/releases/download/icons%2Fv0.0.3/SegoeIconsExtension_0.0.3.0_x64.msix)
    </td>
    <td>Search the big list of Segoe Fluent icons.</td>
  </tr>
  <tr>
    <td>Hacker News</td>
    <td>

[v0.0.5](https://github.com/zadjii/CmdPalExtensions/releases/download/hackernews%2Fv0.0.5/HackerNewsExtension_0.0.5.0_x64.msix)
    </td>
    <td>View top posts on Hacker News</td>
  </tr>
  <tr>
    <td>Media Controls (BROKEN)</td>
    <td>

[v0.0.1](https://github.com/zadjii/CmdPalExtensions/releases/download/v0.0.1/MediaControlsExtension_0.0.1.0_x64.msix)
    </td>
    <td>Control playing media. This one is buggy, and hasn't been updated since early CmdPal builds. It needs love</td>
  </tr>
</tbody>
</table>

# [VisualStudioCodeForCommandPalette](https://github.com/tanchekwei/VisualStudioCodeForCommandPalette)      
该项目提供了一个命令调色板扩展，用于从单一统一界面打开 Visual Studio 解决方案和 Visual Studio Code 工作区。

# [CmdPal-VideoDownloader](https://github.com/DevLGuilherme/CmdPal-VideoDownloader)      
使用 yt-dlp 直接从 PowerToys 指令调色板下载和剪辑视频、音频、播放列表、字幕和字幕。

# [CmdPal.Ext.Spotify](https://github.com/waaverecords/CmdPal.Ext.Spotify)      
这是PowerToys Command Palette的一个扩展，允许你搜索Spotify并控制其播放器。

# [MediaControlsExtension](https://github.com/jiripolasek/MediaControlsExtension)      
完全掌控你的媒体播放，而无需离开工作流程。PowerToys Command Palette 的媒体控制让你在最爱的应用中无缝管理音频和视频——所有这些都在同一方便的地方。可以即时播放、暂停、跳过曲目或回溯，并且可以轻松切换开启的媒体播放器，这样你就能掌控播放内容。

# [ColorsExtension](https://github.com/jiripolasek/ColorsExtension)      
该扩展支持命令调色板内的即时色彩可视化、转换和操作。轻松预览、变换和处理颜色——无需离开工作流程。

# [RecentFilesExtension](https://github.com/jiripolasek/RecentFilesExtension)      
该扩展可快速访问 Microsoft PowerToys 命令调色板中最近打开的文件。

# [CmdPal-ProcessKiller](https://github.com/8LWXpg/CmdPal-ProcessKiller)      
用于终止进程的命令调色板扩展
> [!IMPORTANT]
> 该项目仍处于早期开发阶段

# [QRCodesExtension](https://github.com/jiripolasek/QRCodesExtension)      
你可以直接从PowerToys Command Palette创建和管理二维码——无需再打开其他应用或网站。

# [SteamCmdPalExtension](https://github.com/sht2017/SteamCmdPalExtension)      
一目了然地查看、启动和管理Steam游戏
> [!NOTE]  
> 一旦启动这个扩展，Steam就会被终止——这意味着你最好不要在游戏运行时启动或重新加载命令调色板。

> [!WARNING]  
> SteamPal 用于命令调色板，使用 Chrome DevTools 协议，通过 TCP 与 Steam CEF 交互并获取必要数据。请注意，该扩展可能与其他使用相同技术的程序发生冲突。如果存在冲突，你可以考虑手动设置调试端口。此外，由于Steam服务在Windows上的权限等级很高，如果无法保证系统可信，在本地通过TCP使用CEF调试可能会对你的账户造成黑客攻击的风险（我尝试过通过管道实现调试，但似乎Steamwebhelper就是不接受。这可能会进一步实现）。

> [!CAUTION]
> 由于上游的 bug（microsoft/PowerToys#39837），使用该扩展时你可能会发现内存泄漏。我现在无能为力。

# [CmdPalExtensions](https://github.com/michaeljolley/CmdPalExtensions)      
该仓库包含了Windows命令调色板的各种扩展，包括 随 Microsoft PowerToys 一起提供。

# [ChangeCaseExtension](https://github.com/jiripolasek/ChangeCaseExtension)      
直接在 Microsoft PowerToys 的命令面板中转换文本大小写。
> 小写、大写、驼峰命名、蛇形命名、帕斯卡命名等格式转换

# [DevNumbersExtension](https://github.com/jiripolasek/DevNumbersExtension)      
该扩展允许你使用 PowerToys Command Palette 显示和计算各种数值。

# [JPSoftworks.CommandPalette.Extensions.Toolkit](https://github.com/jiripolasek/JPSoftworks.CommandPalette.Extensions.Toolkit)      
一套用于构建命令调色板扩展的扩展和实用工具，扩展了 Microsoft.CommandPalette.Extensions NuGet 包，并赋予了独立自主的功能集。
> [!WARNING]  
> 实施方式未来可能会有所调整。随着Command Palette的演进，这个工具包也会随之发展。请自行承担风险。

# [ToggleDarkModeExtension](https://github.com/jiripolasek/ToggleDarkModeExtension)      
快速从Command调色板切换暗黑模式。

# [NotionForCmdPal](https://github.com/michaeljolley/NotionForCmdPal)      
一个Windows命令面板扩展，允许用户管理他们的Notion页面和数据库。

# [CmdPalExtensions](https://github.com/chatasweetie/CmdPalExtensions)      
一系列适用于Windows的Command Palette扩展，提升你的工作效率，并通过Windows命令面板界面提供娱乐。

# [CmdPal-SSH](https://github.com/8LWXpg/CmdPal-SSH)      
命令托盘扩展，用于连接在文件中配置的SSH客户端。
> [!IMPORTANT]
> 该项目仍处于早期开发阶段

# [CmdPal-WebSearchShortcut](https://github.com/jiripolasek/PowerToys-Run-WebSearchShortcut)      
可快速选择特定搜索引擎通过关键词前缀进行搜索。

# [CmdPal-InputTyper](https://github.com/jiripolasek/CmdPal-InputTyper)      
用于输入输入，仿佛直接从键盘发送。非常适合无法粘贴的场景。
