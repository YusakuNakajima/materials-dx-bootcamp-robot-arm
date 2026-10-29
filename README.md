# ゼロからのロボットアーム入門 ~ ロボットの基本動作と制御 ~

材料DX Boot camp 2026（2026年11月11日 Day 2, 10:00–10:45）のハンズオン「ゼロからのロボットアーム入門」（大阪大学 中島優作）の発表資料です。

- スライド: https://yusakunakajima.github.io/materials-dx-bootcamp-robot-arm/
- ベース: [zero_ros](https://github.com/YusakuNakajima/zero_ros) の `slides/robot-arm-basic-control`

## 内容

1. ロボット動作の方法（ティーチングペンダント / プログラム）
2. TCP と重心
3. ロボットの座標系・姿勢表現
4. 動作指令（PTP / LIN / CIRC）
5. 連続動作とブレンド
6. プログラムから動かす（URの例）
7. ロボットアームの精度
8. 位置制御だけでは難しいタスク（RCC / コンプライアンス制御 / フォース制御）

## ローカルで見る

```bash
python3 -m http.server 8000
# http://localhost:8000 を開く
```

## 構成

```
index.html          # Reveal.js スライド本体
assets/             # Reveal.js などのベンダーファイルと共通スタイル
media/              # 画像・動画
interactive_app/    # スライドに埋め込むブラウザアプリ
code/               # スライドで読み込むサンプルコード
```
