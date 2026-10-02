# 検証メモ

確認日: 2026-10-02（日本時間）

## 照合方法

英雄別の遠征スキル本文・倍率は、WOS Forge WikiとWOS Heroesの全34英雄ページを自動収集し、英雄ごとのスキル数と内容を照合しました。世代・兵種・レアリティはWoS GuruのHero Databaseとも突合し、第7〜8世代および日本語名はアルテマの記事で補助確認しました。

## 解消した不一致

- Hector: WOS Forgeの表順は `Rampant / Blitz / Survival Instincts`、WOS HeroesとWoS Guruは `Survival Instincts / Rampant / Blitz`。乗り手参照の第1スキルについて具体的に記載するWoS Guruおよび別の2026年ガイドとも一致したため、後者を採用。
- Norah: WOS Forgeの表順は `Momentum / Combined Arms / Sneak Strike`、WOS HeroesとWoS Guruは `Combined Arms / Sneak Strike / Momentum`。WoS GuruがCombined Armsを第1遠征スキルと明記しているため後者を採用。
- Hendrik: 第3スキル名に `Dragon's Heir` / `Dagon's Heir` の表記差があるが、スキル名は成果物の要件外。効果本文と倍率は一致。
- Lynn: WOS Heroesの要約表示に `100–5%` という整形誤りがある。WOS Forgeのレベル列 `1/2/3/4/5%` を採用。

## 制約

- Century Gamesは全英雄の遠征スキルを一括公開する公式データベースを提供していないため、スキル本文は公開コミュニティデータベース同士の照合結果です。
- 日本語の効果文は英語原文の意味を保持した要約です。監査用に各スキルの`sourceTextEn`と英雄別URLをJSONへ残しています。
- 計算枠は依頼時に定義された11枠だけです。11枠外の効果を無理に分類していません。

## 主な参照先

- WOS Forge Wiki: https://wiki.wosforge.org/wiki/Hero_Skills
- WOS Heroes: https://wosheroes.com/heroes/
- WoS Guru Hero Database: https://wosguru.com/hero-database
- WoS Guru Heroes（Hector/Norahの順序確認）: https://wosguru.com/heroes
- アルテマ 英雄一覧: https://altema.jp/whiteoutsurvival/charaichiran
- アルテマ Hendrik: https://altema.jp/whiteoutsurvival/chara/37
