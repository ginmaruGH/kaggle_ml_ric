# Kaggleで磨く機械学習の実践力

- [出版サイト](https://www.ric.co.jp/book/new-publication/detail/2168)
- [Follow sit](https://www.ric.co.jp/pdfs/contents/pdfs/1326_support.pdf)
- [sample code](https://www2.ric.co.jp/cgi-bin/download/book_1326.cgi)

---

- [Kaggle](https://www.kaggle.com/)
- [SIGNATE](https://signate.jp/)
- [Nishika](https://www.nishika.com/)
- [ProbSpace](https://comp.probspace.com/)
- [ぐるぐる(atmaCup)](https://www.guruguru.science/competitions)

---

- [LightGBM](https://lightgbm.readthedocs.io/en/latest/index.html)

---

- Part1 分析実務とKaggle
  - Chap.1 実務に必要なスキル
      - 1.1 データサイエンティストという職業
      - 1.2 データサイエンティストに必要なスキル
      - 1.3 分析技術の「使いこなし」スキルの重要性
      - 1.4 実務でのスキルアップの限界とKaggleの活用
  - Chap.2 Kaggleの概要
    - 2.1 Kaggleとは？
    - 2.2 Kaggleで学べること
    - 2.3 Kaggleの学習ツールとしてのメリット
    - 2.4 アカウント登録
    - 2.5 Kaggleの機能
      - 2.5.1 Competitions
      - 2.5.2 Datasets
      - 2.5.3 Code
      - 2.5.4 Discussions
      - 2.5.5 Courses
  - Chap.3 Kaggleを学習ツールに
    - 3.1 Kaggleを用いた学習のプロセス
    - 3.2 学習目的の設定
    - 3.3 コンペの選択
      - 3.3.1 コンペの種類
      - 3.3.2 コンペの選択方法
    - 3.4 分析環境の準備
    - 3.5 コンペの推進と技術調査
    - 3.6 振り返り


- Part2 機械学習の進め方
  - Chap.4 ベースライン作成
    - 4.1 ベースラインと試行錯誤
      - 4.1.1「ベースライン」と呼ばれる骨格を最初に作成する
      - 4.1.2 トライ&エラーを繰り返すことを前提とする
    - 4.2 分析設計
    - 4.3 ファイルの読み込み
    - 4.4 データの確認（簡易）
      - 4.4.1 レコード数とカラム数の確認
      - 4.4.2 カラムごとのデータの種類の確認
      - 4.4.3 欠損値の確認
    - 4.5 データセットの作成
    - 4.6 バリデーション設計
      - 4.6.1「学習データ」と「検証データ」の分割方法
      - 4.6.2 ホールドアウト検証と交差検証
    - 4.7 モデル学習（勾配ブースティング）
      - 4.7.1 ホールドアウト検証の場合
      - 4.7.2 クロスバリデーションの場合
      - 4.7.3 ベースラインの評価
    - 4.8 モデル推論
      - 4.8.1 推論用データセット作成
      - 4.8.2 学習済みモデルを用いた推論
    - Chap.5 特徴量エンジニアリング
      - 5.1 特徴量エンジニアリングの進め方
      - 5.2 データ前処理
        - 5.2.1 データの確認（詳細）
        - 5.2.2 欠損値の把握・補間
        - 5.2.3 外れ値の検出・補正
        - 5.2.4 標準化・正規化
      - 5.3 特徴量生成
        - 5.3.1 単変数: 数値
        - 5.3.2 単変数: カテゴリ変数
        - 5.3.3 2変数組合せ: 数値 x 数値
        - 5.3.4 2変数組合せ: 数値 x カテゴリ変数
        - 5.3.5 2変数組合せ: カテゴリ変数 x カテゴリ変数
        - 5.3.6 時系列データ
        - 5.3.7 テキストデータ
      - 5.4 データセット作成
        - 5.4.1 特徴量選択の方法
        - 5.4.2 ラッパー法の進め方
    - Chap.6 モデルチューニング
      - 6.1 LightGBMのハイパーパラメータのチューニング
        - 6.1.1 ハイパーパラメータの手動チューニング
        - 6.1.2 ハイパーパラメータの自動チューニング
      - 6.2 LightGBM以外のモデル利用
        - 6.2.1 scikit-learnの各種モデル
        - 6.2.2 ニューラルネットワーク
      - 6.3 アンサンブル
        - 6.3.1 単純平均
        - 6.3.2 重み付き平均
        - 6.3.3 スタッキング


- Part3 実践例
  - Chap.7 2値分類のコンペ
    - 7.1 Home Credit Default Riskコンペの概要
    - 7.2 分析のステップ
    - 7.3 ベースライン作成
      - 7.3.1 分析設計
      - 7.3.2 データ前処理
      - 7.3.3 データセット作成
      - 7.3.4 バリデーション設計
      - 7.3.5 モデル学習
      - 7.3.6 モデル推論
    - 7.4 特徴量エンジニアリング
      - 7.4.1 特徴量エンジニアリング: application_train.csv
      - 7.4.2 特徴量エンジニアリング: POS_CASH_balance.csv
    - 7.5 モデルチューニング
      - 7.5.1 optunaによる自動チューニングの実行
  - Chap.8 回帰問題のコンペ
    - 8.1 MLB Player Digital Engagement Forecastingコンペの概要
    - 8.2 分析のステップ
    - 8.3 ベースライン作成
      - 8.3.1 分析設計
      - 8.3.2 データ前処理
      - 8.3.3 データセット作成
      - 8.3.4 バリデーション設計
      - 8.3.5 モデル学習
      - 8.3.6 モデル推論
    - 8.4 特徴量エンジニアリング
      - 8.4.1 データ前処理
      - 8.4.2 データセット作成
      - 8.4.3 モデル学習
      - 8.4.4 モデル推論
    - 8.5 モデルチューニング
      - 8.5.1 データセット作成
      - 8.5.2 モデル学習
      - 8.5.3 モデル推論
  - Chap.9 データサイエンティストの未来
    - 9.1 データサイエンティストの将来性
    - 9.2 Kaggleは実務で活躍できるか？
    - 9.3 楽しいKaggle
