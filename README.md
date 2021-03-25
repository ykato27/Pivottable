# Pivottable
* ピボットテーブルのプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
└── notebook                  jupyter notebook
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Pivottable）
```
cd Desktop/Pivottable
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Pivottable）
```
docker-compose up
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* Pivottable.ipynb : ピボットテーブルのnotebook

## outputイメージ
![Pivottable_image](https://user-images.githubusercontent.com/66448467/105350155-0cec5d00-5c2e-11eb-96a5-21a74dedcbf7.png)

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
