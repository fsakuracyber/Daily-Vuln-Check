# 脆弱性デイリー調査

過去24Hで新たに話題になったものをPickUpしている。

## レポート

- [2026年9月20日の調査](./デイリー調査_2026-09-20.md)
- 今後のレポートも `デイリー調査_YYYY-MM-DD.md` の形式で追加します。ファイル名の日付は日本時間（JST）です。

## 調査と記載の方針

製品・プロジェクトのセキュリティアドバイザリ、リリースノート、修正履歴、上流リポジトリなどの一次情報を確認します。CVE レコード、[NVD](https://nvd.nist.gov/) や [CISA の Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) も照合し、各項目に根拠となるリンクを付けます。報道や脅威インテリジェンスは発見や状況把握の手掛かりとして使い、一次情報で確認できた事実と、外部組織による観測・評価を区別します。

「実悪用あり」「公開 PoC あり」「修正版あり」は別の状態です。攻撃の試行と侵害の成功、実証コードと一般公開された攻撃コードも同一視しません。確認できない点や情報源による差がある点は、そのまま記載します。CVSS の値だけで順位を決めず、悪用状況、攻撃に必要な条件、公開範囲、影響、対策の有無を合わせて判断します。あくまで調査時点です。

一次情報の例：[GitHub Advisory Database](https://github.com/advisories)、[WordPress のセキュリティリリース](https://wordpress.org/news/category/security/)、[SolarWinds ARM のリリースノート](https://documentation.solarwinds.com/en/success_center/arm/content/release_notes/arm_2026-2-1_release_notes.htm)、[Gravity Forms の変更履歴](https://docs.gravityforms.com/gravityforms-change-log/)。個々の判断では、各日のレポートに示した案件別の出典を参照してください。

## 利用にあたって

レポートは記載された最終確認時刻時点の情報です。公開後に影響バージョン、修正版、悪用状況などが変わることがあります。実際の対応では、対象環境を確認したうえで、リンク先のベンダー告知や上流の最新情報を再確認してください。誤りや更新が判明した場合は、後続のレポートで訂正します。

本リポジトリの文章・表の流用、改変、再配布、商用利用は自由です。リンク先など第三者のコンテンツは、それぞれの権利・利用条件に従ってください。**本リポジトリの情報の利用・再利用は、ご自身の判断と責任でお願いします。**
