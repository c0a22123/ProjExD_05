# ゲーム のタイトル
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
こうかとんの仁義なき戦い

## ゲームの実装
###共通基本機能
敵を倒し
スコアが追加される

### 担当追加機能
* 画像差し替え c0b22105 テイコウキン
* 敵パワーアップ c0b22145 望月隆司
* 敵追加 c0a22159 諫山隼汰
* 味方パワーアップ c0a22123 廣田俊介
* アイテム実装  c0b22085
### メモ
**基礎機能**
* Escapeボタンを押すとゲーム終了
* ←→　ボタンで移動
* Spease ボタンでビーム発射
* 敵に当たるか爆弾にあたるとゲームオーバ
* 敵にビームが当たるとScore１UP

**追加機能、敵パワーアップ**
* 敵を5体倒すと新しく出てくる敵の速度が2上昇する

**追加機能　敵追加**
* SCOREが20の倍数になると敵を1体追加する
* 出現する敵は通常の敵よりも小さく、速く、得点が高い(10点)

**追加機能　味方パワーアップ**
* TABボタンでSUPERMODEに変更
* SUPERMODE中は敵にビームをあてると自分からビームを打つ

