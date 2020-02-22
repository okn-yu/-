### 2章

### 3章

### 4章 GLMのモデル選択
* 平均対数尤度は（真のモデルは一般的には不明なため）直接計算で求めることはできない
* 平均対数尤度の**推定量**は以下で与えられる
* 最大対数尤度 - モデルのパラメータ数

#### 用語の整理
* 最大対数尤度：モデルの推定に用いる尺度。モデルの既知データに対してどの程度フィットできるか
* 平均対数尤度：モデルの予測に用いる尺度。モデルの未知データに対してどの程度フィットできるか
* バイアス：最大対数尤度から平均対数尤度を減算した値。バイアスは正負いずれの値も取りうる
* AIC（赤池情報量基準）：平均対数尤度の推定量に(-2)を乗じた値
