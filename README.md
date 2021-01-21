# Pivottable
* ピボットテーブルのプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── Dockerfile                Dockerファイル
└── notebook                  jupyter notebook
```

## 環境構築
Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Pivottable）
```
cd Desktop/Pivottable
```
Dockerによる環境構築
```
docker build .
```
docker run実行（対象フォルダをマウントする／例：Desktop/Pivottable）
```
docker run -p 8888:8888 -v ~/Desktop/Pivottable/:/work --name Pivottable <docker image>
```
ブラウザーを立ち上げてlocalhost:8888へアクセス
workフォルダ内が対象フォルダにマウントされている

## jupyter notebook説明
* Pivottable.ipynb : ピボットテーブルのnotebook

## outputイメージ
![Pivottable_image](https://user-images.githubusercontent.com/66448467/105350155-0cec5d00-5c2e-11eb-96a5-21a74dedcbf7.png)

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3