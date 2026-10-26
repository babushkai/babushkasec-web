# BabushkaSec 配信リポジトリ（生成物のみ）

**ここで編集しないでください。** ビルド成果物だけを置く GitHub Pages 用のリポジトリです。

- 実装・コピー・テスト: `babushkai/security-advisory`（非公開）
- 反映: そちらで `npm run validate` → `dist/` の中身をこのリポジトリの main に push
- 配信: https://security.babushkai.com
- 注意: `public/_headers` は GitHub Pages では効きません（Netlify 用）。Content-Security-Policy は HTML の `<meta http-equiv>` として出力されています。
- 現在 `noindex, nofollow` と `robots.txt: Disallow: /` のまま配信しています（ソフトローンチ）。
