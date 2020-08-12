## 这是什么 | What's this

小米 Air 13.3 2018（CPU i5-8250U） BIOS

BIOS for XiaoMi Air 13.3 2018 (CPU i5-8250U)

有两个版本：

Two versions available:

- `XMAKB3M0P100B.exe` 为 2018 年 3 月份版本（March 2018 version）

- `XMAKB3M0P120C.exe` 为 2018 年 7 月份版本（July 2018 version）

## 怎么使用 | How to use

- 升级 | Upgrade

    - 默认升级，双击安装即可

    - upgrade by default, double click to install

- 降级 | Downgrade

    - 解压文件，用文本编辑器修改 `platform.ini`

    - extract, edit `platform.ini` with text editor (VSCode, for example)

    - 搜索 `[Bios_Version_Check]`，修改第二个结果下的 `Flag` 为 `0`，即 `Flag=0`，保存

    - search for `[Bios_Version_Check]`, change the value of `Flag` from `1` to `0`, save

    - 双击安装即可

    - double click to install
