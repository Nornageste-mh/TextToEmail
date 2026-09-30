# TextToEmail — SMS to Email Forwarder

*[简体中文](#简体中文) | [繁體中文](#繁體中文) | [English](#english) | [日本語](#日本語) | [Norsk](#norsk) | [文言](#文言)*

---

## English

TextToEmail is an Android app that automatically forwards incoming SMS messages to your email via SMTP.

**Core Features**
- Monitor incoming SMS and forward to one or more email addresses
- SMTP configuration with STARTTLS / SSL-TLS encryption
- Blacklist / whitelist filtering by sender number
- Forward log with export
- App lock PIN
- Shizuku integration for one-click permission grant
- Legal documents (User Agreement, Privacy Policy, Disclaimer) in 6 languages
- Auto-start setup guide for major manufacturers (Xiaomi, Huawei, OPPO, vivo, Samsung)

**Requirements**
- Android 7.0 (API 24) or later
- SMTP email account (Gmail, QQ, 163, etc.)

**Permissions**
- `RECEIVE_SMS` — detect incoming SMS
- `READ_SMS` — optional, read existing SMS
- `POST_NOTIFICATIONS` — foreground service notification
- `RECEIVE_BOOT_COMPLETED` — auto-restart after reboot
- `INTERNET` — SMTP connection
- `WAKE_LOCK` — keep CPU awake for forwarding

**Build**
```bash
git clone https://github.com/Nornageste-mh/TextToEmail.git
cd TextToEmail
./gradlew assembleRelease
```

**License**
This project is open-source. See [LICENSE](LICENSE) for details.

---

## 简体中文

TextToEmail 是一款 Android 应用，可将收到的短信通过 SMTP 自动转发至邮箱。

**核心功能**
- 监听新短信并转发至一个或多个邮箱
- 支持 STARTTLS / SSL-TLS 加密的 SMTP 配置
- 按号码黑名单/白名单过滤
- 转发日志（可导出）
- 应用锁 PIN 码
- Shizuku 一键授权集成
- 六语言法律文档（用户协议、隐私政策、免责声明）
- 主流厂商自启动引导（小米、华为、OPPO、vivo、三星）

**要求**
- Android 7.0 (API 24) 及以上
- SMTP 邮箱账号（Gmail、QQ邮箱、163邮箱等）

**权限**
- `RECEIVE_SMS` — 检测新短信
- `READ_SMS` — 可选，读取已有短信
- `POST_NOTIFICATIONS` — 前台服务通知
- `RECEIVE_BOOT_COMPLETED` — 重启后自动恢复
- `INTERNET` — SMTP 连接
- `WAKE_LOCK` — 保持 CPU 唤醒以转发

**构建**
```bash
git clone https://github.com/Nornageste-mh/TextToEmail.git
cd TextToEmail
./gradlew assembleRelease
```

**许可**
本项目为开源项目。详见 [LICENSE](LICENSE)。

---

## 繁體中文

TextToEmail 是一款 Android 應用，可將收到的簡訊通過 SMTP 自動轉發至郵箱。

**核心功能**
- 監聽新簡訊並轉發至一個或多個郵箱
- 支援 STARTTLS / SSL-TLS 加密的 SMTP 配置
- 按號碼黑名單/白名單過濾
- 轉發日誌（可匯出）
- 應用鎖 PIN 碼
- Shizuku 一鍵授權集成
- 六語言法律文檔（使用者協議、隱私政策、免責聲明）
- 主流廠商自啟動引導（小米、華為、OPPO、vivo、三星）

**要求**
- Android 7.0 (API 24) 及以上
- SMTP 郵箱帳號（Gmail、QQ郵箱、163郵箱等）

**構建**
```bash
git clone https://github.com/Nornageste-mh/TextToEmail.git
cd TextToEmail
./gradlew assembleRelease
```

---

## 日本語

TextToEmail は、受信した SMS を SMTP 経由で自動的にメールに転送する Android アプリです。

**主な機能**
- 新着 SMS を監視し、1 つ以上のメールアドレスに転送
- STARTTLS / SSL-TLS 暗号化対応の SMTP 設定
- 送信者番号によるブラックリスト / ホワイトリストフィルター
- 転送ログ（エクスポート可能）
- アプリロック PIN
- Shizuku によるワンクリック権限付与
- 6 言語の法的文書（利用規約、プライバシーポリシー、免責事項）
- 主要メーカー向け自動起動設定ガイド

**要件**
- Android 7.0 (API 24) 以上
- SMTP メールアカウント

**ビルド**
```bash
git clone https://github.com/Nornageste-mh/TextToEmail.git
cd TextToEmail
./gradlew assembleRelease
```

---

## Norsk

TextToEmail er en Android-app som automatisk videresender innkommende SMS-meldinger til e-post via SMTP.

**Hovedfunksjoner**
- Overvåk nye SMS og videresend til én eller flere e-postadresser
- SMTP-konfigurasjon med STARTTLS / SSL-TLS-kryptering
- Svarteliste / hviteliste-filtrering etter avsendernummer
- Videresendingslogg med eksport
- App-lås PIN
- Shizuku-integrasjon for ett-klikks tillatelsesgiving
- Juridiske dokumenter på 6 språk
- Auto-start guide for store produsenter

**Krav**
- Android 7.0 (API 24) eller nyere
- SMTP e-postkonto

---

## 文言

TextToEmail 者，Android 之器也，可自转发所收之短讯至信函，借 SMTP 而行之。

**枢要之功**
- 监听新讯，转发至一或多信函
- SMTP 之设，支持 STARTTLS / SSL-TLS 之密
- 依号记之善恶录以筛之
- 转发之记（可导出）
- 器锁 PIN 码
- Shizuku 一键授权之集
- 六语法律之文（用户之约、隐私之策、免责之告）
- 主流厂商自启之引

**所需**
- Android 7.0 (API 24) 及以上
- SMTP 信匣之号

---

<div align="center">
<sub>Built with Kotlin &amp; Jakarta Mail</sub>
</div>

---

## 许可

本仓库的**代码与文档**采用 [MIT 许可](LICENSE) 发布。
附加的**署名要求、非官方声明与免责条款**见 [NOTICE.md](NOTICE.md)。

简要说明：

- **可自由使用、修改、再分发**（含商用），但须标注出处 —— 本仓库地址与作者
  Nornageste-mh；若你做了修改，须注明「已修改」，不得让人误以为修改版出自原作者。
- **本项目为非官方第三方工具**：本应用是独立开发的无障碍工具，与任何电信运营商、邮件服务商、设备厂商或平台均无隶属关系。仓库内含的多语言法律文本仅为模板，不构成法律意见。
- **按「现状」提供，不承担任何责任**：因使用本软件导致的游戏存档损坏、游戏崩溃、
  账号受限、或与游戏厂商及任何第三方产生的争议与索赔，作者与贡献者均不负责。
  是否使用请自行判断并自担风险。

第三方组件的许可与出处详见 [NOTICE.md](NOTICE.md)。
