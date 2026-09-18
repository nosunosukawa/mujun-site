# mujun-site — 矛盾。(PARADOX.) のサポート・プライバシーページ

App Store Connect が要求する3本のURLの実体。公開先は GitHub Pages（`main` ブランチの `/`）。

| 用途 | URL | ファイル |
|---|---|---|
| マーケティングURL | https://nosunosukawa.github.io/mujun-site/ | `index.html` |
| サポートURL | https://nosunosukawa.github.io/mujun-site/support.html | `support.html` |
| プライバシーポリシーURL | https://nosunosukawa.github.io/mujun-site/privacy.html | `privacy.html` |

アプリ本体は `~/projects/mobile/mujun`。

## 直すときの約束

- **プライバシーポリシーの本文の出典は `mobile/mujun/docs/PRIVACY.md`。** 片方だけ直さない
- アプリが実際にやらないことを書かない（オンライン対戦・課金の復元・アカウント・広告は**無い**）
- 「診断」「心理テスト」「IQ」「頭の良さ」は使わない（アプリ側の約束 §25 / §36 / §99）
- 価格の話（「無料」等）は書かない（App Review 2.3.7。2026-08-18 に別アプリが副題で却下された）
- 計測タグは入れていない。入れるなら Cloudflare Web Analytics のトークンをこのサイト用に取り、
  privacy.html に「このウェブサイトの計測」の節を足してから

## 手元で見る

```bash
python3 -m http.server 8931
open http://127.0.0.1:8931/
```
