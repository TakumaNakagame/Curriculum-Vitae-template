# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name| かめねこ (Takuma Nakagame)|
|Twitter|[@kameneko1004](https://twitter.com/kameneko1004)|
|Qiita|[かめねこ](https://qiita.com/Kameneko)|
|Speakerdeck|[kameneko](https://speakerdeck.com/takumanakagame)|

## スキル

### 言語

- プログラミング言語
  - C#
    - 学生時代
  - JavaScript
    - 現在勉強中 
- 日本語
  - ネイティブ
- 英語（例）
  - かんたんな技術文書が読める

### フレームワーク

- vue.js
  - [サークルサイト - https://www.lab-dev.net](https://www.lab-dev.net)

### その他

#### 仕事

- 自社データセンターでのVMware vSphere基盤の構築・運用経験
  - 物理サーバ・ストレージのラッキングや構築・運用経験
  - HPE製スイッチ(Cisco系/H3C系)の構築・運用経験
  - ストレージ機器の性能・耐障害性検証の経験(vdbenchを使用)
  - vSphere ESXiのインストール ～ vCenter Serverの構築まで経験
  - vSphere NSXの構築・運用経験
- [FreeNAS](http://freenas.org)の構築・運用経験
- チームにWikiの文化を定着
- Windows Serverの構築経験
  - 2008 R2/ 2012 R2/ 2016
  - 初期構築
  - トラブル対応など
- Linuxの業務利用経験
  - CentOS6/ CentOS7
  - 内部向けサーバで、Dockerを使ったアプリケーション管理

#### 趣味

- Nginxでのリバースプロキシの構成
  - 自分用Redmine/Growiをサブドメインでのリバプロ運用
- 自宅サーバの運用
  - サーバ: vSphere ESXi 6.7 on PowerEdge R610
- Docker
  - Immutable Infrastructureを目指して勉強中

## 強み

- 技術に貪欲な姿勢
- 知らないこと/わからないことは、**とりあえず触ってみる**。
- 常に、どんな物事にも疑問を持ち、改善を続ける姿勢

## やったことはないが興味があるもの

- k8s
- Nuxt.js
- PWA
- Nutanix
- SaaS/PaaS構築
  - Lambda/RDS/GKEなどのプラットフォーム構築

## 登壇歴

### オフライン

- 18/10/24 [「クラウド自動化の基礎」～API設計、Ansible基礎、監視自動化～＠銀座 - connpass](https://fujitsufjct.connpass.com/event/102725/)
  - **コミュニティ**: ニフクラエンジニアミートアップ
  - **概要**: 自動化回ということで、CircleCIを初めて使った感想と、実演をLTしました。
  - **スライド**: [CircleCIでCI/CDを体験した話 - Speaker Deck](https://speakerdeck.com/takumanakagame/cdwoti-yan-sitahua)
- 18/10/26 [執筆の技術を勉強する会 #1 - connpass](https://engineers.connpass.com/event/104055/)
  - **コミュニティ**: エンジニアの登壇を応援する会
  - **概要**: FreeNAS本の執筆を経て、技術書執筆に感じるハードルと、そのハードルの実態について話しました。
  - **スライド**: [アウトプットをほとんどしないペンギンが本を書いた話 - Speaker Deck](https://speakerdeck.com/takumanakagame/autopututowohotondosinaipengingaben-woshu-itahua)

### オンライン

- インフラ勉強会にて各種セッション
  - FreeNAS
  - ActiveDirectory
  - Chef
  - etc ...

## 執筆歴

### 同人

- 技術書典5にて[0から始める！簡単！FreeNAS構築チュートリアル！](https://kameneko.booth.pm/items/1034744)を執筆しました
  - 累計166部頒布
    - 紙: 80部完売
    - 電子版: 64部
    - Booth: 22部

## 職務経歴

### 2017/04 - : 株式会社 TD

- インフラエンジニア
- 新卒入社

#### プライベートクラウドの構築・運用

- 自社データセンターにて、vSphereを利用した仮想基盤の構築を行っています。
- サーバ・ストレージ・スイッチなどのラッキング・配線作業
- HPE製スイッチの初期設定・設定変更（Cisco/H3C系コマンド）
- vSphereの経験
  - ESXi 6.5のインストール
  - vCenter Serverのデプロイ(外部PSC)
  - vCetner Serverの構築
  - vSphere NSXの構築・運用
- FreeNASの経験
  - FreeNASの設計/構築/運用全てを担当
  - NASアプライアンスのリプレースのため、FreeNASを使用
  - レプリケーションやロードバランサを利用して、「アップデートや障害でも落ちないファイルサーバ」を検証する
- Windows Serverの基本的な運用
  - 開発部署への提供のために、マスターイメージの作成や、初期設定などを随時対応

#### ストレージ検証

- ストレージベンダ3社のストレージ(SSD)性能検証
- `vdbench`を使用
- 主に、レスポンス/パフォーマンス/可用性を検証

#### Active Directoryの移行作業

- 複数台あるADDCの1台を新しい機器へリプレース
- TempADを立てる方式ではなく、旧AD降格 → 新AD昇格という手順で作業実施
- 対応中、ADDCの降格に失敗（ウィザードが終了しない）し、強制降格を実施
