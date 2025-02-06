# プロジェクトの概要

## アプリについて
ポートフォリオが閉じてしまって、現在はないので作り直しました。
Next.jsとtypeScriptを使って作成しています。

## フォルダ構成
```
portfolio/
├── docker/          # Docker関連のファイルを格納（ビルドファイルなど）
│   └── Dockerfile   # Docker イメージの設定
├── src/
│   ├── app          # ルーティングに関するコンポーネント
│   ├── features     # ロジック + コンポーネントをまとめたもの
│   │   ├── common   # 共通部分
│   │   └── routes   # 特定のページで使うもの
│   ├── components   # ロジックがない共通コンポーンネント
│   ├── public       # 静的ファイルたち
│   ├── hooks        # 共通ロジックの内、React Hooksが「ある」もの
│   ├── utils        # 共通ロジックの内、React Hooksが「ない」もの
│   ├── constants    # 定数を定義したファイル
│   ├── styles       # scssを格納するフォルダ
│   └── README.md    # プロジェクトの説明
├── compose.yml      # Docker Compose 設定ファイル
└── README.md        # プロジェクトの説明

```