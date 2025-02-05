---
marp : true
theme: ume-orange
paginate: true
header : IS 対応マニュアル FS 引き継ぎ対応
footer : 2025.01.17 Fri マーケティング部 小松
transition : pull 300ms
---
<!-- _paginate : skip -->
<!-- _class : cover -->

# IS 対応マニュアル
## FS 引き継ぎ対応の方法

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 -->
<!-- _class: overview -->

<div>
<div>

## 目次

</div>
<div>

- [FS引継ぎとは](#handover)
- [引継ぎタイミング](#timing)
- [見積希望の場合](#quote)
- [打ち合わせ希望の場合](#meeting)
- [その他の場合](#other)

</div>
</div>

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 -->
<span id="handover"></span>

## FS引継ぎとは

IS対応外の案件やフェーズでFSへ必要な情報伝達・タスク作成・依頼を行うこと。

本マニュアルでは、IS対応案件でFS引継ぎタイミングになった際の対応について説明する。
ISとFS兼任の場合、ISとしての対応が完了し、FSとしての対応がはじまる際の対応方法となっている。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 -->
<span id="timing"></span>

## FS引継ぎタイミング

FS引継ぎタイミング＝IS対応が終了するタイミング。

ISとFS兼任の場合、FSとしての対応がスタートするタイミングでもある。

- 見積作成
- 打ち合わせ日時調整
- システム連携希望が判明した時：<strong>民泊INN / ホテルスマート / エアホストの場合のみ</strong>前田Mgrへ引継ぎ。契約内容が煩雑のため。
- 価格交渉

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 -->
<span id=quote></span>

## 見積希望の場合

### 対応の流れ

1. プロパティ更新＆タスク確認
1. 取引レコード作成
1. プロパティ更新
1. 関連付けの確認・操作
1. タスク作成
1. Trello更新
1. タスクに引継ぎコメント

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 見積希望の場合-->

### 1.プロパティ更新＆タスク確認

コンタクトレコードの下記プロパティを更新する。

- 問い合わせ内容分類（WF）の「見積もり」選択。
- 問い合わせパターン（WF）の「H - 引き継ぎのみ」選択。
- 自動作成されるタスク「一次対応_見積もりクッション メール送信」を削除。
- タスク「営業対応依頼_見積もり」が作成されていることを確認。
- タスクの説明欄通りに作業を進める。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 見積希望の場合-->

### 2.取引レコード作成

コンタクトレコード表示画面の右側にある”取引（0件）”の右側「＋追加」クリック。

「取引を作成」画面が表示されるので、「取引名」を「会社名 姓さま LINKEY Plus (単体 or/and 遠隔)プラン 〇台 施工手配(あり or なし or 不明)」と入力。

> (ex.株式会社ユーエムイー 小松さま LINKEY Plus 遠隔プラン 1台 施工手配不明)

プラン名と台数と施工手配有無がわかるように記載する。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 見積希望の場合-->
<!-- _class: sm -->

### 3.プロパティ更新

各レコードの下記セクション・プロパティを更新する。

#### 取引レコード（セクション）

- この取引の概要

#### コンタクトレコード（プロパティ）

- コンタクト担当者
- 追客完了日
- IS対応完了の理由
- その他更新事項があるプロパティ

会社レコード（プロパティ）
- 会社の担当者

各セクション・プロパティの入力ルールは[こちら](https://docs.google.com/document/d/1r7fNILlrSG4xram_D-H_yWUVuaJSOS5fATU5Q5cnhMk/edit?usp=sharing)

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 見積希望の場合-->

### 4.関連付けの確認・操作

コンタクトレコード～会社レコード～取引レコードの3レコードがそれぞれ正常に関連付けされているか確認する。
取引レコードのページにて会社レコードが関連付けされていないことが多いため、要チェック。

取引レコードで作成したタスクの関連付けが正常にされているか確認する。関連付けされていないコンタクト・会社・取引 があれば関連付けを行う。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 見積希望の場合-->

### 5.タスク作成

手順

- タスクを作成＞タイトル「見積作成依頼 to 営業事務」入力。
- 期日「1営業日以内/時間選択」優先度「中」
- アクティビティの割当先に営業担当者選択。
- メモに見積内容入力。（リード宛に送ったメールからコピペすればOK）
- 左下の「作成」押下。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 見積希望の場合-->

### 6.Trello更新

IS完了リストにカードを新規作成。
詳細は[こちら]([url](https://docs.google.com/document/d/1DRouAwQC5op5pLMc9HhXiXacVwaKiEQ9bJUKe60iL4A/edit?tab=t.0#heading=h.gxx3y1q8oxur))

### 7.タスクに引継ぎコメント

先ほど作成した「見積作成依頼 to 営業事務」タスクのコメントで、
井出常務・栗原Ld・小松宛にFSへ引き継いだ＝IS対応完了した報告を行う。

> (コメント内容
@井出 俊樹 @栗原 大輔 @小松 佳廉
お疲れ様です。○○です。
見積ご希望につき営業案件としております。)

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 打ち合わせ希望の場合-->
<span id="meeting"></span>

## 打ち合わせ希望の場合

### 対応の流れ

1. プロパティ更新＆タスク確認
1. タスク作成
1. プロパティ更新
1. Trello更新
1. タスクに引継ぎコメント

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 打ち合わせ希望の場合-->

### 1.プロパティ更新＆タスク確認

コンタクトレコードの下記プロパティを更新する。

- 問い合わせ内容分類（WF）の「打ち合わせ」選択。
- 問い合わせパターン（WF）の「H - 引き継ぎのみ」選択。
- 自動作成されるタスク「一次対応_打ち合わせクッション メール送信」を削除。
- タスク「営業対応依頼_打ち合わせ」が作成されていることを確認。
- タスクの説明欄通りに作業を進める。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 打ち合わせ希望の場合-->

### 2.タスク作成

手順

- タスクを作成＞タイトル「打ち合わせ日時調整 & 対応」入力。
- 期日「1営業日以内/時間選択」優先度「中」
- アクティビティの割当先に営業担当者選択。
- メモに打ち合わせ内容入力。（スニペット（#meet）「打ち合わせ取次 to 営業」を活用すると便利）
- 左下の「作成」押下。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 打ち合わせ希望の場合-->

### 3.プロパティ更新

コンタクト・会社レコードの下記プロパティを更新する。

コンタクトレコード

- コンタクト担当者を担当営業に変更。
- ライフサイクルステージを「SQL」に変更。
- 追客完了日を選択。
- IS対応完了の理由の「打ち合わせパス」選択。
- その他ヒアリング事項など更新できる箇所がある場合は、随時更新。

会社レコード
- 会社の担当者を担当営業に変更。
  
---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > 打ち合わせ希望の場合-->

### 4.Trello更新

IS完了リストにカードを新規作成。
詳細は[こちら]([url](https://docs.google.com/document/d/1DRouAwQC5op5pLMc9HhXiXacVwaKiEQ9bJUKe60iL4A/edit?tab=t.0#heading=h.gxx3y1q8oxur))

### 5.タスクに引継ぎコメント

先ほど作成した「打ち合わせ日時調整 & 対応」タスクのコメントで、
井出常務・栗原Ld・小松宛にFSへ引き継いだ＝IS対応完了した報告を行う。

> (コメント内容
@井出 俊樹 @栗原 大輔 @小松 佳廉
お疲れ様です。○○です。
打ち合わせご希望につき営業案件としております。)

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > その他の場合 -->
<span id="other"></span>

## その他の場合

その他システム連携や価格交渉等、引継ぎが発生した場合

### 対応の流れ

1. タスク作成
1. プロパティ更新
1. Trello更新
1. タスクに引継ぎコメント

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > その他の場合 -->

### 1.タスク作成

手順

- タスクを作成＞依頼タイトル入力。
  （ex.システム連携に関する連絡/価格交渉連絡など）
- 期日、優先度を適切な値選択。
- アクティビティの割当先に担当者選択。
- メモに依頼内容入力。
  （ex.民泊INNとの連携希望のお客様です。システム連携方法についてご連絡お願いします。など）
- 左下の「作成」押下。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > その他の場合 -->

### 2.プロパティ更新

コンタクト・会社レコードの下記プロパティを更新する。

コンタクトレコード

- コンタクト担当者を担当営業に変更。
- ライフサイクルステージを「SQL」に変更。
- 追客完了日を選択。
- IS対応完了の理由を選択。
- その他ヒアリング事項など更新できる箇所がある場合は、随時更新。

会社レコード
- 会社の担当者を担当営業に変更。

---
<!-- _header : IS 対応マニュアル FS 引き継ぎ対応 > その他の場合 -->

### 3.Trello更新

IS完了リストにカードを新規作成。
詳細は[こちら]([url](https://docs.google.com/document/d/1DRouAwQC5op5pLMc9HhXiXacVwaKiEQ9bJUKe60iL4A/edit?tab=t.0#heading=h.gxx3y1q8oxur))

### 4.タスクに引継ぎコメント

先ほど作成したタスクのコメントで、担当者への依頼と
井出常務・栗原Ld・小松宛にFSへ引き継いだ＝IS対応完了した報告を行う。

> (コメント内容
@担当者
○○につき、取次いたします。
ご対応のほどよろしくお願いいたします。
@井出 俊樹 @栗原 大輔 @小松 佳廉
お疲れ様です。○○です。
○○につき営業案件としております。)

---
<!-- _class: cover -->

# おしまい

