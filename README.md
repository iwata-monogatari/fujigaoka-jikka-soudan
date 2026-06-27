# ふじがおか 実家じまい・空き家相談室

富士ヶ丘サービス株式会社が運営する、相続した実家・空き家・ご両親の家の整理に特化した
不動産売却「相談」サイト（静的サイト）です。

> ご両親の家、相続した実家、空き家のこと。売る前に、まず一緒に整理しませんか。

## 公開URL
https://iwata-monogatari.github.io/fujigaoka-jikka-soudan/

## GitHubアップ先 / 格納先フォルダ
- アップ先：https://github.com/iwata-monogatari/fujigaoka-jikka-soudan/upload/main
- 格納先フォルダ：C:\Users\fujig\Desktop\99大石制作物\02空き家相談事業サイト\ルートへ上書き

## ファイル構成（すべて同じ階層・フラット）

```text
index.html                 … トップページ
important-disclosure.html  … ガイド：重要事項説明書のどこを見るべきか
contact.html               … お問い合わせ・相談フォーム
privacy-policy.html        … プライバシーポリシー
style.css                  … デザイン（くすみブルー × 生成り × テラコッタ）
main.js                    … ナビ開閉・FAQ・スムーススクロール
README.md
```

## 反映手順（ドラッグ＆ドロップ）
1. https://github.com/iwata-monogatari/fujigaoka-jikka-soudan/upload/main を開く
2. 上記の格納先フォルダを開く
3. 中のファイルを全選択（Ctrl+A）→ ドラッグ＆ドロップ →「Commit changes」
4. 1〜2分で公開URLに自動反映

## 公開前に差し替える項目（プレースホルダー）
- 電話番号：`tel:0000000000` と表示文言（`000-000-0000`）
- LINEリンク：`href="#"`（LINE公式アカウントURLへ）
- **問い合わせフォームの送信先**：contact.html の `form action="https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID"`
  - Formspree（無料）でフォームIDを取得し差し替えると、送信内容が fudosan.fujigaokas@gmail.com に届きます。
  - Googleフォーム派の場合は、contact.html のフォーム部分をGoogleフォームのリンク／埋め込みに置き換え。
- 会社情報・プライバシーポリシー内：住所・宅建免許番号・受付時間
- 関連サイトリンク：富士ヶ丘サービス公式 / 不動産ページ / 磐田物語（`href="#"`）
- 画像：ヒーロー・代表写真など（現在は画像なしでも崩れないプレースホルダー表示）

## デザイン（配色）
緑系の磐田物語・公式サイトと差別化した別系統の配色。`style.css` 冒頭の `:root` で変更可。

| 役割 | 色 | コード |
|---|---|---|
| 背景（生成り） | クリーム | `#faf7f0` |
| 主役 | 藍鼠ブルー | `#44637a` / 濃 `#324c5e` |
| 差し色 | テラコッタ | `#c97b5a` |

## 運用方針
ブログのように毎週更新しません。お知らせ欄も置きません。
月1回：各リンク・フォーム送信テスト・表示崩れ確認／3か月に1回：料金・エリア・FAQ見直し。
