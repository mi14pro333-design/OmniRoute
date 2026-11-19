# README (日本語)

🌐 **Languages:** 🇺🇸 [English](../../../README.md) · 🇪🇹 [am](../am/README.md) · 🇸🇦 [ar](../ar/README.md) · 🇦🇿 [az](../az/README.md) · 🇧🇬 [bg](../bg/README.md) · 🇧🇩 [bn](../bn/README.md) · 🇧🇦 [bs](../bs/README.md) · 🇨🇿 [cs](../cs/README.md) · 🇩🇰 [da](../da/README.md) · 🇩🇪 [de](../de/README.md) · 🇬🇷 [el](../el/README.md) · 🇪🇸 [es](../es/README.md) · 🇪🇪 [et](../et/README.md) · 🇮🇷 [fa](../fa/README.md) · 🇫🇮 [fi](../fi/README.md) · 🇫🇷 [fr](../fr/README.md) · 🇮🇪 [ga](../ga/README.md) · 🇮🇳 [gu](../gu/README.md) · 🇳🇬 [ha](../ha/README.md) · 🇮🇱 [he](../he/README.md) · 🇮🇳 [hi](../hi/README.md) · 🇭🇷 [hr](../hr/README.md) · 🇭🇺 [hu](../hu/README.md) · 🇦🇲 [hy](../hy/README.md) · 🇮🇩 [id](../id/README.md) · 🇳🇬 [ig](../ig/README.md) · 🇮🇹 [it](../it/README.md) · 🇬🇪 [ka](../ka/README.md) · 🇰🇭 [km](../km/README.md) · 🇮🇳 [kn](../kn/README.md) · 🇰🇷 [ko](../ko/README.md) · 🇱🇹 [lt](../lt/README.md) · 🇱🇻 [lv](../lv/README.md) · 🇮🇳 [ml](../ml/README.md) · 🇮🇳 [mr](../mr/README.md) · 🇲🇾 [ms](../ms/README.md) · 🇲🇹 [mt](../mt/README.md) · 🇲🇲 [my](../my/README.md) · 🇳🇵 [ne](../ne/README.md) · 🇳🇱 [nl](../nl/README.md) · 🇳🇴 [no](../no/README.md) · 🇮🇳 [or](../or/README.md) · 🇮🇳 [pa](../pa/README.md) · 🇵🇭 [phi](../phi/README.md) · 🇵🇱 [pl](../pl/README.md) · 🇵🇹 [pt](../pt/README.md) · 🇧🇷 [pt-BR](../pt-BR/README.md) · 🇷🇴 [ro](../ro/README.md) · 🇷🇺 [ru](../ru/README.md) · 🇱🇰 [si](../si/README.md) · 🇸🇰 [sk](../sk/README.md) · 🇸🇮 [sl](../sl/README.md) · 🇷🇸 [sr](../sr/README.md) · 🇸🇪 [sv](../sv/README.md) · 🇰🇪 [sw](../sw/README.md) · 🇮🇳 [ta](../ta/README.md) · 🇮🇳 [te](../te/README.md) · 🇹🇭 [th](../th/README.md) · 🇹🇷 [tr](../tr/README.md) · 🇺🇦 [uk-UA](../uk-UA/README.md) · 🇵🇰 [ur](../ur/README.md) · 🇺🇿 [uz](../uz/README.md) · 🇻🇳 [vi](../vi/README.md) · 🇳🇬 [yo](../yo/README.md) · 🇨🇳 [zh-CN](../zh-CN/README.md) · 🇹🇼 [zh-TW](../zh-TW/README.md)

---

<div align="center">

<img src="./docs/screenshots/MainOmniRoute.png" alt="OmniRoute ダッシュボード" width="820"/>

<br/>
<br/>

# 🚀 OmniRoute — 無料の AI ゲートウェイ

