# Ponzu Studio Works コーポレートサイト

調味料専門EC事業者向けの静的Webサイト（HTML / CSS / JavaScript）。サーバーサイド処理やビルドは不要です。AI生成のコンセプト画像を含みます。設立は2026年7月、問い合わせ先は rie_ponzu_ceo@ponzustudioworks.shop に設定しています。

## アップロード

ZIPを展開し、**`index.html` / `privacy.html` / `assets/` / `.nojekyll` / `README.md` をGitHubリポジトリのルートに配置**してください。ZIPの中身はルート直下に必要ファイルがある構造です。

GitHubでリポジトリ → Settings → Pages → `Deploy from a branch` → `main` / `/(root)` → Save。

## 独自ドメイン `ponzustudioworks.shop` を設定する場合

1. GitHubの `Settings → Pages → Custom domain` に `ponzustudioworks.shop` を入力・保存する（GitHubがCNAMEファイルを生成）。
2. VALUE-DOMAINなどのDNS管理画面で、**ルートドメインのAレコード**をGitHub PagesのIPアドレスに設定する。
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
3. 任意で `www` を `ishibashi09.github.io` へのCNAMEに設定する。DNS反映後にHTTPS設定を有効化する。
4. **既存のメール用MX/TXT/SPF/DKIM等のDNSレコードは削除しないこと**。WebサイトのAレコードを追加・変更する場合もメール設定は維持する。

> GitHub Pagesの独自ドメイン設定が終わるまで、`CNAME` はZIPに含めていません。前もって含めると既存の仮公開URLに影響する場合があるためです。

## Claude for Startups申し込み前の確認

- 企業・事業サイトを公開済みであること。
- 申込メール `rie_ponzu_ceo@ponzustudioworks.shop` が実際に送受信できること。
- Claude Consoleアカウントを作成済みであること。
- 何を構築しているか、Claudeをどこに利用するかを正確に説明できること。実際の導入実績を偽らないこと。
- プログラムの募集状況・資格条件を申込当日に公式で再確認すること。2026年10月13日に現在の募集枠満了と発表されました。

プログラム： https://claude.com/programs/startups
公式募集情報：https://claude.com/resources/articles/were-expanding-the-claude-startups-program-to-help-founders-build

## 公開前の確認

- `事業名称` は正式な屋号・事業者名として正しいか確認。
- 事業内容の各記述が実際の活動に合っているか確認。
- AI画像は実際のオフィス/スタッフ写真ではありません。サイトではイメージ画像として記載しています。
- `privacy.html` の個人情報取扱い方針が実際の運営と一致することを確認。
- 独自ドメイン運用時にはDNS・メール送受信・HTTPS・サイト表示を確認。

## フォルダ

```
index.html
privacy.html
.nojekyll
README.md
assets/
  favicon.svg
  css/style.css
  js/script.js
  images/hero.webp
  images/operations.webp
```


## この版について（2026年10月）

- 事業内容：調味料に特化したEC事業の企画・運営、オンライン販売。
- 設立：2026年7月。
- 問い合わせメール：`rie_ponzu_ceo@ponzustudioworks.shop`。
- 商品写真はAI生成したイメージ素材で、実際の販売商品・取引先・実績を示すものではありません。
- 販売ストアのURL、事業者の法的な名称、所在地、代表者名など、必要に応じて事実に基づき追記してください。
- Claude for Startups の資格や募集状況は公式サイトで最新情報をご確認ください。
