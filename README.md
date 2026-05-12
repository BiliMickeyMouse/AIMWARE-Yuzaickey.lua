# AIMWARE-Yuzaickey.lua
A lua for AIMWARE v6

# Yuzaickey Recode

**yuzaickey.lua** - 基于 [yuzaki.lua](#致谢) 编写的 CS2 游戏辅助脚本，免费且开源，支持二改并免费发布。

## License

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at https://mozilla.org/MPL/2.0/.

```
Mozilla Public License Version 2.0
==================================

1. Definitions
--------------

1.1. "Contributor"
    means each individual or legal entity that creates, contributes to
    the creation of, or owns Covered Software.

1.2. "Contributor Version"
    means the combination of the Contributions of others (if any) used
    by a Contributor and that particular Contributor's Contribution.

1.3. "Contribution"
    means any work of authorship, including the original version of the
    Covered Software and any modifications or additions to that Software
    or Documentation in which the Copyright owner intentionally submits
    for inclusion in the Covered Software, and which is intended to be
    included in the Covered Software.

1.4. "Covered Software"
    means Source Code Form made available under this License.

1.5. "Larger Work"
    means a work that combines Covered Software with other material,
    in a separate file or files, that is not Covered Software.

1.6. "License"
    means this document.

1.7. "Modifications"
    means any of the following:
    (a) any file in Source Code Form that results from adding to,
        deleting from, or modifying the contents of Covered Software; or
    (b) any new file in Source Code Form containing any portion of
        Covered Software, or any Larger Work derived therefrom.

1.8. "Patent Claims" of a Contributor
    means any patent claim(s), including without limitation, method,
    process, and apparatus claims, now owned by or hereafter acquired
    by such Contributor, that would necessarily be infringed if some
    aspect of the Contributor's Contribution were made, used, sold,
        offered for sale, imported, or otherwise disposed of, either
        alone or in combination with the Contributor's Version.

1.9. "Source Code Form"
    means the preferred form for making modifications, including but
    not limited to software source code, documentation source, and
    configuration files.

1.10. "You" (or "Your")
    means an individual or a legal entity exercising rights under this
    License.

2. Grant of Rights License
--------------------------

2.1. The initial Developer grants You a worldwide, royalty-free,
    non-exclusive license:
    (a) under intellectual property rights (other than patent or
        trademark) to use, reproduce, modify, display, perform,
        sublicense, and distribute the Covered Software in Source
        Code or Object Code form; and
    (b) under Patent Claims of that Contributor to make, use, sell,
        offer for sale, have made, import, and otherwise transfer
        either its Contributions or its Contributor Version.

2.2. Additional Grant of Patent Rights
    Subject to the terms and conditions of this License, each Contributor
    hereby grants to You a perpetual, worldwide, non-exclusive, no-
    charge, royalty-free, irrevocable (except as stated herein)
    patent license to make, have made, use, offer to sell, sell,
    import, and otherwise transfer its Contributions where such
    license applies only to those patent claims licensable by such
    Contributor that are necessarily infringed by their
    Contribution(s) alone or by combination of their
    Contribution(s) with the Contributor Version to which such
    Contribution(s) was submitted.

3. Distribution Obligations
---------------------------

3.1. Availability of Source Code
    You may distribute Covered Software in Object Code form only if:
    (a) you make the Source Code available under the terms of this
        License; and
    (b) you include prominent notice stating location of Source Code.

3.2. Modifications
    If You create Modifications, You must:
    (a) cause modified files to carry prominent notices stating
        that You changed the files;
    (b) license the Modified Files under MPL-2.0; and
    (c) retain all copyright, patent, trademark, and attribution
        notices from the Source Code form.

3.3. Distribution of Executable Forms
    When distributing Covered Software in Executable form, You must
    make the Source Code available under MPL-2.0.

4. Inability to Comply Due to Statutory or Regulatory Condition
-------------------------------------------------------------

If it is impossible for You to comply with any of the terms due to
statute or judicial regulation, then: (a) You must comply to the
maximum extent possible before distributing; and (b) describe the
limitations and the code they affect.

5. Termination
--------------

5.1. This License and the rights granted hereunder will terminate
    automatically if You fail to comply with terms herein and fail to
    cure such breach within 30 days of becoming aware.

5.2. If Your rights have been terminated and not reinstated, then:
    (a) rights granted by this License terminate; but
    (b) licenses from Contributors where You received the software
        remain valid.

5.3. Rights may be reinstated upon agreement with the copyright holder.

6. Disclaimer of Warranty
-------------------------

UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING, THE
COPYRIGHT HOLDERS PROVIDE THE COVERED SOFTWARE "AS IS" WITHOUT
WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT
LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE
OF THE COVERED SOFTWARE IS WITH YOU.

7. Limitation of Liability
--------------------------

UNDER NO CIRCUMSTANCES SHALL ANY COPYRIGHT HOLDER BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES ARISING FROM USE OF THE COVERED SOFTWARE, EVEN IF ADVISED OF
THE POSSIBILITY OF SUCH DAMAGE.

8. Miscellaneous
---------------

This License represents the complete agreement concerning the subject
matter hereof.
```

## 功能特性

### Aimbot（自瞄）
- FOV 范围调节与可视化绘制
- 平滑度控制
- 目标选择：敌人 / 队友 / 全部
- 击中部位选择：头/颈/胸/腹/四肢
- 瞄准指示器显示（支持上/下/左/右位置）

### Spammer（刷屏器）
- 多种分类文本池：Insult 系列、各作弊网站名称、自定义文本
- 可调发送间隔

### Helper（游戏助手）
- **RageBot / LegitBot** 切换
- **AutoWall** 自动穿墙开关
- **ThroughSmoke** 烟雾穿透开关
- **DoubleTap (DT)** 双击开关
- **指示器系统**：
  - 每个功能项独立的 On/Off 颜色选择器（默认开=绿，关=红）
  - 横向 / 竖向布局切换
  - 竖向模式下支持居中/左对齐/右对齐
  - X/Y 偏移量自由调节

### SpinBot（旋转）
- 多种旋转模式：下视 / 水平 / 上视 / 抖动
- 旋转速度可调
- 内置指示器显示（旋转状态/速度/模式）
- 指示器颜色独立可配

### Watermark（水印）
- 多主题样式：
  - **Skeet1** — 简洁风格
  - **Skeet2** — HSV 彩虹流动边框 + 透明外框
  - **Neverlose Light** — 浅色主题
  - **Neverlose Dark** — 深色主题
- 自定义信息模块：Logo / 用户名 / FPS / 运行时间 / IP / 移动速度
- 主题色全局可控

### Hitlog（击中日志）
- Dark / Light 双主题
- 实时显示击中和击杀信息
- 包含目标名、部位、伤害值、剩余血量
- Y 轴偏移可调

### TriggerBot Delay（触发延迟）
- 根据准心到最近敌人距离自动调节延迟
- 配合连点倍率使用

## 使用说明

1. 将 `yuzaickey.lua` 文件放入脚本加载目录
2. 在游戏中通过菜单加载脚本
3. 在 `Yuzaickey Recode` 窗口中配置各项功能

## 致谢

- 基于 **yuzaki.lua**（作者: Yuzaki Xiaosi1337 Xingdao）编写优化
- Skeet 水印样式参考自 QQ 3167516283 的仿 SK 水印实现
- 所有引用的第三方代码均在源码注释中标明出处

## 作者

**M1ckey_**

> yuzaickey.lua 免费且开源，支持二改并免费发布。修改过的版本请注明原作者，尊重他人(AI)的劳动成果。