**[Diego Souza](https://github.com/diegosouzapw) によって作成**

<img src="./docs/diagrams/readme-hero.svg" width="100%" alt="OmniRoute — コーディングを止めない。すべての AI ツールを、1 つのエンドポイント経由で 394 のプロバイダー（150 以上が無料）へ。Claude Code、Codex、Cursor、Cline、Copilot、Antigravity を、オートフォールバック付きで無料の Claude / GPT / Gemini へ接続。RTK + Caveman の積層圧縮により、トークンを 15～95%（平均約 89%）節約し、制限に達することはありません。394 の AI プロバイダー · 150 以上の無料ティア · 月間約 16.2 億の無料トークン · 22 のルーティング戦略 · $0 で開始。"/>

</div>

<div align="center">

## 💰 サードパーティの無料枠全体で月間約1.62Bトークン

</div>

> **ご自身のプロバイダーアカウントをご利用ください。** これは個別に利用資格のあるサードパーティ無料枠を合算した推定値であり、OmniRouteから付与されるトークンではありません。必要に応じてサインアップして認証情報を取得し、利用できるプロバイダーを接続してください。各プロバイダーが利用上限、提供状況、利用規約を管理しています。
>
> 無料枠を手作業で積み上げるのは大変です — 数十のSDK、数十のレート制限、そして実際にどれだけ利用できるのか分かりません。OmniRouteは、**34個の反復プールキーにまたがる465件の無料枠エントリ**をカタログ化し、共有プールごとに重複排除したうえで、**公開された月間の正の予算を持つ17個のプールと、モデルごとの5つのGroq上限**からトークンの見出し値を算出します。地域の本人確認後にのみ開放されるクォータ（現在はModelScope）は別枠で表示され、地域本人確認後に約600万トークンが追加されますが、見出し値には決して合算されません。結果はダッシュボード（`/dashboard/free-tiers`）に表示され続けます。

<img src="./docs/diagrams/free-tier-budget.svg" width="100%" alt="OmniRouteの無料枠予算カード：月間約16.2億の無料トークンを安定して利用でき、サインアップクレジット込みの初月は最大約22.2億トークン。34個の文書化された反復プールキーが、1つのエンドポイントの背後にある465件のカタログ掲載無料枠エントリをカバーします。共有プールをそれぞれ1回だけ数える、正直なプール重複排除方式の計算です。公開された月間の正のトークン予算を持つ17個の反復プールと、モデルごとの5つのGroq上限も含まれます。利用規約リスクのカタログでは12プロバイダーに「回避」のマークが付いているため、利用するかどうかはご自身で判断できます。予算バーには、Mistral 1B、Nara 210M、LLM7 150M、xKiro 150M、Groq 30M（モデルごとの5つの上限）、その他の小規模プールが含まれます。さらに、初月のサインアップクレジットと、恒久的に無料でトークン上限のないプロバイダーは別途表示されるため、見出し値を膨らませることはありません。`/dashboard/free-tiers` で使用量と残量をリアルタイムに確認できます。"/>

> 稼働中の `/dashboard/free-tiers` ページのアニメーション概要です。完全な方法論（プールの重複排除、クレジット階層、プロバイダー規約）：**[docs/reference/FREE_TIERS.md](docs/reference/FREE_TIERS.md)**。
>
> <sub>これらの数値は、稼働中のカタログに対して2週間ごとに再監査され、**増減します** — プロバイダーが無料枠を終了すれば数値は下がり、新しいプロバイダーが加われば上がります。カタログが実際に算出した値を公開しており、都合のよい最大値に切り上げることは決してありません。</sub>

<br/>

<div align="center">

<h3>

OMNIROUTEが節約や作業の効率化に役立ったなら、リポジトリに⭐を付けてください。

</h3>

[![Stars](https://img.shields.io/github/stars/diegosouzapw/OmniRoute?style=flat&logo=github&logoColor=white&label=Stars&color=e5ac82&labelColor=20211c)](https://github.com/diegosouzapw/OmniRoute)
<a href="https://trendshift.io/repositories/23589" target="_blank"><img src="https://trendshift.io/api/badge/repositories/23589" alt="diegosouzapw%2FOmniRoute | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>
[![Star History Rank](https://api.star-history.com/badge?repo=diegosouzapw/OmniRoute&theme=dark)](https://www.star-history.com/diegosouzapw/omniroute)
[![olud.ai](https://olud.ai/badge.php?tool=diegosouzapw-omniroute)](https://olud.ai/project/diegosouzapw-omniroute.html)

### 💬 コミュニティに参加

**👋 メンテナーをフォロー — 新しいプロバイダー、リリース、ヒントをいち早く入手：**

[![Follow Diego on LinkedIn](https://img.shields.io/badge/Follow_Diego_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&color=e5ac82&labelColor=20211c)](https://www.linkedin.com/in/diegosouzapw/)
[![Follow @diegosouzapw on GitHub](https://img.shields.io/github/followers/diegosouzapw?style=for-the-badge&logo=github&logoColor=white&label=Follow%20on%20GitHub&color=e5ac82&labelColor=20211c)](https://github.com/diegosouzapw)

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white&color=e5ac82&labelColor=20211c)](https://discord.gg/U47eFqAXCn)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&color=e5ac82&labelColor=20211c)](https://t.me/omnirouteOficial)
[![WhatsApp Global](https://img.shields.io/badge/WhatsApp_Global-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&color=e5ac82&labelColor=20211c)](https://chat.whatsapp.com/FvuCbrpZmQ6I85n2vW5QIC?s=cl&p=a&mlu=4)
[![WhatsApp Brasil](https://img.shields.io/badge/WhatsApp_Brasil-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&color=e5ac82&labelColor=20211c)](https://chat.whatsapp.com/KWgatljAjmbELQory59Oti?s=cl&p=a&mlu=4)
[![Website](https://img.shields.io/badge/Website-omniroute.online-blue?logo=google-chrome&logoColor=white&color=e5ac82&labelColor=20211c)](https://omniroute.online)

**質問、プロバイダーに関するヒント、ロードマップ、サポート → [Discord](https://discord.gg/U47eFqAXCn) · [Telegram](https://t.me/omnirouteOficial) · WhatsApp [🌍 グローバル](https://chat.whatsapp.com/FvuCbrpZmQ6I85n2vW5QIC?s=cl&p=a&mlu=4) / [🇧🇷 ブラジル](https://chat.whatsapp.com/KWgatljAjmbELQory59Oti?s=cl&p=a&mlu=4) / [📢 公式チャンネル](https://whatsapp.com/channel/0029VbDwC7A3wtb5PN6a5t2R) / [ポータル](https://portal.sthub.com.br/communities/groups/st-hub/channels/Omniroute-World-8kRjmK)**

<br/>

## 📈ゲートウェイは成長を続ける

<div align="center">

|                                      |           v3.8.50            | **v3.8.51** |      `v3.8.55+`       |
| ------------------------------------ | :--------------------------: | :---------: | :-------------------: |
| 🌐プロバイダー                       |             352              |   **358**   |          394          |
| 🧠独自のチャットモデルIDs            |             1320             |  **1374**   |         1491          |
| 🖼️モダリティブリッジ                 | 🆕ビジョン+オーディオ+ビデオ |      ✓      |           ✓           |
| 📡レーダー無料カタログ               |         🆕オプトイン         |      ✓      |           ✓           |
| ⚖️クォータを意識したスケジューリング |       🆕クォータシェア       |      ✓      |           ✓           |
| 📊クォータ テレメトリ                |           🆕ライブ           |      ✓      |           ✓           |
| 🧰ヘッドレスモード                   |              —               |      —      | 🆕 `serve --headless` |
| 🛤️ LTS鉄道インフラ                   |              —               |      —      |  🆕リリース チャネル  |
| 🔎モデル検出API                      |              —               |      —      | 🆕 `/v1/models/query` |

**→[ロードマップ](ROADMAP.md)— `v3.9.0 LTS`へのレールに乗る**

</div>

<br/>

## 🧩利用可能

[![npm バージョン](https://img.shields.io/npm/v/omniroute?color=cb3837&logo=npm)](https://www.npmjs.com/package/omniroute) ![NPM Monthly](https://img.shields.io/npm/dm/omniroute?label=npm/month&color=cb3837&logo=npm) [![Dockerハブ](https://img.shields.io/docker/v/cheaperinference/omniroute?label=Docker%20Hub&logo=docker&color=2496ED)](https://hub.docker.com/r/cheaperinference/omniroute) [![ライセンス: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square) ](LICENSE) ![Docker Pulls](https://img.shields.io/docker/pulls/diegosouzapw/omniroute?label=docker%20pulls&logo=docker&color=2496ED) ![Electron Downloads](https://img.shields.io/github/downloads/diegosouzapw/omniroute/total?style=flat&label=electron%20downloads&logo=electron&color=47848F)

<table>
  <tr>
    <td align="right"><b>🚀スタート</b></td>
    <td align="center"><a href="#-quick-start">🚀クイックスタート</a></td>
    <td align="center"><a href="#-more-install-methods--docker-source-pnpm-arch">📦インストール</a></td>
    <td align="center"><a href="#first-run">🆓プロバイダーに接続する</a></td>
  </tr>
  <tr>
    <td align="right"><b>💡学ぶ</b></td>
    <td align="center"><a href="#-the-promise">💥約束</a></td>
    <td align="center"><a href="#-why-omniroute">🤔なぜOmniRouteのか</a></td>
    <td align="center"><a href="#-what-sets-omniroute-apart">🏆の特徴</a></td>
  </tr>
  <tr>
    <td align="right"><b>⚙️特徴</b></td>
    <td align="center"><a href="#-combos--the-flagship">🎯コンボ</a></td>
    <td align="center"><a href="#-394-ai-providers--153-catalog-marked-free">🌐プロバイダー</a></td>
    <td align="center"><a href="#-full-cli--a2a--mcp">🔌 CLI &amp; MCP</a></td>
  </tr>
  <tr>
    <td align="right"></td>
    <td align="center"><a href="#%EF%B8%8F-save-1595-tokens--automatically">🗜️圧縮</a></td>
    <td align="center"><a href="#%EF%B8%8F-where-omniroute-runs--anywhere">🖥️が実行される場所</a></td>
    <td align="center"><a href="#-private--local-first">🔒プライベート</a></td>
  </tr>
  <tr>
    <td align="right"><b>👀見てください</b></td>
    <td align="center"><a href="#-omniroute-in-action">🎬の動作中</a></td>
    <td align="center"><a href="#-whats-new">✨の新機能</a></td>
    <td align="center"><a href="#-compatible-clis--coding-agents">🤖互換性のあるCLIs</a></td>
  </tr>
  <tr>
    <td align="right"><b>💚サポート</b></td>
    <td align="center"><a href="#-support-omniroute">💚サポート / 寄付</a></td>
    <td align="center"><a href="#-community--help">💬コミュニティ</a></td>
    <td align="center"><a href="#-sponsors">💖スポンサー</a></td>
  </tr>
  <tr>
    <td align="right"><b>📦プロジェクト</b></td>
    <td align="center"><a href="#%EF%B8%8F-tech-stack">🛠️技術スタック</a></td>
    <td align="center"><a href="#-documentation">📖ドキュメント</a></td>
    <td align="center"><a href="#-1000-contributors">👥寄稿者</a></td>
  </tr>
</table>

</div>

<div align="center">
  <b>🌐 67 か国語で</b>
  <br/><br/>
  <a href="README.md"><img src="docs/assets/flags/us.svg" width="30" alt="English (en)" title="English (en)"></a>
  <a href="docs/i18n/pt-BR/README.md"><img src="docs/assets/flags/br.svg" width="30" alt="Português — Brasil (pt-BR)" title="Português — Brasil (pt-BR)"></a>
  <a href="docs/i18n/pt/README.md"><img src="docs/assets/flags/pt.svg" width="30" alt="Português (pt)" title="Português (pt)"></a>
  <a href="docs/i18n/es/README.md"><img src="docs/assets/flags/es.svg" width="30" alt="Español (es)" title="Español (es)"></a>
  <a href="docs/i18n/fr/README.md"><img src="docs/assets/flags/fr.svg" width="30" alt="Français (fr)" title="Français (fr)"></a>
  <a href="docs/i18n/it/README.md"><img src="docs/assets/flags/it.svg" width="30" alt="Italiano (it)" title="Italiano (it)"></a>
  <a href="docs/i18n/de/README.md"><img src="docs/assets/flags/de.svg" width="30" alt="Deutsch (de)" title="Deutsch (de)"></a>
  <a href="docs/i18n/nl/README.md"><img src="docs/assets/flags/nl.svg" width="30" alt="Nederlands (nl)" title="Nederlands (nl)"></a>
  <a href="docs/i18n/ru/README.md"><img src="docs/assets/flags/ru.svg" width="30" alt="Русский (ru)" title="Русский (ru)"></a>
  <a href="docs/i18n/uk-UA/README.md"><img src="docs/assets/flags/ua.svg" width="30" alt="Українська (uk-UA)" title="Українська (uk-UA)"></a>
  <a href="docs/i18n/pl/README.md"><img src="docs/assets/flags/pl.svg" width="30" alt="Polski (pl)" title="Polski (pl)"></a>
  <a href="docs/i18n/cs/README.md"><img src="docs/assets/flags/cz.svg" width="30" alt="Čeština (cs)" title="Čeština (cs)"></a>
  <a href="docs/i18n/sk/README.md"><img src="docs/assets/flags/sk.svg" width="30" alt="Slovenčina (sk)" title="Slovenčina (sk)"></a>
  <a href="docs/i18n/ro/README.md"><img src="docs/assets/flags/ro.svg" width="30" alt="Română (ro)" title="Română (ro)"></a>
  <a href="docs/i18n/hu/README.md"><img src="docs/assets/flags/hu.svg" width="30" alt="Magyar (hu)" title="Magyar (hu)"></a>
  <a href="docs/i18n/bg/README.md"><img src="docs/assets/flags/bg.svg" width="30" alt="Български (bg)" title="Български (bg)"></a>
  <a href="docs/i18n/da/README.md"><img src="docs/assets/flags/dk.svg" width="30" alt="Dansk (da)" title="Dansk (da)"></a>
  <a href="docs/i18n/fi/README.md"><img src="docs/assets/flags/fi.svg" width="30" alt="Suomi (fi)" title="Suomi (fi)"></a>
  <a href="docs/i18n/no/README.md"><img src="docs/assets/flags/no.svg" width="30" alt="Norsk (no)" title="Norsk (no)"></a>
  <a href="docs/i18n/sv/README.md"><img src="docs/assets/flags/se.svg" width="30" alt="Svenska (sv)" title="Svenska (sv)"></a>
  <a href="docs/i18n/zh-CN/README.md"><img src="docs/assets/flags/cn.svg" width="30" alt="中文 — 简体 (zh-CN)" title="中文 — 简体 (zh-CN)"></a>
  <a href="docs/i18n/zh-TW/README.md"><img src="docs/assets/flags/tw.svg" width="30" alt="中文 — 繁體 (zh-TW)" title="中文 — 繁體 (zh-TW)"></a>
  <a href="docs/i18n/ja/README.md"><img src="docs/assets/flags/jp.svg" width="30" alt="日本語 (ja)" title="日本語 (ja)"></a>
  <a href="docs/i18n/ko/README.md"><img src="docs/assets/flags/kr.svg" width="30" alt="한국어 (ko)" title="한국어 (ko)"></a>
  <a href="docs/i18n/th/README.md"><img src="docs/assets/flags/th.svg" width="30" alt="ไทย (th)" title="ไทย (th)"></a>
  <a href="docs/i18n/vi/README.md"><img src="docs/assets/flags/vn.svg" width="30" alt="Tiếng Việt (vi)" title="Tiếng Việt (vi)"></a>
  <a href="docs/i18n/id/README.md"><img src="docs/assets/flags/id.svg" width="30" alt="Bahasa Indonesia (id)" title="Bahasa Indonesia (id)"></a>
  <a href="docs/i18n/ms/README.md"><img src="docs/assets/flags/my.svg" width="30" alt="Bahasa Melayu (ms)" title="Bahasa Melayu (ms)"></a>
  <a href="docs/i18n/phi/README.md"><img src="docs/assets/flags/ph.svg" width="30" alt="Filipino (phi)" title="Filipino (phi)"></a>
  <a href="docs/i18n/hi/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="हिन्दी (hi)" title="हिन्दी (hi)"></a>
  <a href="docs/i18n/gu/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="ગુજરાતી (gu)" title="ગુજરાતી (gu)"></a>
  <a href="docs/i18n/mr/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="मराठी (mr)" title="मराठी (mr)"></a>
  <a href="docs/i18n/ta/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="தமிழ் (ta)" title="தமிழ் (ta)"></a>
  <a href="docs/i18n/te/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="తెలుగు (te)" title="తెలుగు (te)"></a>
  <a href="docs/i18n/bn/README.md"><img src="docs/assets/flags/bd.svg" width="30" alt="বাংলা (bn)" title="বাংলা (bn)"></a>
  <a href="docs/i18n/ur/README.md"><img src="docs/assets/flags/pk.svg" width="30" alt="اردو (ur)" title="اردو (ur)"></a>
  <a href="docs/i18n/fa/README.md"><img src="docs/assets/flags/ir.svg" width="30" alt="فارسی (fa)" title="فارسی (fa)"></a>
  <a href="docs/i18n/ar/README.md"><img src="docs/assets/flags/sa.svg" width="30" alt="العربية (ar)" title="العربية (ar)"></a>
  <a href="docs/i18n/he/README.md"><img src="docs/assets/flags/il.svg" width="30" alt="עברית (he)" title="עברית (he)"></a>
  <a href="docs/i18n/tr/README.md"><img src="docs/assets/flags/tr.svg" width="30" alt="Türkçe (tr)" title="Türkçe (tr)"></a>
  <a href="docs/i18n/az/README.md"><img src="docs/assets/flags/az.svg" width="30" alt="Azərbaycan (az)" title="Azərbaycan (az)"></a>
  <a href="docs/i18n/sw/README.md"><img src="docs/assets/flags/tz.svg" width="30" alt="Kiswahili (sw)" title="Kiswahili (sw)"></a>
  <a href="docs/i18n/el/README.md"><img src="docs/assets/flags/gr.svg" width="30" alt="Ελληνικά (el)" title="Ελληνικά (el)"></a>
  <a href="docs/i18n/hr/README.md"><img src="docs/assets/flags/hr.svg" width="30" alt="Hrvatski (hr)" title="Hrvatski (hr)"></a>
  <a href="docs/i18n/sr/README.md"><img src="docs/assets/flags/rs.svg" width="30" alt="Српски (sr)" title="Српски (sr)"></a>
  <a href="docs/i18n/lt/README.md"><img src="docs/assets/flags/lt.svg" width="30" alt="Lietuvių (lt)" title="Lietuvių (lt)"></a>
  <a href="docs/i18n/et/README.md"><img src="docs/assets/flags/ee.svg" width="30" alt="Eesti (et)" title="Eesti (et)"></a>
  <a href="docs/i18n/lv/README.md"><img src="docs/assets/flags/lv.svg" width="30" alt="Latviešu (lv)" title="Latviešu (lv)"></a>
  <a href="docs/i18n/sl/README.md"><img src="docs/assets/flags/si.svg" width="30" alt="Slovenščina (sl)" title="Slovenščina (sl)"></a>
  <a href="docs/i18n/mt/README.md"><img src="docs/assets/flags/mt.svg" width="30" alt="Malti (mt)" title="Malti (mt)"></a>
  <a href="docs/i18n/ga/README.md"><img src="docs/assets/flags/ie.svg" width="30" alt="Gaeilge (ga)" title="Gaeilge (ga)"></a>
  <a href="docs/i18n/kn/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="ಕನ್ನಡ (kn)" title="ಕನ್ನಡ (kn)"></a>
  <a href="docs/i18n/ml/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="മലയാളം (ml)" title="മലയാളം (ml)"></a>
  <a href="docs/i18n/or/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="ଓଡ଼ିଆ (or)" title="ଓଡ଼ିଆ (or)"></a>
  <a href="docs/i18n/pa/README.md"><img src="docs/assets/flags/in.svg" width="30" alt="ਪੰਜਾਬੀ (pa)" title="ਪੰਜਾਬੀ (pa)"></a>
  <a href="docs/i18n/ne/README.md"><img src="docs/assets/flags/np.svg" width="30" alt="नेपाली (ne)" title="नेपाली (ne)"></a>
  <a href="docs/i18n/si/README.md"><img src="docs/assets/flags/lk.svg" width="30" alt="සිංහල (si)" title="සිංහල (si)"></a>
  <a href="docs/i18n/my/README.md"><img src="docs/assets/flags/mm.svg" width="30" alt="မြန်မာ (my)" title="မြန်မာ (my)"></a>
  <a href="docs/i18n/km/README.md"><img src="docs/assets/flags/kh.svg" width="30" alt="ខ្មែរ (km)" title="ខ្មែរ (km)"></a>
  <a href="docs/i18n/ha/README.md"><img src="docs/assets/flags/ng.svg" width="30" alt="Hausa (ha)" title="Hausa (ha)"></a>
  <a href="docs/i18n/yo/README.md"><img src="docs/assets/flags/ng.svg" width="30" alt="Yorùbá (yo)" title="Yorùbá (yo)"></a>
  <a href="docs/i18n/ig/README.md"><img src="docs/assets/flags/ng.svg" width="30" alt="Igbo (ig)" title="Igbo (ig)"></a>
  <a href="docs/i18n/am/README.md"><img src="docs/assets/flags/et.svg" width="30" alt="አማርኛ (am)" title="አማርኛ (am)"></a>
  <a href="docs/i18n/uz/README.md"><img src="docs/assets/flags/uz.svg" width="30" alt="Oʻzbekcha (uz)" title="Oʻzbekcha (uz)"></a>
  <a href="docs/i18n/ka/README.md"><img src="docs/assets/flags/ge.svg" width="30" alt="ქართული (ka)" title="ქართული (ka)"></a>
  <a href="docs/i18n/hy/README.md"><img src="docs/assets/flags/am.svg" width="30" alt="Հայերեն (hy)" title="Հայերեն (hy)"></a>
  <a href="docs/i18n/bs/README.md"><img src="docs/assets/flags/ba.svg" width="30" alt="Bosanski (bs)" title="Bosanski (bs)"></a>
</div>

<br/>
<br/>

<div align="center">

<a id="first-run"></a>

## 🆓 インストールしてプロバイダーを接続し、1つのエンドポイント経由でルーティング

</div>

<img src="./docs/diagrams/works-zero-config.svg" width="100%" alt="3つの手順：OmniRouteをインストールして起動し、自分のアカウントまたはAPIキーで対象プロバイダーを接続し、OmniRoute APIキーとmodel autoを使用してツールの接続先をlocalhost:20128/v1に設定します。ルーティングは、利用可能な対象接続とプロバイダーの制限に依存します。"/>

```bash
# プロバイダーを接続したら、Dashboard → Endpoints からOmniRouteキーをコピーします：
curl http://localhost:20128/v1/chat/completions \
  -H "Authorization: Bearer YOUR_OMNIROUTE_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"auto","messages":[{"role":"user","content":"Hello!"}]}'
```

<sub>`auto`には対象ルートが必要です。新規インストールでは、キー不要で利用できる対象が存在しない場合があり、キー不要のプロバイダーがサードパーティー製クライアントを拒否することもあります。Kiroを含む`tos: avoid`のマークが付いたプロバイダーは、デフォルトで自動ルーティングから除外されます。アカウントを接続しても、この設定は上書きされません。プロバイダーを選ぶ前に、[無料ティアガイド](docs/getting-started/FREE-TIERS-GUIDE.md)を参照してください。</sub>

<sub>📦 **Python、Node.js、PHP、cURL** 用のコピーペースト可能なクイックスタートスクリプト → [`examples/quickstart/`](examples/quickstart/)</sub>

<br/>

<div align="center">

# 💥 OmniRouteの約束

</div>

<img src="./docs/diagrams/promise-pillars.svg" width="100%" alt="OmniRouteの約束 — 1つのエンドポイントと394のプロバイダー。別の正常な対象が利用可能な間は、自動フォールバックによってルーティングを継続します。6つの柱：394のプロバイダーにまたがる高耐障害性フォールバック · 対象ワークロードで最大95%のトークン削減 · 150以上の無料ティアと、継続利用可能またはキー不要で永久無料の51プロバイダーにより、$0から開始可能 · 1つの設定で39のCLI/エージェント統合 · /v1でのOpenAI、Claude、Gemini、Responses API互換性 · サーキットブレーカー、TLSステルス、MCP 110ツール、A2A、メモリ、ガードレール、評価機能、7,800以上の追跡テストファイルにまたがる56,000以上の静的テスト宣言などの本番環境向け制御。"/>

<br/>
<br/>

<div align="center">

# 🤔 なぜOmniRouteなのか？

</div>

<img src="./docs/diagrams/why-pain-fix.svg" width="100%" alt="なぜOmniRouteなのか — 10個のダッシュボード、使えなくなったAPIキー、予想外の請求額をやりくりするのをやめましょう。日々の10の問題と解決策：未使用のままクォータが期限切れになる → サブスクリプションを最大限活用；コーディング中にレート制限に達する → 4段階の自動フォールバック（サブスクリプション → API → 低コスト → 無料）；ツール出力でトークンを消費する → RTK + Caveman圧縮（15–95%）；高価なAPI → コスト最適化ルーティング；ツールごとに個別の設定が必要 → 1つのエンドポイント、1つのダッシュボード；AIがブロックされる → 3段階プロキシ + TLSステルス；使えなくなったキー → 3層の耐障害性（サーキットブレーカー、キーのクールダウン、モデルのロックアウト）；チームで1つのサブスクリプションを共有 → 公平なクォータ配分を備えたキープール；誰かのクラウド経由でプロンプトを送信 → AES-256-GCMで暗号化されたキーによるローカルファースト；支出の可視性がない → ライブ分析（使用量、クォータ、節約額、p95レイテンシ）。"/>

<div align="center">

<img src="./docs/diagrams/tier-cascade.svg" width="100%" alt="OmniRouteのリクエストフロー：IDEまたはCLI（Claude Code、Cursor、Cline…）が1つのローカルエンドポイント（http://localhost:20128/v1）を呼び出します。OmniRoute Smart Router（RTK + Caveman圧縮、22のルーティング戦略、サーキットブレーカー、TLSステルス、MCP、A2A、ガードレール）は、対象となる正常な対象が存在する間、4つのプロバイダーティアにまたがってフォールバックできます — ティア1 サブスクリプション、ティア2 APIキー、ティア3 低コスト、ティア4 無料。"/>

</div>

<br/>

<div align="center">

## 🤝 オープンソースフレンドによるサポート

</div>

<p align="center">
  <a href="https://platform.kimi.ai?track_id=track-8197581fdd7d4139a0f562e4a03c3798&aff=omniroute">
    <img src="public/sponsors/kimi-k3-banner.png" width="100%" alt="Kimi K3 — オープンフロンティアインテリジェンス · 2.8Tパラメータ · 1Mトークンコンテキスト"/>
  </a>
</p>

> **オープンソースフレンドとして参加しませんか？** これらの企業はオープンソースを支援し、OmniRouteの活動を継続するのに役立っています。そして、私たちは彼らが提供するすべてのトークンがどこに使われるかを公にしています。ご連絡ください: [diegosouza.pw@outlook.com](mailto:diegosouza.pw@outlook.com)

<table>
  <tr>
    <td align="center" width="150">
      <a href="https://platform.kimi.ai?track_id=track-8197581fdd7d4139a0f562e4a03c3798&aff=omniroute">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="public/providers/kimi-logomark-dark.svg">
          <img src="public/providers/kimi-logomark-light.svg" width="64" alt="Kimi (Moonshot AI)"/>
        </picture>
      </a>
      <br/><b>Kimi</b><br/><sub>Moonshot AI</sub><br/><br/>
      <img src="https://img.shields.io/badge/Founding_Friend-1783FF?style=flat-square" alt="創設オープンソースフレンド"/>
    </td>
    <td>
      このプロジェクトを支援してくださる、創設オープンソースフレンドである<b>Kimi (Moonshot AI)</b>に感謝いたします！Kimiは、オープンウェイトのK2およびK3モデルファミリーを開発するAIラボです。<b>Kimi K3</b>は、1Mトークンのコンテキストウィンドウ、ネイティブビジョン、フロンティアレベルのコーディングを、クローズドモデルのわずかな価格で提供し、Claude Code、Codex、およびOmniRouteが提供するすべてのコーディングツールとすぐに連携します。
      <br/><br/>
      <b>Kimiのサポートがもたらすもの:</b> KimiのAPIクレジットは、OmniRouteのAI検証済みリリースパイプライン（すべてのプルリクエストが出荷される前にレビューされる<i>Kimi K3によるマージ検証</i>ステージ）と、日々の機能開発を支えています。ファーストクラスのKimiサポートは、直接の<a href="https://platform.kimi.ai?track_id=track-8197581fdd7d4139a0f562e4a03c3798&aff=omniroute">Kimi API</a>（<code>kimi-k3</code>）と<a href="https://www.kimi.ai/code?aff=omniroute">Kimi Codeコーディングプラン</a>（OAuthおよびAPIキー）の両方で提供されます。OmniRouteは、Kimiのサポートプログラムにおける最初のブラジル製オープンソースプロジェクトでもあります。<a href="https://platform.kimi.ai?track_id=track-8197581fdd7d4139a0f562e4a03c3798&aff=omniroute"><b>15%追加クレジット付きのKimi APIキーを入手 →</b></a>
    </td>
  </tr>
  <tr>
    <td align="center" width="150">
      <a href="https://cheaperinference.com/?utm_source=omniroute">
        <img src="./public/providers/cli-generic.svg" width="64" alt="Cheaper Inference"/>
      </a>
      <br/><b>Cheaper Inference</b><br/><sub>cheaperinference.com</sub><br/><br/>
      <img src="https://img.shields.io/badge/Open_Source_Friend-31f889?style=flat-square&labelColor=04170d" alt="オープンソースフレンド"/>
    </td>
    <td>
      このプロジェクトを支援してくださる、OmniRouteのオープンソースフレンドである<b>Cheaper Inference</b>に感謝いたします！Cheaper Inferenceは、42のフロンティアモデル（Claude、GPT-5.x、Gemini、Kimi K3、GLM、DeepSeek、Grok、MiniMax）を1つのOpenAI互換エンドポイントの背後で再販する、コストランク付けされたゲートウェイです。各リクエストを最も安価な適格プロバイダーにルーティングし、モデルメーカーの定価を超える料金を請求することはありません。
      <br/><br/>
      <b>OmniRouteでのファーストクラスサポート:</b> チャット補完、ネイティブの<code>/v1/responses</code>エンドポイント、ビジョン、ツール呼び出し、および3つの画像モデル（<code>grok-imagine</code>、<code>nano-banana-pro</code>、<code>nano-banana-2</code>、<code>cheaperinference/&lt;model&gt;</code>としてアクセス可能）。<a href="https://cheaperinference.com/?utm_source=omniroute"><b>APIキーを入手 →</b></a>
    </td>
  </tr>
</table>

<sub><code>aff=omniroute</code>タグ付きのリンクはパートナーリンクです。これらは追加費用なしでプロジェクトに資金を提供します。</sub>

<br/>

<details open>
<summary><sub><b>🎟️ アフィリエイトプロモーション</b> — スポンサーではないプロバイダーからの無料登録クーポン（クリックで展開）</sub></summary>

<sub><i>このセクションは紹介/クーポンコードのみを対象としています。スポンサーシップパートナーシップは上記の<b>🤝 オープンソースフレンドによるサポート</b>に記載されています。OmniRouteはここに記載されているプロバイダーとのスポンサーシップやパートナーシップは一切ありません。これらは誰でも利用できる公開クーポンです。</i></sub>

<table>
  <tr>
    <td align="center" width="120">
      <a href="https://agentrouter.org/register?aff=70LM">
        <img src="./public/providers/cli-generic.svg" width="32" alt="AgentRouter"/>
      </a>
      <br/><sub><b>AgentRouter</b></sub><br/><sub>agentrouter.org</sub>
    </td>
    <td>
      <sub><b><a href="https://agentrouter.org/register?aff=70LM">AgentRouter</a></b> — アフィリエイト登録 · 登録時に<b>$100の無料クレジット</b>（無料サーバー、レイテンシが高くなる可能性があります — 本番環境ではなくテストに最適）。OmniRouteでは<b>v3.8.50</b>以降、チャット補完、Anthropic互換のワイヤーフォーマット、OpenAI互換パスでファーストクラスのサポートを提供。利用可能なモデルには<code>claude-opus-4-8</code>、<code>claude-opus-5</code>、<code>gpt-5.6-sol</code>などがあります。<b><a href="https://agentrouter.org/register?aff=70LM">$100を獲得 →</a></b></sub>
      <br/><br/>
      <sub>⚠️ <i>アフィリエイトリンク — OmniRouteはこのプロバイダーとのスポンサーシップやパートナーシップはありません。</i></sub>
    </td>
  </tr>
</table>

<sub>OmniRouteユーザーに利益をもたらす、寛大な無料登録クーポンを提供する他のプロバイダーをご存知ですか？イシューをオープンしていただければ、ここに追記します。</sub>

</details>

<br/>

<div align="center">

## 🎯 コンボ — フラッグシップ

</div>

<img src="./docs/diagrams/strategies-grid.svg" width="100%" alt="22種類のコンボルーティング戦略のうち18種類のアニメーション例 — priority、fill-first、weighted、round-robin、p2c、least-used、random、strict-random、cost-optimized、headroom、reset-window、reset-aware、context-relay、context-optimized、lkgp、auto、fusion、pipelineの各戦略につき1タイル。cache-optimized、quota-weighted、expiry-first、jevにはアニメーションがなく、以下の表で22種類すべてを説明しています。"/>

> **コンボ**とは、OmniRouteが**自動的に**順番にルーティングするモデルのチェーンです。クォータを使い切った場合、プロバイダーに障害が発生した場合、またはコストが急増した場合、コンボは利用可能で正常な次のモデルへ移行できます。 🛡️

### ⚡ ゼロ設定 — `auto` を使うだけ

作成するコンボはありません。モデルを `auto`（またはそのバリアント）に設定すると、OmniRouteは接続済みのプロバイダーから、リアルタイムのスコアに基づいて仮想コンボを構築します。

<table>
  <tr><th align="left">モデルID</th><th align="left">最適化の対象</th></tr>
  <tr><td align="left" nowrap><code>auto</code></td><td align="left">🎯 バランスの取れたデフォルト（LKGP — 最後に正常だったプロバイダーを使い続ける）</td></tr>
  <tr><td align="left" nowrap><code>auto/coding</code></td><td align="left">🧑💻 コード生成向けの品質優先の重み付け</td></tr>
  <tr><td align="left" nowrap><code>auto/fast</code></td><td align="left">⚡ 最低レイテンシを優先</td></tr>
  <tr><td align="left" nowrap><code>auto/cheap</code></td><td align="left">💰 トークンあたりの低コストを優先</td></tr>
  <tr><td align="left" nowrap><code>auto/subscription</code></td><td align="left">🎟️ 既に料金を支払っているサブスクリプションクォータのみを使用 — フェイルクローズし、請求対象となるフォールバックは使用しません（<a href="./docs/routing/SUBSCRIPTION_LADDER.md">ガイド</a>）</td></tr>
  <tr><td align="left" nowrap><code>auto/thrifty</code></td><td align="left">🪜 まずプランのクォータを使用し、その後は最も安価な有料オプションへ一段ずつ移行 — リセット後はプランに戻ります（<a href="./docs/routing/SUBSCRIPTION_LADDER.md">ガイド</a>）</td></tr>
  <tr><td align="left" nowrap><code>auto/offline</code></td><td align="left">🔋 クォータまたはレート制限の余裕が最も大きいものを優先</td></tr>
  <tr><td align="left" nowrap><code>auto/smart</code></td><td align="left">🔭 品質優先 + より良いモデルを見つけるための10%の探索</td></tr>
  <tr><td align="left" nowrap><code>auto/lkgp</code></td><td align="left">📌 最後に正常だったプロバイダーを明示的に優先</td></tr>
  <tr><td align="left" nowrap><code>auto/chaos</code></td><td align="left">🧪 複数のモデル（デフォルトではプロバイダーごとに1つ、計5つ）への並列ファンアウトを行い、1つの回答を返します。パネル内の各モデルにつき1回のアップストリーム呼び出しを行いますが、フォールトインジェクションではありません</td></tr>
</table>

##

### 🔀 独自の構成を作成 — 22種類のルーティング戦略

**22種類**すべての戦略を、コンボの各ステップで自由に組み合わせられます：

<table>
  <tr>
    <th>#</th>
    <th align="left">戦略</th>
    <th align="left">動作</th>
  </tr>
  <tr>
    <td align="center">1</td>
    <td nowrap><code>priority</code></td>
    <td>最初のターゲットから順に処理し、各ターゲットを使い切ってから次へ進む 🥇</td>
  </tr>
  <tr>
    <td align="center">2</td>
    <td nowrap><code>fill-first</code></td>
    <td>各ターゲットの割り当て枠を完全に埋めてから次へ進む</td>
  </tr>
  <tr>
    <td align="center">3</td>
    <td nowrap><code>weighted</code></td>
    <td>ターゲットごとの重みに基づく重み付きランダム</td>
  </tr>
  <tr>
    <td align="center">4</td>
    <td nowrap><code>round-robin</code></td>
    <td>ターゲットを順番に巡回する</td>
  </tr>
  <tr>
    <td align="center">5</td>
    <td nowrap><code>p2c</code></td>
    <td>2つの候補から選ぶ方式によるランダム負荷分散</td>
  </tr>
  <tr>
    <td align="center">6</td>
    <td nowrap><code>least-used</code></td>
    <td>現在の負荷が最も低いターゲットを選択する</td>
  </tr>
  <tr>
    <td align="center">7</td>
    <td nowrap><code>random</code></td>
    <td>一様ランダムに選択（重複排除）</td>
  </tr>
  <tr>
    <td align="center">8</td>
    <td nowrap><code>strict-random</code></td>
    <td>重複を排除せずにランダム選択 🎲</td>
  </tr>
  <tr>
    <td align="center">9</td>
    <td nowrap><code>cost-optimized</code></td>
    <td>ライブカタログの価格情報に基づき、リクエストあたりの $ を最小化 💸</td>
  </tr>
  <tr>
    <td align="center">10</td>
    <td nowrap><code>headroom</code></td>
    <td>残りの割り当て枠が最も多いターゲットを選択する</td>
  </tr>
  <tr>
    <td align="center">11</td>
    <td nowrap><code>quota-weighted</code></td>
    <td>使い切ったアカウントを除外し、残りの割り当て枠 ÷ 実行中の負荷に比例して選択する — 既存の会話は同じターゲットに固定される ⚖️</td>
  </tr>
  <tr>
    <td align="center">12</td>
    <td nowrap><code>reset-window</code></td>
    <td>割り当て枠のウィンドウが最も早くリセットされるターゲットを優先する</td>
  </tr>
  <tr>
    <td align="center">13</td>
    <td nowrap><code>reset-aware</code></td>
    <td>割り当て枠のリセット時刻で順位付けする — 短いウィンドウを優先 📊</td>
  </tr>
  <tr>
    <td align="center">14</td>
    <td nowrap><code>context-relay</code></td>
    <td>長い会話のためにターゲット間でコンテキストを引き継ぐ 🧠</td>
  </tr>
  <tr>
    <td align="center">15</td>
    <td nowrap><code>context-optimized</code></td>
    <td>現在のコンテキストサイズに最適なターゲットを選択する</td>
  </tr>
  <tr>
    <td align="center">16</td>
    <td nowrap><code>cache-optimized</code></td>
    <td>再利用可能な各プロンプトプレフィックスを同じアカウントに固定し、プロンプトキャッシュのヒット率を最大化する 🎯</td>
  </tr>
  <tr>
    <td align="center">17</td>
    <td nowrap><code>lkgp</code></td>
    <td>Last-Known-Good Path — 最後に成功したプロバイダーに固定し、その後はルールにフォールバックする</td>
  </tr>
  <tr>
    <td align="center">18</td>
    <td nowrap><code>auto</code></td>
    <td>すべての接続を対象に、16要素でリアルタイムスコアリングする 🤖</td>
  </tr>
  <tr>
    <td align="center">19</td>
    <td nowrap><code>fusion</code></td>
    <td>複数のモデルに分散して実行し、判定役が1つの回答に統合する 🧬</td>
  </tr>
  <tr>
    <td align="center">20</td>
    <td nowrap><code>pipeline</code></td>
    <td>ステップを連結し、各ターゲットの出力を次のターゲットに渡す 🔗</td>
  </tr>
  <tr>
    <td align="center">21</td>
    <td nowrap><code>expiry-first</code></td>
    <td>未使用のまま最初に期限切れになるアカウントを使う — リセットが最も近く、残りの割り当て枠が最も多いものを優先 ⏳</td>
  </tr>
  <tr>
    <td align="center">22</td>
    <td nowrap><code>jev</code></td>
    <td>ユーザーが順位付けしたリストを使用し、TypeSafe Jev がリクエストごとに実行するエントリを選択する。選択できない場合はユーザーの順序にフォールバックする（オプトインフラグ） ⚖️</td>
  </tr>
</table>

<sub>Auto-Combo エンジンは、すべての候補を**16要素**（健全性、割り当て枠、コスト、レイテンシ、タスク適合性、品質、セッションの可用性など）でスコアリングします — [`docs/routing/AUTO-COMBO.md`](docs/routing/AUTO-COMBO.md) を参照してください。</sub>

##

### 🧱 レジリエンスを組み込み済み（独立した3つのレイヤー）

<img src="./docs/diagrams/resilience-layers.svg" width="100%" alt="OmniRoute のレジリエンス — 独立した3つの自己修復レイヤーで、障害に応じて適切なレイヤーが対応します。レイヤー1 プロバイダーサーキットブレーカー（プロバイダー全体）：408/5xx の場合のみ作動し、しきい値は OAuth 8× / API-key 12× / local 2×。60秒/30秒/15秒後に HALF-OPEN プローブへ移行し、遅延回復します。OPEN 中はコンボが次のプロバイダーへ再ルーティングします。レイヤー2 接続クールダウン（1つのキー/アカウント）：基本時間は OAuth 5秒 / API-key 3秒で、指数バックオフ ×2 とサンダリングハード防止ガードを使用します。429 では Retry-After を尊重し、成功するとすべてのエラー状態をクリアします。クールダウン中のキーはスキップされますが、同じ接続の他のキーは処理を継続します。レイヤー3 モデルロックアウト（1つのモデル）：モデル単位の429、local の404、またはモード拒否が発生した場合、そのモデルだけをロックし、接続全体をロックすることはありません。終端状態（禁止、期限切れ、クレジット枯渇）はオペレーター向けであり、クールダウンの対象ではありません。"/>

<sub>📖 [Auto-Combo エンジン](docs/routing/AUTO-COMBO.md) · [レジリエンスガイド](docs/architecture/RESILIENCE_GUIDE.md)</sub>

<br/>

<div align="center">

## 🏆 OmniRouteを際立たせる要素

</div>

<img src="./docs/diagrams/comparison-table.svg" width="100%" alt="OmniRouteを際立たせる要素 — 13の機能における、9router、OpenRouter、CLIProxyAPI、LiteLLMとの日付付き機能スナップショット比較。OmniRouteには、394のプロバイダー、組み込みの150以上の無料ティア、22のルーティング戦略、12エンジンによるトークン圧縮、110のツールを備えた組み込みMCPサーバー、A2Aエージェントプロトコル、永続メモリ、ガードレール、クラウドエージェント、TLSフィンガープリントステルス、Desktop/Termux/PWA、67のi18n UIロケールが含まれます。OmniRouteはMITライセンスで提供され、セルフホスト可能です。競合製品の機能や数は変更される場合があります。詳細はリンク先の方法論をご覧ください。"/>

<sub>📊 9router、OpenRouter、CLIProxyAPI、LiteLLMとの完全な方法論および機能別の詳細 → [`docs/comparison/OMNIROUTE_VS_ALTERNATIVES.md`](docs/comparison/OMNIROUTE_VS_ALTERNATIVES.md)</sub>

<br/>

## 💚 OmniRoute を支援する

OmniRoute は MIT ライセンスで公開され、オープンに保守されています。時間や費用の節約に役立った場合は、独立性を維持するために、ご自分に合った方法でご支援ください。スポンサーシップがルーティングの優先順位に影響することはありません。得られるのは可視性であり、順位ではありません。

<table>
  <tr><td nowrap>⭐ <b>リポジトリにスターを付ける</b></td><td>無料 — 可視性の向上に本当に役立ちます</td><td><a href="https://github.com/diegosouzapw/OmniRoute">OmniRoute にスターを付ける</a></td></tr>
  <tr><td nowrap>🐙 <b>GitHub Sponsors</b></td><td>単発または月額 · プラットフォーム手数料なし</td><td><a href="https://github.com/sponsors/diegosouzapw">github.com/sponsors/diegosouzapw</a></td></tr>
  <tr><td nowrap>☕ <b>Ko-fi</b></td><td>手軽な単発支援、支援者の登録は不要</td><td><a href="https://ko-fi.com/diegosouzapw">ko-fi.com/diegosouzapw</a></td></tr>
  <tr><td nowrap>🧋 <b>Buy Me a Coffee</b></td><td>少額で気軽な支援</td><td><a href="https://www.buymeacoffee.com/diegosouzapw">buymeacoffee.com/diegosouzapw</a></td></tr>
  <tr><td nowrap>🖐 <b>Liberapay</b></td><td>継続支援 · 非営利 · オープンソース</td><td><a href="https://liberapay.com/diegosouzapw">liberapay.com/diegosouzapw</a></td></tr>
  <tr><td nowrap>🇧🇷 <b>PIX</b>（ブラジル）</td><td>即時、手数料なし</td><td>キーと QR は以下</td></tr>
  <tr><td nowrap>₿ <b>暗号資産</b></td><td>BTC · ETH · USDT-TRC20 · USDC-Solana</td><td>アドレスは以下</td></tr>
</table>

**🇧🇷 PIX** — 即時、手数料なし（ブラジル）

<img src="docs/assets/pix-qr.png" width="140" align="right" alt="OmniRoute の PIX QR コード"/>

キー（ランダム）：`5d865059-bc44-483a-962d-43ceb80126eb`

Pix コピー＆ペースト：

```
00020101021126580014br.gov.bcb.pix01365d865059-bc44-483a-962d-43ceb80126eb5204000053039865802BR5922OMNIROUTE CONTRIBUICAO6006BRASIL62070503***630475DD
```

<br clear="right"/>

<details>
<summary><b>₿ 暗号資産</b> — BTC · ETH · USDT-TRC20 · USDC-Solana（クリックして展開）</summary>

<table>
  <tr><td nowrap><b>₿ BTC</b></td><td nowrap>Bitcoin (SegWit)</td><td><code>bc1qh00smz004sy85wyl28v77tenkt3ckl6eaep7fd</code></td></tr>
  <tr><td nowrap><b>Ξ ETH</b></td><td nowrap>Ethereum (ERC20)</td><td><code>0x64Cf6B68A6Ff34288e89172950a2d00102337a84</code></td></tr>
  <tr><td nowrap><b>₮ USDT</b></td><td nowrap>Tron (TRC20)</td><td><code>TKAF41JpuQrHbKTnsQa9svJE2T192Hvsc2</code></td></tr>
  <tr><td nowrap><b>$ USDC</b></td><td nowrap>Solana</td><td><code>2emNNZzVVWQc3FQ2wk9M6qXUQmW8AKdjjL174fXR28Tu</code></td></tr>
</table>

<sub>⚠️ 各コインは、表示されているネットワークでのみ送金してください。誤ったネットワークで送金すると、資金を失う可能性があります。</sub>

</details>

🐛 バグを見つけた場合やフィードバックがある場合は、[Discussion](https://github.com/diegosouzapw/OmniRoute/discussions) を作成してください。

<br/>

<p><strong>開発者向け注記：</strong> このプロジェクトでは、開発者の利便性のため、npm install/postinstall の実行中にローカルの <code>.env</code> ファイルが生成される場合があります。このファイルは意図的に <code>.gitignore</code> 経由で無視されており（<code>.gitignore</code> を参照）、決してコミットしてはなりません。誤ってコミットした場合は、露出したシークレットをすべてローテーションし、履歴からそのファイルを削除してください。ローカル環境ファイルとシークレットの管理方法については、<a href="docs/DEVELOPER-ENVIRONMENT.md">docs/DEVELOPER-ENVIRONMENT.md</a> を参照してください。</p>

## 📡 OmniRoute Radar

無料枠の主な目安は、上記のドキュメント化されたプール重複排除済みカタログに基づき、引き続き**月間約1.62Bトークン**です。プロバイダーの一時的なサインアップクレジットにより、初月は別途**約2.22B**まで増える可能性があります。Radarは、OmniRouteのリリース間でも無料モデルの提供状況をより最新の状態で把握したい方のための、署名付きカタログオーバーレイです。利用は任意であり、コミュニティカタログおよび既存のすべての無料機能は、引き続き無料です。

サポーターは、ライブカタログと追加のプロバイダー利用機会を受け取ることができます。この枠は独立して変動し、プロバイダーの提供状況に応じて、上限は**最大で月間約3Bトークン**です。この上限は保証されるものではありません。プロバイダーは、割り当て量、利用資格、モデル、または対象地域をいつでも変更できます。

Radarはオプトイン方式で、GETリクエストのみを使用します。OmniRouteクライアントが、プロンプト、トラフィック、プロバイダー設定、使用状況テレメトリ、またはローカルのお知らせ非表示状態をアップロードすることはありません。利用資格と現在のカタログについては、**[radar.omniroute.online/planos](https://radar.omniroute.online/planos)**をご覧ください。

<br/>

<div align="center">

## ✨の新機能

</div>

> 最近のハイライト**v3.8.20 → v3.8.55** 。 [`CHANGELOG.md`](CHANGELOG.md)の全履歴。

- **⚖️ `quota-weighted`ルーティング**— 20 番目のコンボ戦略は、使い果たされたアカウントをスキップし、残りのクォータ÷の飛行中の負荷に比例して残りのアカウントを描画し、既存の会話を固定したままにします。 →[オートコンボ](docs/routing/AUTO-COMBO.md)
- **🧰ヘッドレスモード**— `omniroute serve --headless` (または`OMNIROUTE_HEADLESS=1`) は、ダッシュボードおよびダッシュボード専用サブシステムをオフにして、 `/v1/*`プロキシ エンジンのみを実行します。 →[ヘッドレスモード](docs/guides/HEADLESS.md)
- **🔎モデルの検出**— `/v1/models`機能、コンテキスト、種類、テキストによってフィルタリングし、 `POST /v1/models/query`同じキーごとの可視性を持つ短い決定論的な候補リストを返します。 → [APIリファレンス](docs/reference/API_REFERENCE.md)
- **🔑キーごとのルーティング制御**— 、 APIキーを 1 つのモデルまたは`forcedModel`とのコンボに固定し、キーのモデルとコンボをアトミックに追加または削除します (`/api/keys/{id}/access`)。 → [APIリファレンス](docs/reference/API_REFERENCE.md)· [OpenAPI](docs/openapi.yaml)
- **🛡️より細かいPIIコントロール**—タイプごとの選択、最大 20 個の検証済みカスタム マスキング パターンおよびタイプごとの検出カウンター。マスキング自体はオプトインのままです。 →[ガードレール](docs/security/GUARDRAILS.md)
- **🌍 67 言語**—ダッシュボード、ドキュメント ミラー、およびCLI `npm run i18n:add-locale`使用すると、1 つのコマンドであらゆる場所に言語を追加できます。 → [i18n ガイド](docs/guides/I18N.md)
- **🎛️ OmniConductor**エージェント フリートへの—インバウンドA2A委任、エージェント カードのコンダクター スキル、および Faro プッシュツートーク音声チャットを備えたダッシュボード パネル。 → [A2Aサーバー](docs/frameworks/A2A-SERVER.md)
- **🛂適応型アドミッションおよび過負荷保護**—ヘビーウェイト チャット リクエストは、接続ごとにアトミックなRPMローリング リースを使用して、503 の代わりにキューに入れられます。 →[レジリエンス ガイド](docs/architecture/RESILIENCE_GUIDE.md)
- **🗂️正規`/v1/models`順序付け**—プロバイダーごとに 1 つの連続したプロバイダー グループ化ブロック (最初に固定されたコンボ)。すべてのカタログ ソースにわたって安定しています。 → [APIリファレンス](docs/reference/API_REFERENCE.md)
- **🗜️圧縮硬化**—デフォルトオンのインフレガード、 DE / FR / JA +中国語 (wényán) 用の Caveman パック、Gradle および 用のRTKフィルター。NET。 →[圧縮](docs/compression/COMPRESSION_ENGINES.md)
- **💸正直な定額料金**—サブスクリプション / コーディング プラン プロバイダーの読み取り**$0**コスト分析において。予算、割り当て、ルーティングの見積もりを続けます。 → [APIリファレンス](docs/reference/API_REFERENCE.md)
- **⚖️クォータ共有ルーティング**— 、共有アカウントのクォータをプールされたキー間で公平に分割し、作業を節約するため、アイドル状態のスライスが貸し出されます。 →[レジリエンス ガイド](docs/architecture/RESILIENCE_GUIDE.md)
- **🤖ワンコマンドCLI/agentセットアップ**— 15 個の登録された`setup-*`コマンド。 `omniroute run` 7 つのCLIs (Claudeコード、 Codex、 Aider、Goose、 OpenCode、 Qwenコード、 Gemini CLI) を起動します。 `omniroute configure`対話型プロバイダーの+モデル ピッカーとコンテキストごとのお気に入りを備えた 11 のターゲットをサポートします。 → [CLI統合](docs/guides/CLI-INTEGRATIONS.md)
- **🛰️リモートモード**—スコープ付きトークン (`connect` / `contexts` / `tokens`) を使用してリモートOmniRouteドライブします。 + `antigravity` VPSインストール用のOAuthヘルパー。 →[リモートモード](docs/guides/REMOTE-MODE.md)
- **🧭よりスマートな自動ルーティング**— `auto/<category>:<tier>`コンボ、**融合**(モデルパネル+ジャッジ)、タスク認識ルーティング、リクエストごとのモデル / モード / USD 予算オーバーライド。 →[オートコンボ](docs/routing/AUTO-COMBO.md)
- **🗜️プラガブル圧縮**— 12 のコンポーザブル エンジン+ Compression Studios: LLMLingua-2、2 層 Ultra、オムニグリフ、ステップごとの忠実度ゲート、 GCF v3.2、ドラッグ リオーダー エディター。 →[圧縮](docs/compression/COMPRESSION_ENGINES.md)
- **🕵️透過的なMITM復号化 (TPROXY)** — 、SNI ごとのCA + trust-store インストーラーを使用して、プロキシ環境変数を無視するCLIsキャプチャします。 → [MITM/TPROXY](docs/security/MITM-TPROXY-DECRYPT.md)
- **💸どこでもコストテレメトリ**すべてのエンドポイントの— `X-OmniRoute-*` cost/usageヘッダー、キャッシュ HIT 節約ヘッダー、キーごとのUSD消費クォータ。 → [APIリファレンス](docs/reference/API_REFERENCE.md)
- **🧠あなたがコントロールするメモリ**—はデフォルトでオフ、オプトイン int8 ベクトル量子化+型付き減衰、リクエストごとの`x-omniroute-no-memory`。 →[メモリ](docs/frameworks/MEMORY.md)
- **🛡️セキュリティ**すべてのLLMルートの—プロンプト インジェクション ガード (レッド チーム スイート)、オプトイン資格情報マスキング ガードレール (漏洩したAPI keys/secrets両方向で編集)、無料のDuckDuckGo最後の手段 Web 検索、およびダッシュボードのオプションのOIDCログイン ゲート (パスワード ログインは常に利用可能)。 →[ガードレール](docs/security/GUARDRAILS.md)
- **🖼️新しいエンドポイント**— `/v1/ocr` (Mistral OCR) および`/v1/audio/translations` (Whisper スタイル) はメディアの表面を丸めます。 → [APIリファレンス](docs/reference/API_REFERENCE.md)
- **🎨画像/ビデオ/オーディオ生成**メディア用の— one API : xAI Grok Imagine & Novita AIビデオ、 ComfyUI、Magnific、Adobe Firefly、Segmind、およびElevenLabsなどの音声プロバイダー。 → [APIリファレンス](docs/reference/API_REFERENCE.md)
- **🌍導入と運用**—リバースプロキシ`basePath`、ブラウザ言語自動検出、キーごとのデバイス追跡、ルートレスMITMトラスト、zh-TW ローカリゼーション。 →[環境](docs/reference/ENVIRONMENT.md)
- **🤝その他のプロバイダーとエージェント**—クラウド エージェント (Codexクラウド、 Cursor、 Devin、 Jules)、ブラウザー付きGrokビルド (xAI) + OAuthログイン、 Ollamaファーストクラス カード、 Claude Opus 5 & Sonnet 5、 Kimiオフィシャル パートナーシップ (Code/Web/Moonshot)、 Zed、Requesty、 SenseNova、Yuanbao、Agnes AI…そしてリフレッシュ**394プロバイダーカタログ**。 →[プロバイダー](docs/reference/PROVIDER_REFERENCE.md)
- **📡ルーティングの透明性**—すべての応答には、応答を提供したstrategy/provider/latencyを指定する`X-OmniRoute-Decision`ヘッダー、新しい`cache-optimized`コンボ戦略+自動コンボ`cacheAffinity`因子ルートの繰り返し要求がキャッシュされたプレフィックスを保持する接続に戻され、読み取り専用の`/v1/auto-combo/{channel}/candidates`エンドポイントが`auto/*`チャネルのライブ候補プールを公開します。 →[オートコンボ](docs/routing/AUTO-COMBO.md)
- **⚡ローカルパフォーマンスとインフラ**—ワンクリック ローカルRedis、 Cloudflare Workers / Deno リレー デプロイヤ、Bifrost および Mux を監視付き組み込みサービスとして展開します。 →[組み込みサービス](docs/frameworks/EMBEDDED-SERVICES.md)
- **🧩箱にも入っています**—プラグイン フレームワーク+マーケットプレイス、 Omni/Agent/GitHubスキル フレームワーク、 Obsidian vault 統合 (22 のMCPツール)、OpenAI 互換のバッチおよびファイルAPIs、セマンティック応答キャッシュ、リーダーボードによるゲーミフィケーション、 ACPエージェント検出 (15 の組み込みエージェント)、 BigQueryへのスケジュールされたログ エクスポート、 `auto/chaos`並列マルチモデル ファンアウト、 Telegramボット ブリッジ、アプリ内バージョン マネージャーと LMArena-ELO 無料プロバイダー ランキング。 →[ドキュメント](docs/README.md)

<br/>

<div align="center">

## 🤖 対応CLI & コーディングエージェント

> 1つの設定 — `http://localhost:20128/v1` — で、**すべて**のAI IDEやCLIが無料・低コストのモデルで動作します。

<div align="center">
<table>
  <tr>
    <td align="center" width="76"><a href="https://github.com/anthropics/claude-code"><img src="./public/providers/claude.svg" width="40" alt="Claude Code"/><br/><sub><b>Claude Code</b></sub><br/><sub>                           </sub></a></td>
    <td align="center" width="76"><a href="https://github.com/openai/codex"><img src="./public/providers/codex.svg" width="40" alt="Codex CLI"/><br/><sub><b>Codex CLI</b></sub><br/><sub>                           </sub></a></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme:dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@1.91.0/dark/cline.png"/><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/cline.svg" width="40" alt="Cline"/></picture><br/><sub><b>Cline</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><a href="https://github.com/Kilo-Org/kilocode"><img src="./public/providers/cli-generic.svg" width="40" alt="Kilo Code"/><br/><sub><b>Kilo Code</b></sub><br/><sub>                           </sub></a></td>
    <td align="center" width="76"><a href="https://github.com/Zoo-Code-Org/Zoo-Code"><img src="./public/providers/cli-generic.svg" width="40" alt="Zoo Code"/><br/><sub><b>Zoo Code</b></sub><br/><sub>                           </sub></a></td>
    <td align="center" width="76"><img src="./public/providers/continue.svg" width="40" alt="Continue"/><br/><sub><b>Continue</b></sub><br/><sub>                           </sub></td>
  </tr>
  <tr>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="Aider"/><br/><sub><b>Aider</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="ForgeCode"/><br/><sub><b>ForgeCode</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="jcode"/><br/><sub><b>jcode</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/deepseek.svg" width="40" alt="DeepSeek TUI"/><br/><sub><b>DeepSeek TUI</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="CodeWhale"/><br/><sub><b>CodeWhale</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><a href="https://github.com/anomalyco/opencode"><img src="./public/providers/cli-generic.svg" width="40" alt="OpenCode"/><br/><sub><b>OpenCode</b></sub><br/><sub>                           </sub></a></td>
  </tr>
  <tr>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="Factory Droid"/><br/><sub><b>Factory Droid</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/copilot.svg" width="40" alt="GitHub Copilot CLI"/><br/><sub><b>Copilot CLI</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cursor.svg" width="40" alt="Cursor CLI"/><br/><sub><b>Cursor CLI</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="Smelt"/><br/><sub><b>Smelt</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="Pi (pi-coding-agent)"/><br/><sub><b>Pi</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/grok.svg" width="40" alt="Grok Build (xAI)"/><br/><sub><b>Grok Build</b></sub><br/><sub>                           </sub></td>
  </tr>
  <tr>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme:dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@1.91.0/dark/nousresearch.png"/><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/nousresearch.svg" width="40" alt="Hermes Agent (Nous Research)"/></picture><br/><sub><b>Hermes Agent</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/openclaw.svg" width="40" alt="OpenClaw"/><br/><sub><b>OpenClaw</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme:dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@1.91.0/dark/goose.png"/><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/goose.svg" width="40" alt="Goose"/></picture><br/><sub><b>Goose</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="Open Interpreter"/><br/><sub><b>Open Interpreter</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><img src="./public/providers/cli-generic.svg" width="40" alt="Warp AI"/><br/><sub><b>Warp AI</b></sub><br/><sub>                           </sub></td>
    <td align="center" width="76"><a href="https://deyin.ai"><img src="./public/deyin.svg" width="40" alt="deyin.ai"/><br/><sub><b>deyin.ai</b></sub><br/><sub>                           </sub></a></td>
  </tr>
</table>
</div>

<div align="center">
<b>＋ 他にも対応</b> · Agent Deck · Kiro · Command Code · Antigravity · Windsurf · AMP · <b>あらゆるOpenAI互換ツール</b>
</div>

<sub>📖 すべての39ツール（CLI Code 28種 + CLI Agent 11種）のツールごとのセットアップ → [`docs/reference/CLI-TOOLS.md`](docs/reference/CLI-TOOLS.md) · 🧩 OpenCodeプラグイン → [`@omniroute/opencode-provider`](https://www.npmjs.com/package/@omniroute/opencode-provider)</sub>

</div>

<br/>

**OmniRouteを使って、サポートされている任意のCLIを1コマンドで起動** — 設定ファイル不要、
認証情報はプロセスごとに注入、Qwen/Geminiには使い捨ての分離されたホームを割り当て:

```bash
omniroute run claude   --model openai/gpt-5.4          # Claude Code
omniroute run codex    --model glm/glm-5.2             # OpenAI Codex CLI
omniroute run aider    --model glm/glm-5.2 -- --message "reply OK"
omniroute run goose    --model glm/glm-5.2
omniroute run opencode --model glm/glm-5.2 -- run "reply OK"
omniroute run qwen     --model glm/glm-5.2 -- -p "reply OK"
omniroute run gemini   --model glm/glm-5.2 -- --skip-trust -p "reply OK"

# または、プロバイダーとモデルを対話的に選択し、ツール独自の設定を書き込む:
omniroute configure codex          # 他にも: claude opencode qwen aider goose gemini cline continue kilo 5dive
```

すべてのコマンドはアクティブなリモートコンテキスト（`omniroute connect <host>`）を尊重し、`--dry-run`で
実行せずに正確な環境変数や引数をプレビュー、`--api-key-env NAME`で
シェル履歴に秘密情報を残しません。→ [CLI統合](docs/guides/CLI-INTEGRATIONS.md)

<br/>

<div align="center">

## 🌐 394 の AI プロバイダー — カタログで無料表示された 153 件

</div>

> **394 件の登録済みプロバイダー**を、標準のチャット、メディア、検索、ローカル、クラウドエージェント、システムの各コレクションにまたがって収録しています。そのうち **153 件は `hasFree: true` の検出メタデータを持ちます**。チャットモデルレジストリには、**239 プロバイダー / 3,059 個の異なるプロバイダーとモデルの組み合わせ / 1,475 個の生モデル ID**が含まれます。別個に用意された無料予算カタログには、**モデル単位の行が 465 件**、**定期プールが 34 件**、**定期利用またはキー不要で永久無料のプロバイダーが 51 件**あります。これらは意図的に異なる分母を使用しています。定義とプール重複排除後の計算については、[プロバイダーリファレンス](docs/reference/PROVIDER_REFERENCE.md) および [無料ティア](docs/reference/FREE_TIERS.md) を参照してください。

<div align="center">

### 🏢 主要ラボをすべて — 1 つのエンドポイントから

<table>
  <tr>
    <td align="center" width="80"><picture><source media="(prefers-color-scheme:dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@1.91.0/dark/openai.png"/><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/openai.svg" width="40" alt="OpenAI"/></picture><br/><sub>OpenAI</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/claude-color.svg" width="40" alt="Anthropic"/><br/><sub>Anthropic</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/gemini-color.svg" width="40" alt="Gemini"/><br/><sub>Gemini</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><picture><source media="(prefers-color-scheme:dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@1.91.0/dark/grok.png"/><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/grok.svg" width="40" alt="xAI Grok"/></picture><br/><sub>xAI Grok</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/deepseek-color.svg" width="40" alt="DeepSeek"/><br/><sub>DeepSeek</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/mistral-color.svg" width="40" alt="Mistral"/><br/><sub>Mistral</sub><br/><sub>                           </sub></td>
  </tr>
  <tr>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/qwen-color.svg" width="40" alt="Qwen"/><br/><sub>Qwen</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/meta-color.svg" width="40" alt="Meta Llama"/><br/><sub>Meta Llama</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><picture><source media="(prefers-color-scheme:dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@1.91.0/dark/groq.png"/><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/groq.svg" width="40" alt="Groq"/></picture><br/><sub>Groq</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/nvidia-color.svg" width="40" alt="NVIDIA"/><br/><sub>NVIDIA</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/minimax-color.svg" width="40" alt="MiniMax"/><br/><sub>MiniMax</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/cohere-color.svg" width="40" alt="Cohere"/><br/><sub>Cohere</sub><br/><sub>                           </sub></td>
  </tr>
  <tr>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/perplexity-color.svg" width="40" alt="Perplexity"/><br/><sub>Perplexity</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/huggingface-color.svg" width="40" alt="Hugging Face"/><br/><sub>HuggingFace</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/together-color.svg" width="40" alt="Together"/><br/><sub>Together</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/fireworks-color.svg" width="40" alt="Fireworks"/><br/><sub>Fireworks</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/cloudflare-color.svg" width="40" alt="Cloudflare"/><br/><sub>Cloudflare</sub><br/><sub>                           </sub></td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/baidu-color.svg" width="40" alt="Baidu"/><br/><sub>Baidu</sub><br/><sub>                           </sub></td>
  </tr>
</table>

<sub>…さらに 350 件以上 — すべてのアイコンがダッシュボードのプロバイダーカタログからリアルタイムで解決されます。📖 [プロバイダーリファレンス](docs/reference/PROVIDER_REFERENCE.md)</sub>

<br/>

### 🆓 永久無料 — $0、カード不要

<table>
  <tr>
    <td align="center" width="150"><img src="./public/providers/cli-generic.svg" width="42" alt="OpenCode Zen"/><br/><b>OpenCode Zen</b><br/><sub>DeepSeek V4、Nemotron 3<br/>トークン上限なし</sub></td>
    <td align="center" width="150"><img src="./public/providers/cli-generic.svg" width="42" alt="Kilo Code"/><br/><b>Kilo Code</b><br/><sub>自動ルーター、Tencent Hy3<br/>永久無料</sub></td>
    <td align="center" width="150"><img src="./public/providers/requesty.svg" width="42" alt="Requesty"/><br/><b>Requesty</b><br/><sub>GPT-OSS 120B、Nemotron<br/>永久無料</sub></td>
    <td align="center" width="150"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/siliconcloud-color.svg" width="42" alt="SiliconFlow"/><br/><b>SiliconFlow</b><br/><sub>DeepSeek V3.2 / R1<br/>無料枠あり</sub></td>
    <td align="center" width="150"><img src="./public/providers/zhipu.svg" width="42" alt="Z.AI GLM"/><br/><b>Z.AI GLM</b><br/><sub>GLM-4.7 / 4.5-Flash<br/>永久無料</sub></td>
    <td align="center" width="150"><img src="./public/providers/baidu.svg" width="42" alt="Baidu ERNIE"/><br/><b>Baidu ERNIE</b><br/><sub>ERNIE 4.0<br/>永久無料</sub></td>
  </tr>
  <tr>
    <td align="center" width="150"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.91.0/icons/qoder-color.svg" width="42" alt="Qoder AI"/><br/><b>Qoder AI</b><br/><sub>Qwen3-Max、Kimi-K2<br/>無料で無制限</sub></td>
    <td align="center" width="150"><img src="./public/providers/pollinations.svg" width="42" alt="Pollinations"/><br/><b>Pollinations</b><br/><sub>GPT、Llama、Claude<br/>キー不要</sub></td>
    <td align="center" width="150"><img src="./public/providers/cloudflare.svg" width="42" alt="Cloudflare AI"/><br/><b>Cloudflare AI</b><br/><sub>50以上のモデル<br/>1日10Kニューロン</sub></td>
    <td align="center" width="150"><img src="./public/providers/nvidia.svg" width="42" alt="NVIDIA NIM"/><br/><b>NVIDIA NIM</b><br/><sub>GLM、MiniMax<br/>無料で約40 RPM</sub></td>
    <td align="center" width="150"><img src="./public/providers/cerebras.svg" width="42" alt="Cerebras"/><br/><b>Cerebras</b><br/><sub>GLM 4.7、GPT-OSS<br/>一度限りの$5クレジット、カード必須</sub></td>
    <td align="center" width="150"><img src="./public/providers/openrouter.svg" width="42" alt="OpenRouter"/><br/><b>OpenRouter</b><br/><sub>:freeモデル<br/>+$10 → より高いRPM</sub></td>
  </tr>
</table>

📖 完全な機械可読カタログ → [`docs/reference/PROVIDER_REFERENCE.md`](docs/reference/PROVIDER_REFERENCE.md)

<br/>
</div>

<div align="center">

## 🖥️ OmniRouteどこでも—を実行する場所

</div>

> 同じアプリ、同じマシン、あなたのルール。グローバル npm インストールから**あなたの電話**Termux経由。

<table>
  <tr><th align="left">プラットフォーム</th><th align="left">インストール</th><th align="left">ハイライト</th></tr>
  <tr><td align="left" nowrap>📦 <b>npm (グローバル)</b></td><td align="left" nowrap><code>npm install -g omniroute</code></td><td align="left">1 つのコマンド、任意のOS</td></tr>
  <tr><td align="left" nowrap>⚡ <b>Bun (グローバル)</b></td><td align="left" nowrap><code>bun add -g omniroute</code></td><td align="left">同じレジストリ tarball、より高速なインストール</td></tr>
  <tr><td align="left" nowrap>🐳 <b>Docker</b></td><td align="left" nowrap><code>docker run … cheaperinference/omniroute</code></td><td align="left">マルチアーチ <b>AMD64 + ARM64</b></td></tr>
  <tr><td align="left" nowrap>🖥️ <b>デスクトップ (Electron)</b></td><td align="left" nowrap><code>npm run electron:build</code></td><td align="left">ネイティブ ウィンドウ+システム トレイ— <b>Windows / macOS / Linux</b></td></tr>
  <tr><td align="left" nowrap>🎩 <b>メニューバー (OmniRouteTray)</b></td><td align="left" nowrap><code>brew install --cask zoispag/tap/omniroute-tray</code></td><td align="left">&amp;サーバー—の自動更新を監視します。 <b>macOS</b></td></tr>
  <tr><td align="left" nowrap>💪 <b>ARM</b></td><td align="left" nowrap>ネイティブ<code>arm64</code></td><td align="left">Raspberry Pi、 ARMサーバー、Appleシリコン</td></tr>
  <tr><td align="left" nowrap>📱 <b>アンドロイド (Termux)</b></td><td align="left" nowrap><code>pkg install nodejs && npx -y omniroute</code></td><td align="left">走る <b>あなたの電話で</b>、 24/7、ルートなし</td></tr>
  <tr><td align="left" nowrap>📲 <b>PWA</b></td><td align="left" nowrap>「ホーム画面に追加」</td><td align="left">フルスクリーン、オフライン、ブラウザからインストール可能</td></tr>
  <tr><td align="left" nowrap>🧩 <b>OpenCodeプラグイン</b></td><td align="left" nowrap><code>@omniroute/opencode-provider</code></td><td align="left">ネイティブOpenCode統合</td></tr>
  <tr><td align="left" nowrap>🤖 <b>VSコードCopilotチャット</b></td><td align="left" nowrap>インストール <b>OmniCopilot</b> 拡大</td><td align="left">ネイティブCopilotのすべてのOmniRouteモデル チャット ピッカー—安定版&amp; Insider</td></tr>
  <tr><td align="left" nowrap>🛠️ <b>ソースから</b></td><td align="left" nowrap><code>npm install && npm run dev</code></td><td align="left">ハックして貢献してください</td></tr>
</table>

<sub>📖 [Dockerガイド](docs/guides/DOCKER_GUIDE.md)·[デスクトップ](electron/README.md)·[メニュー バー トレイ](https://github.com/zoispag/omniroute-tray)· [Termux](docs/guides/TERMUX_GUIDE.md) · [PWA](docs/guides/PWA_GUIDE.md) · [OpenCode](docs/frameworks/OPENCODE.md)</sub>

<br/>

<div align="center">

### 🧩新しい: VSコードのネイティブCopilotチャット内のOmniRoute

</div>

> 新しいサイドバーや新しいチャットはありませんUI — OmniRouteが提供するすべてのモデルがすぐに表示されます**すでに使用しているCopilotチャット モデル ピッカー**。 VSコード 1.122 以降、プロバイダー モデルは、 GitHubサインインやCopilotサブスクリプション、 —エージェント モード、ツール呼び出し、ビジョンがなくても、無料で動作します。

をインストールします**[OmniCopilot](https://github.com/diegosouzapw/OmniCopilot)**拡張子を使用して、 OmniRouteサーバー (デフォルトは`localhost:20128`) を指定してから、 Copilot Chat → model picker →を開きます。**モデルを管理…** →**OmniRoute** 。

<table>
  <tr><th align="left">店</th><th align="left">リンク</th><th align="left">で動作します</th></tr>
  <tr><td align="left" nowrap>🧩 <b>VSコード マーケットプレイス</b></td><td align="left"><a href="https://marketplace.visualstudio.com/items?itemName=diegosouzapw.omnicopilot">→をインストールする</a></td><td align="left">VSコード—安定版&amp;インサイダー</td></tr>
  <tr><td align="left" nowrap>🔓 <b>VSXレジストリを開く</b></td><td align="left"><a href="https://open-vsx.org/extension/diegosouzapw/omnicopilot">→をインストールする</a></td><td align="left">Cursor、 Windsurf、 VSCodium、 Theia 、コードサーバー、 Gitpod 、 Antigravity、 Kiro…</td></tr>
</table>

エディター内から:**拡張機能**見る、検索する**「OmniRoute」** 、 クリック**インストール**—両方のストアで同じように機能します。ソース、問題、発行 Runbook は[diegosouzapw/OmniCopilot](https://github.com/diegosouzapw/OmniCopilot)にあります。

<sub>📖 [VSコードCopilotチャット ガイド](docs/guides/VSCODE-COPILOT.md)—セットアップ、ピッカーの表示内容、タブ内のダッシュボード、トラブルシューティング</sub>

<br/>

<div align="center">

### 🎩 New: OmniRouteTray —ゲートウェイ、メニュー バーに常駐

</div>

> `omniroute serve`常にオンになっているときが最も幸せです。** [OmniRouteTray](https://github.com/zoispag/omniroute-tray)**これをmacOSの設定して忘れるメニューバー アプリに変えます。サーバーを起動し、再起動後もサーバーを維持し、所定の位置に更新し、ワンクリックでライブ トークン バジェットを設定します—**ターミナルウィンドウを開いたままにしておく必要はなく、 `npm install -g omniroute`子守をする必要もありません。**

[Tauri v2](https://v2.tauri.app/) (丸め誤差のサイズの Rust コア) で構築されており、独自の署名付き Node 24 ランタイムが同梱され、アプリ所有のOmniRouteインストールを管理するため、グローバル`node`/`bun`と競合することはありません。それ**既存の`~/.omniroute/`構成とデータベースを共有します**—つまり、すでに実行しているのと同じOmniRouteですが、帽子をかぶっているだけです。 🎩

<table>
  <tr><th align="left">何をするのか</th><th align="left">どうやって</th></tr>
  <tr><td align="left" nowrap>🟢 <b>サーバーを監視します</b></td><td align="left"><code>omniroute serve</code>を生成し、既に実行中のインスタンスを複製する代わりに採用します。</td></tr>
  <tr><td align="left" nowrap>📊 <b>ライブでの使用状況が一目でわかる</b></td><td align="left">プロバイダー クォータ バー、リセット カウントダウン付きのClaude session/weekly制限、30 日間のコストの内訳</td></tr>
  <tr><td align="left" nowrap>🔄 <b>自動更新が導入されている</b></td><td align="left">段階的インストール、アトミックスワップ、失敗時のロールバック—は常に最新リリース</td></tr>
  <tr><td align="left" nowrap>🚀 <b>ログイン時に開始</b></td><td align="left">ログイン時にオプションで起動します。トレイのみ、ドックアイコンなし</td></tr>
  <tr><td align="left" nowrap>🩺 <b>ドクター&amp;ログ</b></td><td align="left">ワンクリック診断とサーバーログへのアクセス</td></tr>
</table>

```sh
brew install --cask zoispag/tap/omniroute-tray
```

<sub>ダウンロードをご希望ですか?最新の<code>.dmg</code>次から取得します。
<a href="https://github.com/zoispag/omniroute-tray/releases">リリース</a>。ソース、問題、ビルド
ドキュメントは<a href="https://github.com/zoispag/omniroute-tray">zoispag/omniroute-tray</a>にあります。
<br/>💛によるコミュニティ プロジェクト <a href="https://github.com/zoispag">@zoispag</a> —正式なOmniRouteリリースではありません。</sub>

<br/>

<div align="center">

## 🔒 プライベート＆ローカルファースト

</div>

<img src="./docs/diagrams/privacy-local.svg" width="100%" alt="プライベートかつローカルファースト — OmniRoute のゲートウェイとコントロールプレーンは、お使いのマシン上で動作します。プロンプトはリクエストごとに選択されたアップストリームプロバイダーへ送信されます。OmniRoute がホストするプロンプト処理の中継地点はなく、テレメトリはデフォルトで無効です。認証情報は保存時に AES-256-GCM で暗号化されます。セキュリティ制御には、API キーのスコープ設定、IP フィルタリング、レート制限、プロンプトインジェクション対策、アップストリームヘッダーの除去、オプトイン方式の PII 編集、サニタイズされたエラー、ローカル SQLite 監査証跡が含まれます。OmniRoute は MIT ライセンスで提供され、セルフホストできます。"/>

<sub>📖 [認可](docs/architecture/AUTHZ_GUIDE.md) · [ガードレール](docs/security/GUARDRAILS.md) · [コンプライアンス](docs/security/COMPLIANCE.md)</sub>

<br/>

<div align="center">

## 🔌 フル CLI + A2A & MCP

</div>

> サーバーにとどまらず、OmniRoute は **80 以上のコマンドを備えたフル機能のコマンドラインコックピット**であり、AI エージェントが **自律的に操作できる**オープンなエージェントプロトコルにも対応しています。

### ⌨️ `start` だけではない本格的な CLI

```bash
omniroute               # ゲートウェイ + ダッシュボードを起動（ポート 20128）
omniroute chat          # 対話型 TUI チャットクライアント（スラッシュコマンド: /model /combo /skill /memory）
omniroute setup         # 初回起動ガイドウィザード
omniroute doctor        # プロバイダー、ポート、ネイティブ依存関係を診断
```

### 🛰️ リモートモード — ここで CLI を実行し、VPS 上で OmniRoute を動かす

サーバー上で OmniRoute を実行していますか？**同じ CLI** を使ってノートパソコンから操作できます。一度スコープ付きアクセストークンでログインすれば、それ以降のすべてのコマンドがリモートを対象にします。

```bash
omniroute connect 192.168.0.15            # パスワード → スコープ付きトークンを発行し、コンテキストとして保存
omniroute models                         # ← リモートサーバーに対して実行
omniroute configure codex                 # ← リモートモデルを選択し、ローカルの Codex プロファイルを書き込む
omniroute tokens create --name ci --scope read   # 他のマシン用に、より限定されたトークンを発行
omniroute contexts use default            # ← ローカルサーバーに戻す
```

トークンのスコープは `read` / `write` / `admin` で指定でき、プロセスを起動するルートはループバックのみに制限されます。
<sub>📖 [リモートモード](docs/guides/REMOTE-MODE.md)</sub>

<div align="left">

<img src="./docs/diagrams/cli-terminal.svg" width="50%" alt="OmniRoute CLI のアニメーションターミナルデモ — omniroute providers list、omniroute combo list、omniroute health が、providers · oauth · keys · combo · nodes · models · cache · compression · cost · usage · quota · health · resilience · telemetry · logs · audit · mcp · a2a · cloud · memory · skills · eval · tunnel · backup · sync · webhooks · policy · pricing · translator · simulate …で構成される 89 コマンドのトップレベルサーフェスを順番に表示"/>

</div>

### 🤝 エージェントを接続 — OmniRoute 自体を制御

**MCP**、**A2A**、**REST API**、**webhook**、または **リモート CLI** 経由で OmniRoute を公開すると、対応可能なエージェント（または独自のコード）が、ルーティング、プロバイダー、コンボ、キャッシュ、圧縮、メモリなど、ゲートウェイ全体を自律的に操作できるようになります。以下の HTTP エンドポイントは `http://localhost:20128` 配下で提供されます。

<table>
  <tr><th align="left">インターフェース</th><th align="left">エンドポイント / コマンド</th><th align="left">用途</th></tr>
  <tr><td align="left" nowrap>🧰 <b>MCP (stdio)</b></td><td align="left" nowrap><code>omniroute --mcp</code></td><td align="left">Claude Desktop、Cursor、その他の MCP クライアントに接続</td></tr>
  <tr><td align="left" nowrap>🌊 <b>MCP (HTTP)</b></td><td align="left" nowrap><code>/api/mcp/stream</code></td><td align="left">リモート MCP — <b>110 個のツール</b>、33 のスコープ（適用はオプトイン）、完全な監査証跡</td></tr>
  <tr><td align="left" nowrap>📡 <b>MCP (SSE)</b></td><td align="left" nowrap><code>/api/mcp/sse</code></td><td align="left">ストリーミング MCP トランスポート</td></tr>
  <tr><td align="left" nowrap>🤝 <b>A2A</b></td><td align="left" nowrap><code>/.well-known/agent.json</code></td><td align="left">エージェント間通信、<b>JSON-RPC 2.0</b> + SSE、6 つのスキル</td></tr>
  <tr><td align="left" nowrap>🌐 <b>REST API</b></td><td align="left" nowrap><code>/v1/*</code></td><td align="left">OpenAI 互換 — チャット、埋め込み、画像、音声、OCR</td></tr>
  <tr><td align="left" nowrap>🔔 <b>Webhooks</b></td><td align="left" nowrap><code>/api/webhooks</code></td><td align="left">リクエスト / クォータのイベントを Slack、Discord、Telegram、または任意の URL にプッシュ</td></tr>
  <tr><td align="left" nowrap>🛰️ <b>Remote CLI</b></td><td align="left" nowrap><code>omniroute connect <host></code></td><td align="left">スコープ付きアクセストークンでリモートインスタンスを操作</td></tr>
</table>

```bash
# Claude Code に MCP 経由で OmniRoute の完全なツールセットを提供:
omniroute mcp enable --transport streamable-http
claude mcp add --transport http omniroute http://localhost:20128/api/mcp/stream \
  --header "Authorization: Bearer <api-key-with-manage-scope>"
```

<sub>📖 [MCP サーバー](docs/frameworks/MCP-SERVER.md) · [A2A サーバー](docs/frameworks/A2A-SERVER.md) · [エージェントプロトコル](docs/frameworks/AGENT_PROTOCOLS_GUIDE.md)</sub>

<br/>

<div align="center">

## 🗜️ 15 ～ 95% のトークンを自動的に節約—

</div>

### 📖仕組み—パイプライン、アーキテクチャ、節約の計算

<img src="./docs/diagrams/compression-pipeline.svg" width="100%" alt="OmniRoute compression pipeline: an illustrative 10,000-token client request passes through 12 composable engines — Session-Dedup, CCR, Lite, RTK, Responses Tool Output, Headroom, Relevance, Caveman, Aggressive, LLMLingua-2, Ultra and OmniGlyph — and can reach the provider at about 1,080 tokens in the documented stacked example. Structured content is protected by preservation guards and per-step fidelity gates; explicit lossy or experimental modes may transform eligible content."/>

デフォルトのスタックコンボは`RTK → Caveman`を実行します。両方が同じtool/contextペイロードで動作する場合、節約はさらに増加します。

```txt
combined = 1 − (1 − RTK) × (1 − Caveman_input)
average  = 1 − (1 − 0.80) × (1 − 0.46) = 89.2%
range    = 78.4 – 94.6%
```

コード ブロック、 URLs、 JSONおよび構造化データは、**常に守られている**保存エンジンによって。

> **少数のトークンで効果があるのに、なぜ多くのトークンを使用するのでしょうか?**すべてのリクエストはOmniRouteの圧縮パイプラインを通過します**透明に**—クライアントは変更されません。それは今では**12 個のコンポーザブル エンジンのスタック**[RTK](https://github.com/rtk-ai/rtk) 、 [Caveman](https://github.com/JuliusBrussee/caveman) (⭐ 90K +)、 [LLMLingua-2](https://github.com/microsoft/LLMLingua) 、および[Troglodita](https://github.com/leninejunior/troglodita) (PT-BR) からのアイデアに基づいて構築された、ルーティング コンボ—ごとに順番に実行され、組み合わせて一致します。

### 🧱 12 エンジン スタック

エンジンはパイプライン順序で実行されます。それぞれは個別に切り替え可能で、コンボごとに構成可能です。

<table>
  <tr><th align="center">#</th><th align="left">エンジン</th><th align="left">何をするのか</th></tr>
  <tr><td align="center" nowrap>1</td><td align="left" nowrap><b>セッション重複除去</b></td><td align="left">ターンをまたいで繰り返されるコンテンツをドロップします (コンテンツアドレス、クロスターン)</td></tr>
  <tr><td align="center" nowrap>2</td><td align="left" nowrap><b>CCR</b></td><td align="left">取得マーカーの背後にある大きなブロックをアーカイブし、オンデマンドでフェッチします</td></tr>
  <tr><td align="center" nowrap>3</td><td align="left" nowrap><b>ライト</b></td><td align="left">ホワイトスペース+画像 URL トリミング (レイテンシーライト ベースライン)</td></tr>
  <tr><td align="center" nowrap>4</td><td align="left" nowrap><b>RTK</b></td><td align="left">スマートツールによる結果のフィルタリング、重複排除、切り捨て (コマンド対応)</td></tr>
  <tr><td align="center" nowrap>5</td><td align="left" nowrap><b>応答ツールの出力</b></td><td align="left">shell/patch/search/build出力のロスレスファーストJSON +有界診断圧縮 (応答API)</td></tr>
  <tr><td align="center" nowrap>6</td><td align="left" nowrap><b>ヘッドルーム</b></td><td align="left">ベンダーが提供するJSON配列のロスレス表形式圧縮 (~ 30%) <b>GCF</b> コーデック</td></tr>
  <tr><td align="center" nowrap>7</td><td align="left" nowrap><b>関連性</b></td><td align="left">最後のユーザークエリに対する抽出文スコアリング</td></tr>
  <tr><td align="center" nowrap>8</td><td align="left" nowrap><b>穴居人</b></td><td align="left">ルールベースの散文圧縮 (~出力で 65 ～ 75%)</td></tr>
  <tr><td align="center" nowrap>9</td><td align="left" nowrap><b>攻撃的</b></td><td align="left">要約+老人の進行性老化</td></tr>
  <tr><td align="center" nowrap>10</td><td align="left" nowrap><b>LLMLingua-2</b></td><td align="left">MobileBERT ONNX —コードセーフ、非同期によるMLセマンティック プルーニング</td></tr>
  <tr><td align="center" nowrap>11</td><td align="left" nowrap><b>ウルトラ</b></td><td align="left">オプションの小規模モデル (SLM) 層を使用したヒューリスティック トークン プルーニング</td></tr>
  <tr><td align="center" nowrap>12</td><td align="left" nowrap><b>OmniGlyph</b></td><td align="left">直接Anthropicワイヤ上で測定されたClaude Fable 5 の実験的な context-as-image エンコード。 GPT 5.6 トランスフォーマーは、フェールクローズされた保留中のプロバイダー受信のままになります。 4 つの圧縮プロファイル (アグレッシブなデフォルト、バランス型、コーディングセーフ、パススルー) (最もアグレッシブな、オプトイン)</td></tr>
</table>

コードブロック、 URLs 、構造化データは**常に保存されています**バイトパーフェクト。**ワンクリックのプリセット**エンジンを組み合わせる:

<table>
  <tr><th align="left">モード</th><th align="left">貯蓄</th><th align="left">こんな方に最適</th></tr>
  <tr><td align="left" nowrap>🪶 <b>ライト</b></td><td align="left" nowrap>~15%</td><td align="left">常時安全なデフォルト</td></tr>
  <tr><td align="left" nowrap>🪨 <b>スタンダード (穴居人)</b></td><td align="left" nowrap>~30%</td><td align="left">毎日のコーディング</td></tr>
  <tr><td align="left" nowrap>⚡ <b>攻撃的</b></td><td align="left" nowrap>~50%</td><td align="left">ツールを多用する長時間のセッション</td></tr>
  <tr><td align="left" nowrap>🔥 <b>ウルトラ</b></td><td align="left" nowrap>~75%</td><td align="left">最大限の節約</td></tr>
  <tr><td align="left" nowrap>🧰 <b>RTK</b></td><td align="left" nowrap>60–90%</td><td align="left">Shell/test/build/git出力</td></tr>
  <tr><td align="left" nowrap>🔗 <b>積み上げ (RTK →穴居人)</b></td><td align="left" nowrap><b>78–95%</b></td><td align="left">混合プロンプト+ツールのログ</td></tr>
</table>

**実際の例—標準モード:**

> **前 (69 トークン):** _「 Reactコンポーネントが再レンダリングされる理由は、レンダリング サイクルごとに新しいオブジェクト参照を作成しているためである可能性があります。インライン オブジェクトをプロップとして渡すと、 Reactの浅い比較では毎回異なるオブジェクトとして認識され、再レンダリングがトリガーされます。オブジェクトをメモ化するにはuseMemo使用することをお勧めします。」
>
> **後 (トークン 19 個):** _"新しいオブジェクト参照をそれぞれレンダリングします。インライン オブジェクト prop =新しい参照=を再レンダリングします。 useMemoでラップします。"_
>
> **同じ答えです。トークンが 72% 減少します。精度損失ゼロ。** ✅

**PT-BR の例— [Troglodita](https://github.com/leninejunior/troglodita)モード:**

> **アンティ (42 トークン):** _「問題はコンポーネントの再レンダリングであり、新しいオブジェクトの参照を送信するために、レンダリングされたレンダリング結果が表示されます。EU の推奨useMemo。」_
>
> **デポワ (12 トークン):** _「再レンダリング: ref nova cada ciclo (objeto inline recriado)。Usar `useMemo`.」_
>
> **メスマレスポスタ。 ~ 70% メノストークン。精密な技術をそのままに。** ✅

<br/>

### 🎚️エンジン—出力スタイルを超えて、アダプティブ ダイヤルとリクエストごとのコントロール

上記の 12 個のエンジンは、必要なものを縮小します。**で**。さらに3層の形状**どうやって**、**いつ**、そして何が来るのか**外**:

- **🪄出力スタイル**_(出力軸ステアリング)_ — 、決定的でキャッシュセーフな応答整形命令を挿入します。 `lite` / `full` / `ultra`強度でそれぞれ組み合わせることができます。スタイルの追加は、次の 1 行のレジストリ エントリです。
  - **簡潔な散文**—ドロップフィラー / 記事 / ヘッジ;技術的な内容を正確に保つこと。
  - **コードの削減**— "lazy Senior dev" YAGNI: 作業上の変更は最小限で、要求されていないスキャフォールディングはありません。
  - **ポニーテール (怠惰なシニア開発者)** — YAGNIはしごを登り、根本原因を修正し、最小の動作差分を修正します。
  - **ADHD (アクションファースト) を持っています**—次のアクションは、ステップ番号が付けられ、具体的な次のステップが 1 つあり、前文はありません。
  - **Terse CJK (文言)** —古典中国語の超簡潔スタイル ( `zh`にロケールゲートされる)。
- **🎯適応型コンテキストバジェット**_(ダイヤル)_ 1 つのon/offトークンしきい値の代わりに—使用し、最も安価で最も損失の少ないエンジンを必要な範囲にのみエスカレーションします。**モデルのコンテキストウィンドウに合わせる**。ポリシー: `reserve-output` (デフォルト、モデル対応) · `percentage` · `absolute`。モード: `floor` (適合性の保証) · `replace-autotrigger` (明示的な選択が優先) · `off` (レガシーしきい値)。
- **🎛️圧縮が決定される場所**_(優先順位、高→低)_ —リクエストごとの`x-omniroute-compression`ヘッダー › ルーティング コンボ オーバーライド › アクティブな名前付きプロファイル › アダプティブ / 自動トリガー › パネルのデフォルト › オフ。適用されたプランは、 `X-OmniRoute-Compression: <mode>; source=<source>`応答ヘッダーにエコーバックされます。

トークンしきい値による自動トリガー、アダプティブ ダイヤルのオン、名前付きプロファイルの固定、リクエストごとに 1 回限りの設定、またはルーティング コンボ—ごとのパイプラインの割り当てなど、ワークロードに適したものを選択できます。オフラインでのオプトイン**評価ハーネス**(`npm run eval:compression`) は、変更をプロモートする前に、固定されたコーパスの忠実度と節約をスコア付けします。

📖 [`COMPRESSION_GUIDE.md`](docs/compression/COMPRESSION_GUIDE.md) · [`RTK_COMPRESSION.md`](docs/compression/RTK_COMPRESSION.md) · [`COMPRESSION_ENGINES.md`](docs/compression/COMPRESSION_ENGINES.md)

<br/>

<div align="center">

# ⚡クイックスタート

</div>

**1) インストールして実行する**

```bash
npm install -g omniroute
omniroute
```

> 💡 `npm warn ERESOLVE`またはpeer-dep の警告が表示されますか?[それらは無害です](docs/guides/TROUBLESHOOTING.md#npm-install-warnings-eresolve--peer--deprecated)。** npm 11 以降を使用していますか?** npm は、許可されていない限り、パッケージ ライフサイクル スクリプトをブロックする場合があります。 OmniRouteの`postinstall` (`node scripts/build/postinstall.mjs`) は、ネイティブ ランタイム ファイルを準備するために必要です。グローバルにインストールするときに、npm の警告で指定されたパッケージを許可します。 OmniRoute 3.8.55 によって報告されるパッケージ セットの場合:
>
> `bash npm install -g --allow-scripts=omniroute,keytar,onnxruntime-node,@parcel/watcher,@swc/core,protobufjs,esbuild omniroute `
>
> 今後のグローバル インストールでこの許可リストを再利用するには、一度設定してから通常どおりインストールします。
>
> `bash npm config set allow-scripts=omniroute,keytar,onnxruntime-node,@parcel/watcher,@swc/core,protobufjs,esbuild --location=user npm install -g omniroute `
>
> 依存関係リストはリリース間で変更される可能性があります。 npm が別のリストを報告する場合は、その警告にあるパッケージ名を使用してください。パッケージを許可すると、そのインストール スクリプトの実行が許可されます。** Gemini Web または別の Web Cookie プロバイダーを使用していますか?** npm パッケージにはPlaywrightが含まれていますが、その Chromium バイナリは含まれていません。最初の Web プロバイダー要求を行う前に、 [Playwright Chromium セットアップ](docs/guides/TROUBLESHOOTING.md#gemini-web-and-playwright-chromium)ノートを参照してください。

`http://localhost:20128`のダッシュボード · APIの`http://localhost:20128/v1`。

**2) 自分のアカウントを使用して対象となるプロバイダーに接続します**

ダッシュボード→**プロバイダー**→ 、現在の契約条件とクォータがユースケースに適合するプロバイダーを選択します→ APIキーを追加するか、アカウント フローを完了します。無料利用枠では、サインアップ、承認、または支払い方法が必要な場合があります。[無料利用枠ガイド](docs/getting-started/FREE-TIERS-GUIDE.md)を確認してください。キーレスの可用性は保証されておらず、 `tos: avoid`とマークされたプロバイダーはデフォルトで`auto`から除外されます。

**3) コーディングツールを指定する**

```txt
Base URL: http://localhost:20128/v1
API Key:  [copy from Dashboard → Endpoints]
Model:    auto            (routes among eligible connections — or choose provider/model)
```

**4) 動作していることを確認する**

```bash
curl http://localhost:20128/v1/models -H "Authorization: Bearer YOUR_KEY"
```

接続されているモデルがリストに表示されるはずです。 🎉以上です—コーディングを開始すると、 OmniRoute自動ルーティングとフォールバックを行います。

クライアントがカスタム ヘッダーを送信できない場合、 OmniRouteトークン化された互換性エイリアスも公開します。

```txt
OpenAI catalog:   http://localhost:20128/vscode/YOUR_KEY/
OpenAI models:    http://localhost:20128/vscode/YOUR_KEY/models
OpenAI chat:      http://localhost:20128/vscode/YOUR_KEY/chat/completions
OpenAI responses: http://localhost:20128/vscode/YOUR_KEY/responses
Ollama chat:      http://localhost:20128/vscode/YOUR_KEY/api/chat
Ollama tags:      http://localhost:20128/vscode/YOUR_KEY/api/tags
```

これらは、 `Authorization: Bearer ...`接続できないクライアントにのみ使用してください。ヘッダー認証は引き続き優先モードです。

<br/>

## 📦その他のインストール方法— Docker、source、pnpm、Arch

**🐳 Docker**

```bash
docker run -d --name omniroute --restart unless-stopped --stop-timeout 40 \
  -p 127.0.0.1:20128:20128 -v omniroute-data:/app/data cheaperinference/omniroute:latest
```

`:latest`最高のものに続きます**出版された**安定したSemVer。 git `main`は追跡しません。 `:X.Y.Z` GitOpsにピン留めします。 [Dockerリリース チャネル」](docs/guides/DOCKER_GUIDE.md#release-channels)を参照してください。イメージ ピン**`OMNIROUTE_MEMORY_MB=1024`** 。ダッシュボードと軽いチャットにはこれで十分です。**コーディングエージェント**( Claudeコードの`POST /v1/responses` 、 Codex、 Grok、…) は、はるかに大きな V8 ヒープ、または 2 つのオーバーラップする長いコンテキストの下で~ 12 GiBで`FATAL ERROR`を処理する必要があります。コンテナーのサイズをヒープより上に設定します (ネイティブ バッファーは V8 の外側にあります)。

| ワークロード                    | ヒープ (`-e OMNIROUTE_MEMORY_MB`) | コンテナ (`--memory`) |
| ------------------------------- | --------------------------------- | --------------------- |
| ダッシュボード / ライトチャット | `1024` (画像のデフォルト)         | ≥                     |
| 1 つのコーディング エージェント | `8192`                            | ≥ 10g                 |
| 2 つの同時ロング`/v1/responses` | `10240`–`12288`                   | ≥ 12–16 g             |

```bash
docker run -d --name omniroute --restart unless-stopped --stop-timeout 40 \
  -e OMNIROUTE_MEMORY_MB=8192 --memory=10g \
  -p 127.0.0.1:20128:20128 -v omniroute-data:/app/data cheaperinference/omniroute:latest
```

完全な表: [Dockerガイド—ランタイムRAM](docs/guides/DOCKER_GUIDE.md#runtime-ram-for-coding-agents) 。

> **プレリリースDockerチャネル:** `diegosouzapw/omniroute:next`と`diegosouzapw/omniroute:next-web`現在のデフォルトの`release/v*`ブランチに従います。これらの変更可能なタグは、未リリースの修正をテストすることのみを目的としており、**実稼働環境ではサポートされていません**。 [Dockerリリース チャネル」](docs/guides/DOCKER_GUIDE.md#release-channels)を参照してください。

**🥟 Bun**

標準の`bun install`およびグローバル インストール (`bun install -g omniroute`) は、 Bunランタイム検出によってサポートされます。

- **内蔵`bun:sqlite`** : OmniRoute 、 Bunで実行する場合、 Bunの組み込み`bun:sqlite`ドライバーを使用し、 Node.jsまたは`sql.js`上の`better-sqlite3`にフォールバックします。
- **開発環境での Webpack バンドラーの自動選択**: 開発 (`bun run dev`) は、ネイティブ V8 バインディングの非互換性を防ぐために、 Bun自動的に検出し、Webpack を優先してTurbopackを無効にします。実稼働ビルド (`bun run build`) は、ノード上とまったく同じように`OMNIROUTE_USE_TURBOPACK`に従います。デフォルトではTurbopack 、Webpack でビルドする`OMNIROUTE_USE_TURBOPACK=0` (`Dockerfile.bun`それを`--build-arg`として公開します)。
- **専用のBun Dockerfile** : ネイティブBun実稼働デプロイメント用のマルチステージ`Dockerfile.bun` (`docker build -f Dockerfile.bun -t omniroute:bun .`)。

```bash
# Install and run with Bun
bun install
bun run dev
```

**🛠️ソースより**

```bash
cp .env.example .env && npm install
PORT=20128 npm run dev
```

**📦 pnpm**

```bash
pnpm add -g omniroute@latest --allow-build=better-sqlite3 --allow-build=@swc/core && omniroute
```

**🐧アーチLinux (AUR)**

```bash
yay -S omniroute-bin && systemctl --user enable --now omniroute.service
```

**🔧ニクス (フレーク)**

```bash
# Using Nix flakes
nix develop
npm run dev

# Or using devbox
devbox run npm run dev
```

📖 [Dockerガイド](docs/guides/DOCKER_GUIDE.md)— Compose プロファイル、Caddy HTTPS、 Cloudflareトンネル。

**🦭ポッドマン**

```bash
# 1. Prepare the bind-mounted data directory
mkdir -p data

# 2. Linux + local rootless Podman only (never a remote Podman Machine client):
podman unshare chown 1000:1000 ./data

# 3. Set the runtime hint, build the local Compose image, and start
echo "CONTAINER_HOST=podman" >> .env
podman compose --profile base up -d --build
```

On macOS or Windows, Podman uses a remote Podman Machine: skip `podman unshare` and follow the [topology-specific data directory guidance](contrib/podman/README.md#data-directory-permissions-by-topology).

📖 [Podman ガイド](contrib/podman/README.md)— Compose ビルド、Podman マシン、およびLinux/systemd Quadlet セットアップ。

**⚡より高速で無駄のないインストール (ネイティブ ビルドをスキップ)**

ネイティブSQLiteエンジン (`better-sqlite3`) は、**オプション**依存関係があるため、グローバル インストールではソースからのコンパイルがブロックされることはありません。 platform/Nodeに一致する場合は事前にビルドされたバイナリが使用され、それ以外の場合は透過的に純粋な JS エンジン (ノード 22 の`node:sqlite` +、そうでない場合はバンドルされている`sql.js` WASM) —にフォールバックされます。ビルド ツールは必要ありません。

ポストインストールをスキップするには**ネイティブのウォーミングアップ**完全に (CI、ヘッドレス、または遅いマシン)。注: これは、ネイティブSQLiteウォームアップ ステップ (`scripts/postinstall.mjs`) のみをスキップします。 binary-copy/repairフック (`scripts/build/postinstall.mjs`) は引き続き正常に実行されます。

```bash
OMNIROUTE_SKIP_POSTINSTALL=1 npm install -g omniroute   # CI=1 also skips it
```

最速のインストールを行うには、** pnpm** (コンテンツ アドレス ストア+ハード リンク—は上記を参照)。ダッシュボード不要のヘッドレス ランタイムの場合は、 Docker `base`プロファイル (上記) または[Termux ガイド](docs/guides/TERMUX_GUIDE.md)を使用します。 CLIと Web ダッシュボードは 1 つのポート上の同じプロセスによって提供されるため、現在、個別の CLI のみのパッケージはありません。

<br/>

<div align="center">

# アクション中の🎬 OmniRoute

</div>

## 📹 動画ガイド

<div align="center">

<sub>2026-10-18 時点のダッシュボードのスナップショット · 未加工カタログ: YT 1.352 | TT 334 | IG 290 · 鮮度（日数）: YT 5 | TT 48 | IG 49</sub>

<table>
  <tr>
    <td align="center" width="320">
      <a href="https://www.instagram.com/reel/Da8ZthUPK98/">
        <img src="https://placehold.co/320x180/111827/FFFFFF?text=Instagram+Reel+%7C+nick_saraev&font=montserrat&bold=true" alt="Instagram Reel — nick_saraev" width="300"/>
      </a><br/>
      <b>🎬 #1 — Instagram</b><br/>
      <sub>nick_saraev — 3,042,474 回視聴</sub>
    </td>
    <td align="center" width="320">
      <a href="https://www.instagram.com/reel/Dbp7wv_CIO0/">
        <img src="https://placehold.co/320x180/111827/FFFFFF?text=Instagram+Reel+%7C+nnapier7&font=montserrat&bold=true" alt="Instagram Reel — nnapier7" width="300"/>
      </a><br/>
      <b>🎬 #2 — Instagram</b><br/>
      <sub>nnapier7 — 1,454,535 回視聴</sub>
    </td>
    <td align="center" width="320">
      <a href="https://www.youtube.com/watch?v=NJ0TQ-pyMDY">
        <img src="https://img.youtube.com/vi/NJ0TQ-pyMDY/maxresdefault.jpg" alt="YouTube — Amidia AI & Tech" width="300"/>
      </a><br/>
      <b>🎬 #3 — YouTube</b><br/>
      <sub>Amidia AI & Tech — 794,974 回視聴</sub>
    </td>
    <td align="center" width="320">
      <a href="https://www.instagram.com/reel/DaSs65mMrHk/">
        <img src="https://placehold.co/320x180/111827/FFFFFF?text=Instagram+Reel+%7C+theopenstack&font=montserrat&bold=true" alt="Instagram Reel — theopenstack" width="300"/>
      </a><br/>
      <b>🎬 #4 — Instagram</b><br/>
      <sub>theopenstack — 692,419 回視聴</sub>
    </td>
    <td align="center" width="320">
      <a href="https://www.tiktok.com/@migue.baena/video/7670919268216622358">
        <img src="https://placehold.co/320x180/111827/FFFFFF?text=TikTok+%7C+migue.baena&font=montserrat&bold=true" alt="TikTok — migue.baena" width="300"/>
      </a><br/>
      <b>🎬 #5 — TikTok</b><br/>
      <sub>migue.baena — 685,788 回視聴</sub>
    </td>
  </tr>
</table>

</div>

**総合ランキング（重複を除外した正規 URL、`v > 0`、リーチの多い順）:**

| #1                                                                                     | #2                                                                                  | #3                                                                                      | #4                                                                                    | #5                                                                                                  |
| -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| [nick_saraev — Instagram](https://www.instagram.com/reel/Da8ZthUPK98/) — **3,042,474** | [nnapier7 — Instagram](https://www.instagram.com/reel/Dbp7wv_CIO0/) — **1,454,535** | [Amidia AI & Tech — YouTube](https://www.youtube.com/watch?v=NJ0TQ-pyMDY) — **794,974** | [theopenstack — Instagram](https://www.instagram.com/reel/DaSs65mMrHk/) — **692,419** | [migue.baena — TikTok](https://www.tiktok.com/@migue.baena/video/7670919268216622358) — **685,788** |

| #6                                                                                                      | #7                                                                                                  | #8                                                                                     | #9                                                                                        | #10                                                                                 |
| ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [milesreevesai — TikTok](https://www.tiktok.com/@milesreevesai/video/7667980059189366019) — **620,400** | [nikothetech — TikTok](https://www.tiktok.com/@nikothetech/video/7671890769665477918) — **610,803** | [Vaibhav Sisinty — YouTube](https://www.youtube.com/watch?v=QucgvbO5gsM) — **509,281** | [buildwithai.club — Instagram](https://www.instagram.com/reel/DbIt9AjK7-U/) — **347,652** | [nivedan.ai — Instagram](https://www.instagram.com/reel/DbIrCksJiqq/) — **331,973** |

2026-10-18 時点の正規指標: **1.976 件のユニーク動画** · **20.220.289 回の既知の視聴数**（`v > 0`）· **ネットワーク別のチャンネル／プロフィール数 1.210 件**。未加工のダッシュボードには 1.976 行（YouTube 1.352 = 長尺動画 740 + Shorts 612 · TikTok 334 · Instagram 290）が含まれています。正規 URL による正規化後、重複は残っておらず、動画ごとに最大の視聴回数が保持されています。YouTube のデータ収集は 2026-10-13 以降停止しており（14/10～18/10 に API クォータを使い切ったため）、TikTok／Instagram は 2026-09-02 以降停止しています（収集クレジットがないため）。76 件の動画には、まだ視聴回数がありません。

> 🎬 **OmniRoute についての動画を作成しましたか？** リンクを添えて [issue](https://github.com/diegosouzapw/OmniRoute/issues/new) または [discussion](https://github.com/diegosouzapw/OmniRoute/discussions) を作成してください。こちらで紹介します。

<br/>

<div align="center">

# 📧 コミュニティとヘルプ

> すべてを一か所にまとめています — メンテナーをフォローしたり、コミュニティとチャットしたり、issue を作成したりできます。

| チャンネル                                     | 場所 / 方法                                                                                                                  |
| ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| 💼 **LinkedIn** — メンテナーをフォロー         | [linkedin.com/in/diegosouzapw](https://www.linkedin.com/in/diegosouzapw/)                                                    |
| 🐙 **GitHub** — リリース情報やヒントをフォロー | [@diegosouzapw](https://github.com/diegosouzapw)                                                                             |
| 💬 **Discord**                                 | [discord.gg/U47eFqAXCn](https://discord.gg/U47eFqAXCn)                                                                       |
| ✈️ **Telegram**                                | [t.me/omnirouteOficial](https://t.me/omnirouteOficial)                                                                       |
| 🟢 **WhatsApp — 🌍 グローバル**                | [グループに参加](https://chat.whatsapp.com/FvuCbrpZmQ6I85n2vW5QIC?s=cl&p=a&mlu=4)                                            |
| 🟢 **WhatsApp — 🇧🇷 ブラジル**                  | [グループに参加](https://chat.whatsapp.com/KWgatljAjmbELQory59Oti?s=cl&p=a&mlu=4)                                            |
| 🌍 **ウェブサイト**                            | [omniroute.online](https://omniroute.online)                                                                                 |
| 🌍 **🌍StHub OmniRoute コミュニティ（無料）**  | [StHubポータル](https://portal.sthub.com.br/communities/groups/st-hub/channels/Omniroute-World-8kRjmK)                       |
| 📦 **ソースコード**                            | [github.com/diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)                                               |
| 🐛 **バグを報告**                              | [Issueを作成](https://github.com/diegosouzapw/OmniRoute/issues) — `npm run system-info` の出力を添付してください             |
| 🤝 **コントリビュート**                        | [CONTRIBUTING.md](CONTRIBUTING.md) · [ブランチおよびリリースモデル](docs/ops/BRANCHING_MODEL.md) · `good first issue` を選択 |
| 💚 **プロジェクトを支援**                      | [支援方法 ↑](#-support-omniroute) · [GitHub Sponsors](https://github.com/sponsors/diegosouzapw)                              |

</div>

---

<br/>
<div align="center">

## 🛠️技術スタック

</div>

<table>
  <tr><th align="left">層</th><th align="left">テクノロジー</th></tr>
  <tr><td nowrap><b>ランタイム</b></td><td>Node.js 22.x / 24.x LTS — <code>&gt;=22.22.2 &lt;23 || &gt;=24.0.0 &lt;27</code></td></tr>
  <tr><td nowrap><b>言語</b></td><td>TypeScript 6.0 — <b>100% TypeScript</b> <code>src/</code>と<code>open-sse/</code> (v2.0 以降、コアには<code>any</code>ありません)</td></tr>
  <tr><td nowrap><b>フレームワーク</b></td><td>Next.js 16 + React 19 + Tailwind CSS 4</td></tr>
  <tr><td nowrap><b>データベース</b></td><td>better-sqlite3 (SQLite、 WALジャーナリング) + LowDB (JSONレガシー) — 147 ドメイン モジュール、240 移行</td></tr>
  <tr><td nowrap><b>メモリ</b></td><td>SQLite FTS5フルテキスト+ int8-quantizedベクトル埋め込み、型付き減衰</td></tr>
  <tr><td nowrap><b>スキーマ</b></td><td>Zod 4 — MCPツールI/O検証+ API契約</td></tr>
  <tr><td nowrap><b>プロトコル</b></td><td>MCP (stdio / HTTP / SSE) + A2A v0.3 (JSON-RPC 2.0 + SSE)</td></tr>
  <tr><td nowrap><b>ストリーミング</b></td><td>サーバー送信イベント (SSE) + WebSocketブリッジ (<code>/v1/ws</code>)</td></tr>
  <tr><td nowrap><b>圧縮</b></td><td>12 エンジン パイプライン— RTK、Caveman、 LLMLingua-2 (MobileBERT ONNX)、 GCF、 OmniGlyph</td></tr>
  <tr><td nowrap><b>認証&amp;セキュリティ</b></td><td>OAuth 2.0 (PKCE) + JWT + APIキー+ MCPスコープ認証 · AES-256-GCM atrest · DOMPurify</td></tr>
  <tr><td nowrap><b>ステルス</b></td><td>wreq-js — JA3 / JA4 TLS指紋偽装、3 レベル プロキシ</td></tr>
  <tr><td nowrap><b>回復力</b></td><td>サーキットブレーカー、エクスポネンシャルバックオフ、アンチサンダーリングハード、オートコンボ自己修復</td></tr>
  <tr><td nowrap><b>ロギング</b></td><td>pino —リクエストコンテキストを含む構造化されたJSONログ</td></tr>
  <tr><td nowrap><b>テスト</b></td><td>Node.jsテスト ランナー+ Vitest — <b>60,000 の+静的テスト宣言</b> 8,400 の+追跡テスト ファイル (ユニット、統合、 E2E、セキュリティ、エコシステム)</td></tr>
  <tr><td nowrap><b>プラットフォーム</b></td><td>デスクトップ (Electron) · Android (Termux) · PWA (任意のブラウザ)</td></tr>
  <tr><td nowrap><b>CI/CD</b></td><td>GitHubアクション— auto npm 公開+ Dockerリリース時のハブ</td></tr>
  <tr><td nowrap><b>リンク</b></td><td><a href="https://omniroute.online">Webサイト</a> · <a href="https://www.npmjs.com/package/omniroute">npm</a> · <a href="https://hub.docker.com/r/cheaperinference/omniroute">Dockerハブ</a></td></tr>
</table>

<div align="center">

<br/>

## 📖 ドキュメント

</div>

### 📘 はじめに

<table>
  <tr><th align="left">ドキュメント</th><th align="left">説明</th></tr>
  <tr><td nowrap><b><a href="docs/guides/USER_GUIDE.md">ユーザーガイド</a></b></td><td>プロバイダー、コンボ、CLI 統合、デプロイ</td></tr>
  <tr><td nowrap><b><a href="docs/guides/SETUP_GUIDE.md">セットアップガイド</a></b></td><td>完全なインストール方法、CLI ツール設定、プロトコルのセットアップ、タイムアウト調整</td></tr>
  <tr><td nowrap><b><a href="docs/reference/CLI-TOOLS.md">CLI ツールガイド</a></b></td><td>Claude Code、Codex、Cursor、Cline、OpenClaw、Kilo、Copilot のツールごとのセットアップ</td></tr>
  <tr><td nowrap><b><a href="docs/guides/REMOTE-MODE.md">リモートモード</a></b></td><td>スコープ付きアクセストークンを使用して、ノート PC の CLI からリモート OmniRoute（VPS）を操作</td></tr>
  <tr><td nowrap><b><a href="docs/guides/CLAUDE-CODE-CONFIGURATION.md">Claude Code 設定</a></b></td><td><code>launch</code> + モデルごとのプロファイルを使用して、Claude Code を OmniRoute（ローカル／リモート）に接続</td></tr>
  <tr><td nowrap><b><a href="README.md#-quick-start">クイックスタート</a></b></td><td>3 ステップでインストール → 接続 → 設定</td></tr>
</table>

### 🔧 運用とデプロイ

<table>
  <tr><th align="left">ドキュメント</th><th align="left">説明</th></tr>
  <tr><td nowrap><b><a href="docs/guides/DOCKER_GUIDE.md">Docker ガイド</a></b></td><td>Docker の実行、Compose プロファイル、Caddy HTTPS、トンネル、イメージタグ</td></tr>
  <tr><td nowrap><b><a href="contrib/podman/README.md">Podman ガイド</a></b></td><td>Quadlet の systemd 統合、podman-compose、SELinux</td></tr>
  <tr><td nowrap><b><a href="docs/ops/VM_DEPLOYMENT_GUIDE.md">VM デプロイ</a></b></td><td>完全ガイド：VM + nginx + Cloudflare のセットアップ</td></tr>
  <tr><td nowrap><b><a href="docs/ops/FLY_IO_DEPLOYMENT_GUIDE.md">Fly.io デプロイ</a></b></td><td>永続ストレージを使用して Fly.io にデプロイ</td></tr>
  <tr><td nowrap><b><a href="docs/guides/TERMUX_GUIDE.md">Termux ガイド</a></b></td><td>Termux 経由で Android 上で OmniRoute を実行</td></tr>
  <tr><td nowrap><b><a href="docs/guides/PWA_GUIDE.md">PWA ガイド</a></b></td><td>Progressive Web App のインストール、キャッシュ、アーキテクチャ</td></tr>
  <tr><td nowrap><b><a href="docs/guides/UNINSTALL.md">アンインストールガイド</a></b></td><td>すべてのインストール方法に対応した完全な削除</td></tr>
  <tr><td nowrap><b><a href="docs/reference/ENVIRONMENT.md">環境設定</a></b></td><td><code>.env</code> の変数と参照の完全ガイド</td></tr>
</table>

### 🧠 機能とアーキテクチャ

<table>
  <tr><th align="left">ドキュメント</th><th align="left">説明</th></tr>
  <tr><td nowrap><b><a href="docs/architecture/ARCHITECTURE.md">アーキテクチャ</a></b></td><td>システムアーキテクチャ、データフロー、内部構造</td></tr>
  <tr><td nowrap><b><a href="docs/compression/COMPRESSION_GUIDE.md">圧縮ガイド</a></b></td><td>7 つのオプションによるパイプライン：off / lite / standard / aggressive / ultra / RTK / stacked</td></tr>
  <tr><td nowrap><b><a href="docs/compression/RTK_COMPRESSION.md">RTK 圧縮</a></b></td><td>コマンド出力の圧縮、フィルター、信頼、検証、未加工出力の復元</td></tr>
  <tr><td nowrap><b><a href="docs/compression/COMPRESSION_ENGINES.md">圧縮エンジン</a></b></td><td>Caveman、RTK、積層パイプライン、ダッシュボード／API／MCP の各インターフェース</td></tr>
  <tr><td nowrap><b><a href="docs/compression/COMPRESSION_RULES_FORMAT.md">圧縮ルール形式</a></b></td><td>Caveman および RTK フィルター用の JSON ルールパックのスキーマ</td></tr>
  <tr><td nowrap><b><a href="docs/compression/COMPRESSION_LANGUAGE_PACKS.md">圧縮言語パック</a></b></td><td>言語検出と Caveman ルールパックの作成</td></tr>
  <tr><td nowrap><b><a href="docs/architecture/RESILIENCE_GUIDE.md">レジリエンスガイド</a></b></td><td>サーキットブレーカー、クールダウン、キュー、群集雪崩対策、TLS スプーフィング</td></tr>
  <tr><td nowrap><b><a href="docs/routing/AUTO-COMBO.md">自動コンボエンジン</a></b></td><td>16 要素のスコアリング、モードパック、自己修復</td></tr>
  <tr><td nowrap><b><a href="docs/ops/PROXY_GUIDE.md">プロキシガイド</a></b></td><td>3 レベルのプロキシシステム、1proxy マーケットプレイス、レジストリの CRUD</td></tr>
  <tr><td nowrap><b><a href="docs/reference/FREE_TIERS.md">無料ティア</a></b></td><td>統合ディレクトリ：文書化された継続利用可能なプール 34 件／カタログ化された無料ティア項目 465 件</td></tr>
  <tr><td nowrap><b><a href="docs/guides/FEATURES.md">機能ギャラリー</a></b></td><td>スクリーンショットで見るビジュアルダッシュボードツアー</td></tr>
  <tr><td nowrap><b><a href="docs/architecture/CODEBASE_DOCUMENTATION.md">コードベースドキュメント</a></b></td><td>初心者向けのコードベース解説</td></tr>
</table>

### 🤖 プロトコルと API

<table>
  <tr><th align="left">ドキュメント</th><th align="left">説明</th></tr>
  <tr><td nowrap><b><a href="docs/reference/API_REFERENCE.md">API リファレンス</a></b></td><td>すべてのエンドポイントと使用例</td></tr>
  <tr><td nowrap><b><a href="docs/openapi.yaml">OpenAPI 仕様</a></b></td><td>OpenAPI 3.0 仕様</td></tr>
  <tr><td nowrap><b><a href="open-sse/mcp-server/README.md">MCP サーバー</a></b></td><td>110 個の MCP ツール、IDE 設定、Python／TS／Go クライアント</td></tr>
  <tr><td nowrap><b><a href="docs/frameworks/MCP-SERVER.md">MCP サーバーガイド</a></b></td><td>MCP のインストール、トランスポート、ツールリファレンス</td></tr>
  <tr><td nowrap><b><a href="src/lib/a2a/README.md">A2A サーバー</a></b></td><td>JSON-RPC 2.0 プロトコル、スキル、ストリーミング、タスク管理</td></tr>
  <tr><td nowrap><b><a href="docs/frameworks/A2A-SERVER.md">A2A サーバーガイド</a></b></td><td>A2A エージェントカード、タスク、スキル、ストリーミング</td></tr>
</table>

### 📋 プロジェクトと品質

<table>
  <tr><th align="left">ドキュメント</th><th align="left">説明</th></tr>
  <tr><td nowrap><b><a href="CONTRIBUTING.md">コントリビューション</a></b></td><td>開発環境のセットアップとガイドライン</td></tr>
  <tr><td nowrap><b><a href="docs/ops/BRANCHING_MODEL.md">ブランチおよびリリースモデル</a></b></td><td>PR の対象先（<code>release/*</code>）、<code>main</code> とタグの意味</td></tr>
  <tr><td nowrap><b><a href="CHANGELOG.md">変更履歴</a></b></td><td>バージョンごとの完全なリリース履歴</td></tr>
  <tr><td nowrap><b><a href="SECURITY.md">セキュリティポリシー</a></b></td><td>脆弱性の報告とセキュリティ対策</td></tr>
  <tr><td nowrap><b><a href="docs/guides/I18N.md">i18n ガイド</a></b></td><td>67 言語のサポート、翻訳ワークフロー、RTL</td></tr>
  <tr><td nowrap><b><a href="docs/ops/RELEASE_CHECKLIST.md">リリースチェックリスト</a></b></td><td>リリース前の検証手順</td></tr>
  <tr><td nowrap><b><a href="docs/ops/COVERAGE_PLAN.md">カバレッジ計画</a></b></td><td>8,400 以上の追跡対象テストファイルにまたがる 60,000 以上の静的テスト宣言に対するテストカバレッジ戦略</td></tr>
</table>

<br/>

<div align="center">

# ⭐ 主なコントリビューター

> OmniRoute は、情熱を持つオープンソースコミュニティによって形作られています。これらの個人は、プロジェクトの品質、安定性、到達範囲に直接影響する、卓越した貢献を行いました。**ありがとうございます。**

### マージされたプルリクエスト数による外部コントリビューター

<table>
  <tr><th align="center">順位</th><th align="left">コントリビューター</th><th align="center">マージされた PR</th><th align="right">~変更行数</th></tr>
  <tr><td align="center">1</td><td align="left"><a href="https://github.com/maxmad64bis"><b>maxmad64bis</b></a></td><td align="center">418</td><td align="right">25,367,739</td></tr>
  <tr><td align="center">2</td><td align="left"><a href="https://github.com/HouMinXi"><b>HouMinXi</b></a></td><td align="center">295</td><td align="right">13,557,796</td></tr>
  <tr><td align="center">3</td><td align="left"><a href="https://github.com/pacocartones"><b>pacocartones</b></a></td><td align="center">222</td><td align="right">81,551</td></tr>
  <tr><td align="center">4</td><td align="left"><a href="https://github.com/backryun"><b>backryun</b></a></td><td align="center">210</td><td align="right">270,562</td></tr>
  <tr><td align="center">5</td><td align="left"><a href="https://github.com/JxnLexn"><b>JxnLexn</b></a></td><td align="center">198</td><td align="right">3,570,623</td></tr>
  <tr><td align="center">6</td><td align="left"><a href="https://github.com/oyi77"><b>oyi77</b></a></td><td align="center">190</td><td align="right">411,243</td></tr>
  <tr><td align="center">7</td><td align="left"><a href="https://github.com/KooshaPari"><b>KooshaPari</b></a></td><td align="center">151</td><td align="right">5,972,314</td></tr>
  <tr><td align="center">8</td><td align="left"><a href="https://github.com/rdself"><b>rdself</b></a></td><td align="center">145</td><td align="right">80,663</td></tr>
  <tr><td align="center">9</td><td align="left"><a href="https://github.com/RaviTharuma"><b>RaviTharuma</b></a></td><td align="center">123</td><td align="right">500,065</td></tr>
  <tr><td align="center">10</td><td align="left"><a href="https://github.com/herjarsa"><b>herjarsa</b></a></td><td align="center">88</td><td align="right">230,872</td></tr>
  <tr><td align="center">11</td><td align="left"><a href="https://github.com/hartmark"><b>hartmark</b></a></td><td align="center">85</td><td align="right">2,849,623</td></tr>
  <tr><td align="center">12</td><td align="left"><a href="https://github.com/jonlwheat2-gif"><b>jonlwheat2-gif</b></a></td><td align="center">68</td><td align="right">69,097</td></tr>
  <tr><td align="center">13</td><td align="left"><a href="https://github.com/artickc"><b>artickc</b></a></td><td align="center">62</td><td align="right">43,502</td></tr>
  <tr><td align="center">14</td><td align="left"><a href="https://github.com/xiaoyaner0201"><b>xiaoyaner0201</b></a></td><td align="center">59</td><td align="right">126,220</td></tr>
  <tr><td align="center">15</td><td align="left"><a href="https://github.com/chirag127"><b>chirag127</b></a></td><td align="center">52</td><td align="right">6,661</td></tr>
  <tr><td align="center">16</td><td align="left"><a href="https://github.com/xz-dev"><b>xz-dev</b></a></td><td align="center">50</td><td align="right">245,976</td></tr>
  <tr><td align="center">17</td><td align="left"><a href="https://github.com/woodsonl"><b>woodsonl</b></a></td><td align="center">48</td><td align="right">811,771</td></tr>
  <tr><td align="center">18</td><td align="left"><a href="https://github.com/rqzbeh"><b>rqzbeh</b></a></td><td align="center">46</td><td align="right">151,229</td></tr>
  <tr><td align="center">19</td><td align="left"><a href="https://github.com/MumuTW"><b>MumuTW</b></a></td><td align="center">43</td><td align="right">28,166</td></tr>
  <tr><td align="center">19</td><td align="left"><a href="https://github.com/QuangBlue"><b>QuangBlue</b></a></td><td align="center">43</td><td align="right">13,112</td></tr>
</table>

<sub>2026-11-03 03:01:19 UTC に、ライブの <code>release/v3.8.53</code> の先端 <code>05bc048d6c</code> を対象として集計。ページ分割された GitHub GraphQL の集計には、マージされた PR が 9,947 件含まれています。その内訳は、リポジトリ所有者によるものが 4,130 件、Dependabot によるものが 240 件、その他のボット／アプリによるものが 6 件、そして<b>883 人の異なるコントリビューターによる外部 PR が 5,571 件</b>です。「変更行数」は GitHub の追加行数と削除行数を合計したもので、生成ファイル、ロックファイル、カタログ、翻訳、ドキュメントを含みます。これは変更量であり、作成者が記述した LOC ではありません。53 件の PR では GitHub の差分が 500,000 行を超えていると報告されています（たとえば #13399 では、単一のプロバイダー追加で 2,347 個の変更ファイルが記録されています）。そのため、上記のいくつかの合計値が膨らんでいます。同順位は同じ順位として扱います。</sub>

### GitHub に帰属するコミット

<table>
  <tr>
    <td align="center" width="160">
      <a href="https://github.com/maxmad64bis">
        <img src="https://github.com/maxmad64bis.png" width="40" style="border-radius:50%" alt="Dizzle"/><br/>
        <b>Dizzle</b>
      </a><br/>
      <sub>🥇 GitHubに帰属するコミット 418件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/HouMinXi">
        <img src="https://github.com/HouMinXi.png" width="40" style="border-radius:50%" alt="Bob.Hou"/><br/>
        <b>Bob.Hou</b>
      </a><br/>
      <sub>🥈 GitHubに帰属するコミット 294件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/oyi77">
        <img src="https://github.com/oyi77.png" width="40" style="border-radius:50%" alt="Paijo"/><br/>
        <b>Paijo</b>
      </a><br/>
      <sub>🥉 GitHubに帰属するコミット 229件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/pacocartones">
        <img src="https://github.com/pacocartones.png" width="40" style="border-radius:50%" alt="Paco Cartones"/><br/>
        <b>Paco Cartones</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 222件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/backryun">
        <img src="https://github.com/backryun.png" width="40" style="border-radius:50%" alt="backryun"/><br/>
        <b>backryun</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 202件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/JxnLexn">
        <img src="https://github.com/JxnLexn.png" width="40" style="border-radius:50%" alt="Jan Leon"/><br/>
        <b>Jan Leon</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 134件</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="160">
      <a href="https://github.com/RaviTharuma">
        <img src="https://github.com/RaviTharuma.png" width="40" style="border-radius:50%" alt="Ravi Tharuma"/><br/>
        <b>Ravi Tharuma</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 126件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/hartmark">
        <img src="https://github.com/hartmark.png" width="40" style="border-radius:50%" alt="Markus Hartung"/><br/>
        <b>Markus Hartung</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 115件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/rdself">
        <img src="https://github.com/rdself.png" width="40" style="border-radius:50%" alt="Randi"/><br/>
        <b>Randi</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 108件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/christopher-s">
        <img src="https://github.com/christopher-s.png" width="40" style="border-radius:50%" alt="Chris"/><br/>
        <b>Chris</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 70件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/jonlwheat2-gif">
        <img src="https://github.com/jonlwheat2-gif.png" width="40" style="border-radius:50%" alt="WebPerson"/><br/>
        <b>WebPerson</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 68件</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/KooshaPari">
        <img src="https://github.com/KooshaPari.png" width="40" style="border-radius:50%" alt="Koosha Paridehpour"/><br/>
        <b>Koosha Paridehpour</b>
      </a><br/>
      <sub>🏅 GitHubに帰属するコミット 68件</sub>
    </td>
  </tr>
</table>

<sub>2026-11-03 02:09:16 UTCに再確認：<code>release/v3.8.53</code>デフォルトブランチについて、リポジトリのContributors APIが報告したGitHubに帰属するコミットです。APIは903件のID（ユーザー429人、ボット2件、匿名472件）を返しました。この表ではメンテナー、ボット、匿名のIDを除外し、同順位を維持しています。上記のマージ済みPRランキングおよび下記のGitメタデータ集計とは異なるものです。</sub>

> 🙏 これらのコントリビューターによる機能、バグ修正、インフラストラクチャの改善は、OmniRouteの信頼性と豊富な機能を支える**中核的な要素**です。すべてのプルリクエスト、すべてのテストケース、そしてすべてのi18n翻訳ファイルが重要です。オープンソースは、彼らのような人々によって築かれています。

</div>

---

<br/>

## 💖 スポンサー

<div align="center">

私費で OmniRoute を支援してくださっている皆さまに、心より感謝いたします。皆さまからのご支援の一つひとつが、このプロジェクトを無料かつ独立した形で継続し、前進させる力になっています。

<table>
  <tr>
    <td align="center" width="160">
      <a href="https://github.com/drewbitt">
        <img src="https://github.com/drewbitt.png?size=140" width="72" style="border-radius:50%" alt="Andrew"/><br/>
        <b>Andrew</b>
      </a><br/>
      <sub>💛 現在の月額スポンサー</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/psylligent">
        <img src="https://github.com/psylligent.png?size=140" width="72" style="border-radius:50%" alt="Vlad I"/><br/>
        <b>Vlad I</b>
      </a><br/>
      <sub>💛 現在の月額スポンサー</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/xiaoyaner0201">
        <img src="https://github.com/xiaoyaner0201.png?size=140" width="72" style="border-radius:50%" alt="小妍儿"/><br/>
        <b>小妍儿</b>
      </a><br/>
      <sub>💛 現在の月額スポンサー</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/Guilsc">
        <img src="https://github.com/Guilsc.png?size=140" width="72" style="border-radius:50%" alt="Guilherme Costa"/><br/>
        <b>Guilherme Costa</b>
      </a><br/>
      <sub>💛 現在の単発スポンサー</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/TheVingance">
        <img src="https://github.com/TheVingance.png?size=140" width="72" style="border-radius:50%" alt="Henrique Triches Iurkiv"/><br/>
        <b>Henrique Iurkiv</b>
      </a><br/>
      <sub>💛 現在の単発スポンサー</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/somesh-ghaturle">
        <img src="https://github.com/somesh-ghaturle.png?size=140" width="72" style="border-radius:50%" alt="Somesh Ghaturle"/><br/>
        <b>Somesh Ghaturle</b>
      </a><br/>
      <sub>💛 現在の単発スポンサー</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="160">
      <a href="https://github.com/Kolonie-AI">
        <img src="https://github.com/Kolonie-AI.png?size=140" width="72" style="border-radius:50%" alt="Kolonie AI"/><br/>
        <b>Kolonie AI</b>
      </a><br/>
      <sub>💛 過去の単発支援者</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/igormorais123">
        <img src="https://github.com/igormorais123.png?size=140" width="72" style="border-radius:50%" alt="Professor Igor Morais Vasconcelos"/><br/>
        <b>Prof. Igor Morais</b>
      </a><br/>
      <sub>💛 過去の単発支援者</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/PixmaNts">
        <img src="https://github.com/PixmaNts.png?size=140" width="72" style="border-radius:50%" alt="Pixma"/><br/>
        <b>Pixma</b>
      </a><br/>
      <sub>💛 過去の単発支援者</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/pacocartones">
        <img src="https://github.com/pacocartones.png?size=140" width="72" style="border-radius:50%" alt="Paco Cartones"/><br/>
        <b>Paco Cartones</b>
      </a><br/>
      <sub>💛 過去の単発支援者</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/longtao77">
        <img src="https://github.com/longtao77.png?size=140" width="72" style="border-radius:50%" alt="longtao"/><br/>
        <b>longtao</b>
      </a><br/>
      <sub>💛 過去の単発支援者</sub>
    </td>
  </tr>
</table>

<sub>…そして、匿名を希望されるその他の皆さまにも感謝いたします 💛</sub>

<sub>公開されている GitHub Sponsors の情報は、GitHub Sponsors GraphQL API を通じて 2026-10-18 に再検証済みです。合計 14 件のうち、公開スポンサーシップは 11 件（現在 6 件、過去 5 件）です。上記の現在のスポンサー区分は、GitHub の <code>isActive</code> ステータスに基づいています。過去に公開で単発支援してくださった方々も引き続き感謝の対象として掲載し、非公開スポンサーの方々は匿名のままとしています。Ko-fi、Buy Me a Coffee、Liberapay、PIX、および暗号資産による寄付は、公開スポンサー記録がないため掲載していません。</sub>

<b><a href="https://github.com/sponsors/diegosouzapw">💖 スポンサーになる →</a></b> — 皆さまからのご支援の一つひとつが、OmniRoute を無料かつ独立したプロジェクトとして維持する力になります。

</div>

<br/>

<div align="center">

## 👥 1,000人以上のコントリビューター

</div>

[![コントリビューター](https://contrib.rocks/image?repo=diegosouzapw/OmniRoute&max=1074&columns=20&anon=1)](https://github.com/diegosouzapw/OmniRoute/graphs/contributors)

<sub>2026-11-02、ライブの <code>release/v3.8.53</code> の先端 <code>1c7135e0fb</code>（7,972コミット）で監査：<b>正規化された人間のGitアイデンティティ1,074件</b> — 759件はコミット作成者（メンテナーを含む）として表示され、315件は明示的な <code>Co-authored-by</code> トレーラーにのみ表示されます。この集計では <code>.mailmap</code> を適用し、メールアドレスを大文字と小文字を区別せずに比較し、数値形式と通常形式のGitHub noreplyアドレスについては同じハンドルを示す場合にのみ統合しています。また、ボット、エージェント、サービス、プレースホルダーのアイデンティティ29件を除外し、表示名が一致するという理由だけで通常のメールアドレスを統合することはありません。2026-08-24の監査では639件が公開されましたが、その監査のベース <code>ac02c5b42f</code> に対してこの方法を再実行すると619件となるため、増加は新しいコントリビューターによるものであり、方法を緩和した結果ではありません。</sub>

### 貢献方法

1. リポジトリをフォークする
2. **アクティブな** `release/vX.Y.Z` の先端（`main` ではありません）からブランチを作成する — [ブランチ分けとリリースモデル](docs/ops/BRANCHING_MODEL.md)を参照
3. フィーチャーブランチを作成する（`git checkout -b feat/amazing-feature`）
4. 変更をコミットする（`git commit -m 'feat: add amazing feature'`）
5. ブランチにプッシュする（`git push origin feat/amazing-feature`）
6. **base = その `release/vX.Y.Z` ブランチ**でプルリクエストを作成する

詳しいガイドラインについては、[CONTRIBUTING.md](CONTRIBUTING.md)を参照してください。

### 新しいバージョンのリリース

```bash
# リリースを作成 — npm publish は自動的に実行されます
VERSION=x.y.z
gh release create "v${VERSION}" --title "v${VERSION}" --generate-notes
```

<br/>

<div align="center">

## 📊 スター

<a href="https://www.star-history.com/?repos=diegosouzapw%2FOmniRoute&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=diegosouzapw/OmniRoute&type=date&theme=dark&legend=top-left&sealed_token=XP_ycEjv7s31p1edvhsMOXry51OWYsUjDRWjflSG7jQKRpO9hPGg7i_EHvwhI6QtrARTMH-YGjJhi8sumRYflEJD0DPlH_MMHjizhBYCX8fbHFrHEiNvVA" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=diegosouzapw/OmniRoute&type=date&legend=top-left&sealed_token=XP_ycEjv7s31p1edvhsMOXry51OWYsUjDRWjflSG7jQKRpO9hPGg7i_EHvwhI6QtrARTMH-YGjJhi8sumRYflEJD0DPlH_MMHjizhBYCX8fbHFrHEiNvVA" />
   <img alt="スター履歴チャート" src="https://api.star-history.com/chart?repos=diegosouzapw/OmniRoute&type=date&legend=top-left&sealed_token=XP_ycEjv7s31p1edvhsMOXry51OWYsUjDRWjflSG7jQKRpO9hPGg7i_EHvwhI6QtrARTMH-YGjJhi8sumRYflEJD0DPlH_MMHjizhBYCX8fbHFrHEiNvVA" />
 </picture>
</a>

<br/>

<div align="center">

## 🌍 StarMapper

<a href="https://starmapper.bruniaux.com/diegosouzapw/omniroute">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://starmapper.bruniaux.com/api/map-image/diegosouzapw/omniroute?theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://starmapper.bruniaux.com/api/map-image/diegosouzapw/omniroute?theme=light" />
    <img alt="StarMapper" src="https://starmapper.bruniaux.com/api/map-image/diegosouzapw/omniroute" />
  </picture>
</a>
</div>

<br/>

<div align="center">

## 🙏 謝辞

</div>

OmniRoute は、多くの先人たちの成果の上に成り立っています。**[9router](https://github.com/decolua/9router)** のフォークとして始まり、Go プロジェクト **[CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI)** の TypeScript ポートとして発展しました。そしてそこから、以下の各サブシステムは、それぞれ先に道を切り開いたオープンソースプロジェクトから着想を得ています。各プロジェクトが OmniRoute の具体的な一部分を形作りました。これらすべてに感謝を捧げます。🙏

> ⭐ スター数は 2026 年 11 月 3 日に GitHub REST API で確認済みです。ぜひこれらのプロジェクトにスターを付けてください。スター数は特定日時点の正確なスナップショットであり、今後自然に変動します。

### 🧬 系譜とゲートウェイ

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute への影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/decolua/9router">9router</a></b></td><td align="center">31,861</td><td>このフォークの基盤となった元のプロジェクトであり、ここではマルチモーダル API と完全な TypeScript 書き換えによって拡張されています。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/router-for-me/CLIProxyAPI">CLIProxyAPI</a></b></td><td align="center">57,329</td><td>この JavaScript / TypeScript ポートに着想を与えた Go 実装です。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/BerriAI/litellm">LiteLLM</a></b></td><td align="center">62,580</td><td>公開価格データセットがコスト追跡の同期に利用され、プロバイダー正規化モデルがルーティングの参考となった AI ゲートウェイです。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/miuuyy/codex-chatgpt-web">codex-chatgpt-web</a></b></td><td align="center">15,435</td><td>MIT ソースをベンダー提供の ChatGPT Web → Codex Responses ブリッジに適用しました。ブラウザーセッション、レスポンスフレーミング、使用量、Web 検索の各アダプターを含みます。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/Alishahryar1/free-claude-code">free-claude-code</a></b></td><td align="center">65,966</td><td>ストリーム復旧、no-thinking エイリアス、フォールバック Web 検索、スライディングウィンドウ制限、ログの秘匿化、堅牢化されたランチャーフローにパターンを移植しました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/standardagents/composer-api">composer-api</a></b></td><td align="center">347</td><td>Cursor Composer のツール選択、出力制約、ツールコミットのパターンをネイティブ Cursor executor に適用しました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/ndycode/codex-multi-auth">codex-multi-auth</a></b></td><td align="center">561</td><td>Codex OAuth の再認証に、新規ログインと refresh-token ローテーションのパターンを移植しました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/ex-machina-co/opencode-anthropic-auth">opencode-anthropic-auth</a></b></td><td align="center">562</td><td>Claude Code 互換の変換デフォルトと課金ヘッダーの動作を、OmniRoute の設定駆動型ブリッジへと一般化しました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/520mmxx/grok2api-merged">grok2api-merged</a></b></td><td align="center">2</td><td>その Grok モデルマッピング、偽の TypeError Statsig ジェネレーター、リクエストおよびデバイスのデフォルト、NDJSON レスポンスプロセッサーを、OmniRoute の Grok Web executor に実質的に適用しました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/TQZHR/grok2api">TQZHR/grok2api</a></b></td><td align="center">707</td><td>grok2api-merged の背後にある主要な間接コードソースです。そのモデル、ヘッダー、ペイロード、Statsig、プロセッサーの実装は、Grok Web の系譜に保持されています。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/chenyme/grok2api">chenyme/grok2api</a></b></td><td align="center">7,874</td><td>Grok のペイロードとデバイスのデフォルト、Statsig ジェネレーター、および <code>result.response</code> プロセッサーの基盤となる MIT ソースであり、TQZHR と grok2api-merged を経由して引き継がれています。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/miuzhaii/grok2api-pro">grok2api-pro</a></b></td><td align="center">27</td><td>プロキシプール層について grok2api-merged が帰属先として挙げている間接的なソースです。OmniRoute はその系譜に関する注記を保持していますが、範囲を限定した Grok Web executor にプロキシプールを移植したとは主張していません。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/CNFlyCat/GrokProxy">GrokProxy</a></b></td><td align="center">52</td><td>Cookie 認証された Grok プロキシと <code>result.response.token</code> のストリーミングパターンが、OmniRoute の Grok Web トランスポートに影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/lianying1716/GrokBridge">GrokBridge</a></b></td><td align="center">5</td><td>元の Grok Web 実装について、その HTTP / ブラウザー上流設計を参照しました。その直接 HTTP パスは GrokProxy に由来するため、独立したコード移植は主張していません。</td></tr>
</table>

### 🗜️ コンテキストとトークンの圧縮 — エンジン

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute に与えた影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/JuliusBrussee/caveman">Caveman</a></b></td><td align="center">116,957</td><td>話題となった「少ないトークンで足りるのに、なぜ多くのトークンを使うのか」プロジェクト。その原始人風の表現哲学が、標準圧縮モードと30以上の冗長表現除去／短縮ルールの基盤となっています。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/rtk-ai/rtk">RTK – Rust Token Killer</a></b></td><td align="center">85,350</td><td>高性能なコマンド出力圧縮。RTK エンジン、JSON フィルター DSL、生出力の復元、そして RTK → Caveman の多段パイプラインに着想を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/headroomlabs-ai/headroom">headroom</a></b></td><td align="center">78,672</td><td>可逆的なコンテキスト圧縮（SmartCrusher）。<code>headroom</code> エンジンと、<code>ccr</code> の取得マーカーパターンに着想を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/microsoft/LLMLingua">LLMLingua</a></b></td><td align="center">6,797</td><td>プロンプト圧縮の研究（LLMLingua / LLMLingua-2）。非同期でコードに安全かつフェイルオープンな <code>llmlingua</code> エンジンに着想を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/atjsh/llmlingua-2-js">llmlingua-2-js</a></b></td><td align="center">33</td><td>LLMLingua エンジンのワーカースレッド用バックエンドとして使用している JS/ONNX ポート（MobileBERT / XLM-RoBERTa）です。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/leninejunior/troglodita">Troglodita</a></b></td><td align="center">50</td><td>ブラジルポルトガル語のトークン圧縮。ブラジルポルトガル語の文法に合わせて調整された冗語の削減と不要語の除去を行う、pt-BR 言語パックの基盤となっています。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/DietrichGebert/ponytail">ponytail</a></b></td><td align="center">182,929</td><td>話題となった「怠け者のシニア開発者」向け YAGNI コーディングスキル。_生成される_コードを削減する、動作する最小限の変更へ導く <b>less-code</b> 出力スタイルに着想を与えました（Caveman の簡潔な文章に対応する出力軸の兄弟機能です）。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/ayghri/i-have-adhd">i-have-adhd</a></b></td><td align="center">59,838</td><td>行動を優先する ADHD フレンドリーな応答スタイルを、5言語に対応した OmniRoute の簡潔な出力スタイルへ適用しました。</td></tr>
</table>

### 🧩 コンパクト形式、トークン研究、コード対応ツール

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute に与えた影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/toon-format/toon">TOON</a></b></td><td align="center">25,602</td><td>Token-Oriented Object Notation。その列指向の「ヘッダー＋行」モデルが、表形式圧縮ステージの設計に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/blackwell-systems/gcf">GCF – Graph Compact Format</a></b></td><td align="center">61</td><td>コンパクトなグラフ形式と汎用プロファイル設計が、OmniRoute の表形式圧縮と Headroom コーデック形式の参考になりました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/blackwell-systems/gcf-typescript">gcf-typescript</a></b></td><td align="center">4</td><td>Headroom の汎用プロファイルコーデックとして直接ベンダリングし、拡張した MIT ライセンスの TypeScript 実装です。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/ooples/token-optimizer-mcp">token-optimizer-mcp</a></b></td><td align="center">566</td><td>Brotli/SQLite キャッシュとセッション単位のコンテキスト差分。<code>session-dedup</code> エンジンに着想を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/Mibayy/token-savior">token-savior</a></b></td><td align="center">1,203</td><td>Bash 出力の圧縮と MCP プロファイル。圧縮を中止する判断基準と、MCP ツールマニフェストの削減に着想を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/ppgranger/token-saver">token-saver</a></b></td><td align="center">162</td><td>コンテンツを考慮したファイル形式別の出力圧縮と、失敗を考慮した中止処理。形式別の振り分けと、最小削減量に満たない場合のスキップが妥当であることを裏付けました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/alexgreensh/token-optimizer">token-optimizer</a></b></td><td align="center">2,853</td><td>「見えないトークンを見つける」という発想。そのオフロードと復元可能なハンドルのパターンが、CCR のオフロード設計の参考になりました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/Shweta-Mishra-ai/tokenmizer">TokenMizer</a></b></td><td align="center">34</td><td>セッショングラフとターンをまたぐ行重複排除の設計例であり、session-dedup の設計に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/jessefreitas/OmniCompress">OmniCompress</a></b></td><td align="center">3</td><td>Rust による列指向 JSON、コンテンツアドレス方式の取得、メッセージ間の重複排除。<code>headroom</code>/<code>ccr</code>/<code>session-dedup</code> エンジンの設計と、キャッシュの安定性を保証する「圧縮形式は位置に依存しない」という不変条件が妥当であることを裏付けました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/atlassian-labs/mcp-compressor">mcp-compressor</a></b></td><td align="center">140</td><td>MCP ツールのスキーマ／説明の圧縮。MCP ツールマニフェストのカーディナリティ削減の参考になりました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/pdavis68/RepoMapper">RepoMapper</a></b></td><td align="center">218</td><td>Aider 形式のリポジトリマップランキング。リポジトリマップ／検索ランキングの検討に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/mrsimpson/quiet-shell-mcp">quiet-shell-mcp</a></b></td><td align="center">4</td><td>MCP を介した宣言的なシェル出力削減。宣言的な Bash 出力圧縮が妥当であることを裏付けました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/dsherret/ts-morph">ts-morph</a></b></td><td align="center">6,222</td><td>TypeScript Compiler API ツールキット。文字列、テンプレート、正規表現リテラルを保持する、パーサーベースのコメント除去に着想を与えました。</td></tr>
</table>

### 🧠 メモリと RAG

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute への影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/mem0ai/mem0">Mem0</a></b></td><td align="center">68,294</td><td>ユニバーサルメモリーレイヤー — プロキシを介した書き込み／読み取り境界モデルが、当社のメモリアーキテクチャの形成に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/letta-ai/letta">Letta (MemGPT)</a></b></td><td align="center">25,321</td><td>階層化メモリを備えたステートフルエージェント — Context Control & Recovery (CCR) の階層モデルに影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/onestardao/WFGY">WFGY</a></b></td><td align="center">1,804</td><td>繰り返し発生する RAG/LLM の16の障害モードを分類した ProblemMap タクソノミー — トラブルシューティングガイドで使用する共通語彙の基盤となりました。</td></tr>
</table>

### 🛰️ トラフィック検査、MITM、透過プロキシ

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute への影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/chouzz/llm-interceptor">llm-interceptor</a></b></td><td align="center">81</td><td>コーディングアシスタントと LLM 間の MITM によるトラフィックの傍受・分析は、初期の Traffic Inspector 要件に影響を与えました。以前に派生した4つのモジュール — SSE のマージ、会話の正規化、シークレットのマスキング、ヘッダーのサニタイズ — は、公開プロトコル標準に基づく独立したクリーンルーム実装に置き換えられています。2つのホストパススルー領域（<code>passthrough.ts</code> および <code>_internal/bypass.cjs</code>）は、OmniRoute 内部の独立した実装として引き続き扱われます。これらは、その置き換えの一環として書き直されたものではありません。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/InterceptSuite/ProxyBridge">ProxyBridge</a></b></td><td align="center">6,978</td><td>プロセス単位の透過プロキシルーティング — クラッシュセーフな MITM のティアダウン、ソケットのアイドルタイムアウト、<code>/proc</code> によるプロセスの帰属、TPROXY キャプチャに影響を与えました。</td></tr>
</table>

### 📚 モデルデータ、可観測性、UI

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute への影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/anomalyco/models.dev">models.dev</a></b></td><td align="center">7,486</td><td>AI モデルの仕様、価格、機能に関するオープンデータベース — 当社のモデルカタログにネイティブに同期されています。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/xyflow/xyflow">React Flow / xyflow</a></b></td><td align="center">38,874</td><td>リアルタイムの Compression Studio と Combo/Routing Studio を支えるノードベースのグラフライブラリです。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/langchain-ai/langgraph">LangGraph</a></b></td><td align="center">44,349</td><td>LangGraph Studio のライブワークフローグラフ可視化は、当社の Studio におけるリアルタイムのカスケード表示に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/langfuse/langfuse">Langfuse</a></b></td><td align="center">36,907</td><td>その trace → span → generation という可観測性モデルが、当社の Compression Studio のウォーターフォール表示の形を作りました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/kiali/kiali">Kiali</a></b></td><td align="center">3,647</td><td>Istio サービスメッシュの可観測性 — Routing/Combo Studio におけるサーキットブレーカーのバッジとエラーエッジの表示に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/lobehub/lobe-icons">lobe-icons</a></b></td><td align="center">2,666</td><td>ダッシュボード全体でプロバイダーアイコンとして表示される AI/LLM ブランドロゴを提供します。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/lipis/flag-icons">flag-icons</a></b></td><td align="center">12,499</td><td>README の言語セレクターで使用される MIT ライセンスの SVG 国旗を提供します。</td></tr>
</table>

### 🛡️ セキュリティ

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute への影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/tldrsec/awesome-secure-defaults">awesome-secure-defaults</a></b></td><td align="center">723</td><td>セキュアなデフォルト設定を備えたライブラリの厳選リストであり、当社のセキュリティ上の選択（Helmet.js、DOMPurify、ssrf-req-filter、safe-regex、Google Tink）の指針となっています。</td></tr>
</table>

### 🧭 補完的なツール

<table>
  <tr><th align="left">プロジェクト</th><th align="center">⭐</th><th align="left">OmniRoute への影響</th></tr>
  <tr><td nowrap><b><a href="https://github.com/BlockRunAI/ClawRouter">ClawRouter</a></b></td><td align="center">6,649</td><td>リクエストの重複排除、緊急時のゼロコストフォールバック、プラuggable な Auto-Combo 戦略、多言語のインテント分類に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/lbjlaq/Antigravity-Manager">Antigravity-Manager</a></b></td><td align="center">32,785</td><td>アカウントを考慮したモデルのリマッピング、実行可能ファイルパスの検証、プランラベルの動作が、OmniRoute の Antigravity ランタイムに影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/jlcodes99/vscode-antigravity-cockpit">vscode-antigravity-cockpit</a></b></td><td align="center">4,852</td><td>コンパクトなクォータリセットのカウントダウン形式が、OmniRoute における対応するプロバイダー制限表示の着想となりました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/iOfficeAI/AionUi">AionUi</a></b></td><td align="center">33,996</td><td>その ACP 統合が、インストール済み CLI エージェントの OmniRoute による自動検出に影響を与えました。</td></tr>
  <tr><td nowrap><b><a href="https://github.com/steipete/CodexBar">CodexBar</a></b></td><td align="center">22,955</td><td>Grok Build のクォータ領域を特定しました。その後、OmniRoute はライブのワイヤー形式を独自に検証し、修正しました。</td></tr>
</table>

## 📄ライセンス

MITライセンス - 詳細については、 [LICENSE](LICENSE)参照してください。

---

<div align="center">

**[⬆トップに戻る](#-omniroute)**· オープンソースのAIコミュニティ用に❤️で構築されています。

<sub>作成者 <a href="https://github.com/diegosouzapw">ディエゴ・ソウザ</a> · OmniRoute v3.8.55 · ノード≥ 22.22.2 · MITライセンス · <a href="https://omniroute.online">オムニルートオンライン</a></sub>

</div>
<!-- GitHub Discussions enabled for community Q&A -->
