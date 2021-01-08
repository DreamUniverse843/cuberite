# Cubarite - 开源的 C++  Minecraft 启动器

请注意：此Respositary仅为自用，非官方代理。
原项目:https://github.com/cuberite/cuberite
为便于贡献，以下为从原README.md的翻译。

Cuberite是Minecraft兼容的多人游戏客户端，用C ++编写，旨在通过内存和CPU高效运行，并具有灵活的Lua插件API。
Cuberite与Java原版Minecraft客户端兼容。
Cuberite可在Windows，* nix和Android操作系统上运行。 这包括Android手机、平板电脑以及Raspberry Pi。
目前，我们支持1.8-1.12.2 之间的Minecraft版本。

## 安装

有多种方式可为此项目进行配置。

### 贡献方式

- 可直接下载本Repo。
- 可下载Cuberite官方的下载脚本进行快速配置（可能不会与本Repo同步）

#### 安装脚本

下列官方脚本将提供正确的源文件：

    curl -sSfL https://download.cuberite.org | sh

### 编译

- 您可以使用项目内随附的 `compile.sh`脚本进行编译。 下方对它有详细描述。
- 您也可以手动编译。 详见项目内的 COMPILING.md 。

手动编译可能会提供更好的兼容效果与跨平台性能。

下述讯息对本Repo无帮助，弃用。
#### Compilling script

This script downloads the source code and compiles it. The script is smart enough to notify you of missing dependencies and instructing you on how to install them. The script doesn't work for Windows.

Using curl:

    sh -c "$(curl -sSfL -o - https://compile.cuberite.org)"

Or using wget:

    sh -c "$(wget -O - https://compile.cuberite.org)"

### Hosted services

- Hosted Cuberite is available via [Gamocosm][5].

## Contributing

Cuberite is licensed under the Apache License V2, and we welcome anybody to fork and submit a Pull Request back with their changes, and if you want to join as a permanent member we can add you to the team.

Cuberite is developed in C++ and Lua. To contribute code, please check out [GETTING-STARTED.md][6] and [CONTRIBUTING.md][7] for more details.

Plugins are written in Lua. You can contribute by developing plugins and submitting them to the [plugin repository][8] or the [forum][9]. Please check out our [plugin introduction guide][10] for more info.

If you are not a programmer, you can help by testing Cuberite and reporting bugs. See [TESTING.md][11] for details.

You can also help with documentation by contributing to the [User's Manual][12].

## Other Stuff

For other stuff, check out the [homepage][13], the [Users' Manual][14], the [forums][15], and the [Plugin API][16].

Support the Cuberite development team on [Liberapay][17]

[1]: https://cuberite.org/news/#subscribe
[2]: https://cuberite.org/
[4]: https://github.com/cuberite/cuberite/blob/master/COMPILING.md
[5]: https://gamocosm.com/
[6]: https://github.com/cuberite/cuberite/blob/master/GETTING-STARTED.md
[7]: https://github.com/cuberite/cuberite/blob/master/CONTRIBUTING.md
[8]: https://plugins.cuberite.org/
[9]: https://forum.cuberite.org/forum-2.html
[10]: https://api.cuberite.org/Writing-a-Cuberite-plugin.html
[11]: https://github.com/cuberite/cuberite/blob/master/TESTING.md
[12]: https://github.com/cuberite/users-manual
[13]: https://cuberite.org/
[14]: https://book.cuberite.org/
[15]: https://forum.cuberite.org/
[16]: https://api.cuberite.org/
[17]: https://liberapay.com/Cuberite
