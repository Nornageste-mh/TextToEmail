# 附加条款与免责声明 / Additional Terms and Disclaimer

> **适用关系**：本文件是对仓库根目录 [`LICENSE`](LICENSE)（MIT 许可）的补充说明
> 与明确化，**不缩减** MIT 许可已授予的任何权利。若两者冲突，以 MIT 许可为准。
> 本文件由开源项目通用模板改写，**不构成法律意见**。

================================================================================
附加条款 / ADDITIONAL TERMS
================================================================================

1. 署名 / Attribution
---------------------

凡复制、修改、分发本软件，或以本软件为基础创作衍生作品，均须以显著方式标注：

  (a) 原始出处：https://github.com/Nornageste-mh/TextToEmail.git，以及作者 Nornageste-mh；
  (b) 若发生修改，须注明「已修改」及修改要点，不得让他人误以为修改版
      出自原作者或获得原作者背书。

标注位置可为 README、项目文档、关于界面、发行说明或源码头部之一，
且须随分发物一同提供。

Any copy, modification, distribution, or derivative work must prominently
credit the origin: this repository's URL and the author Nornageste-mh. If you
changed anything, state that it was modified. Do not imply that a modified
version was produced or endorsed by the original author.

2. 非官方声明 / Unofficial Project
----------------------------------

本软件是非官方的第三方无障碍辅助工具，与任何电信运营商、邮件服务商、
设备厂商、应用分发平台及其关联公司不存在任何隶属、合作、赞助、授权或
背书关系。相关商标与名称的全部权利归各自权利人所有。

This is an unofficial, third-party accessibility tool. It is not affiliated
with, authorized by, sponsored by, or endorsed by any carrier, email
provider, device manufacturer, or app distribution platform. All trademarks
remain the property of their respective owners.

3. 免责与责任限制 / Disclaimer and Limitation of Liability
----------------------------------------------------------

本软件按「现状」提供，不附带任何形式的明示或默示担保。在适用法律允许的
最大范围内，作者与贡献者对因使用或无法使用本软件而产生的任何直接、间接、
附带、特殊、惩罚性或后果性损害均不承担责任。这包括但不限于：

  (a) 短讯转发失败、延迟、漏转或误转，应用无法启动、崩溃或数据异常；
  (b) 邮箱账号或设备被限制、停用，或电信运营商、邮件服务商的服务条款、
      最终用户许可协议被认定违反；
  (c) 短讯内容经第三方邮件服务传输或存储而引发的隐私泄露、越权访问或
      其他后果（本软件不控制该服务的安全性）；
  (d) 与电信运营商、邮件服务商、平台运营方或任何第三方之间产生的争议、
      索赔、诉讼、禁令或任何形式的损失；
  (e) 设备损坏、系统故障、数据丢失或其他财产损失；
  (f) 第三方组件自身的许可瑕疵、权利主张或由此引发的任何责任。

是否使用本软件由你自行决定并自行承担全部风险。你应自行确认在当地法律及
相关服务条款下使用本软件是否合规。

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. TO THE
MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE AUTHORS AND CONTRIBUTORS
SHALL NOT BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY,
OR CONSEQUENTIAL DAMAGES ARISING FROM THE USE OF OR INABILITY TO USE THE
SOFTWARE. THIS INCLUDES, WITHOUT LIMITATION: FAILED, DELAYED, MISSED, OR
MISDIRECTED MESSAGE FORWARDING; APPLICATION OR DEVICE FAILURE; EMAIL ACCOUNT
RESTRICTION OR SUSPENSION; DISCLOSURE OR UNAUTHORIZED ACCESS ARISING FROM
TRANSMISSION OF MESSAGE CONTENT THROUGH A THIRD-PARTY EMAIL SERVICE; ANY
DISPUTE, CLAIM, OR ACTION BY A CARRIER, EMAIL PROVIDER, PLATFORM, OR OTHER
THIRD PARTY; AND ANY DEFECT IN THIRD-PARTY COMPONENTS. YOU USE THIS SOFTWARE
AT YOUR OWN RISK.

4. 第三方组件 / Third-Party Components
--------------------------------------

本软件可能包含或依赖第三方代码。该部分不受本许可授权，其版权与许可归
各自权利人所有，并适用其各自的许可条款。分发时须保留其原始版权声明与
许可文本。

This software may include or depend on third-party code, which is licensed
under its own terms and is not covered by this license. Their copyright
notices and license texts must be preserved.

5. 本仓库第三方组件明细 / Third-Party Components in This Repository
-------------------------------------------------------------------

下表为本仓库实际涉及或依赖的第三方组件，**不受本 MIT 许可授权**，适用其各自许可：

| 组件 | 许可 | 权利人 | 说明 |
|---|---|---|---|
| Jakarta Mail（`com.sun.mail:jakarta.mail:2.0.1`） | EPL-2.0 或 GPL-2.0+CPE（双许可） | Eclipse Foundation | 以依赖形式引入，源码不随仓库分发 |
| AndroidX / Material Components | Apache-2.0 | Google | 同上 |
| Kotlin 标准库 / kotlinx.coroutines | Apache-2.0 | JetBrains | 同上 |
| Gson（`com.google.code.gson:gson:2.10.1`） | Apache-2.0 | Google | 同上 |
| Shizuku（`dev.rikka.shizuku:api`、`:provider:13.1.5`） | Apache-2.0 | RikkaApps | 同上 |
| flexmark-java（`com.vladsch.flexmark:flexmark*:0.64.8`） | **BSD-2-Clause** | Atlassian Pty Ltd / Vladimir Schneider | 同上，BSD-2-Clause 要求随二进制保留版权声明 |
| JUnit 4 / `androidx.test.ext:junit` | EPL-1.0 / Apache-2.0 | JUnit 团队 / Google | **仅测试依赖，不随应用分发** |

分发本软件时，须保留上述组件的原始版权声明与许可文本。若你重新分发本项目的
构建产物，请自行确认已满足全部第三方许可的署名、附随与源码提供要求。

The components above are licensed under their own terms and are **not** covered
by this MIT license. Preserve their copyright notices and license texts when
redistributing.
