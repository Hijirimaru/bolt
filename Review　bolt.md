# section11 bolt(PC)
## 全体
--- 例 ---
1. 修正指示を記載します(メンター)
  - 修正内容を記載してください(研修生)
    例) 〇〇クラスに××を指定して△△になるようにしました。
----------

1. ボルトアイコンピクセルで指定
  - ボルトアイコンをlerge出なく24pxでサイズ指定

2. aタグ下線消す
  - textdecoration:noneでaタグの下線が出ないようにcssで修正

3. ヘッダーのtopとleft０にする
  - position:fixedの時もtopとleftの記述がいるそうなので記述を追加

4. font指定２つ書くralewayがタイトル
  - title-fontクラスを追加して2種類のフォントで使い分けるように修正

5. ourskillとourlatestwork margin-bottom消す
  - margin-bottomeが残っていたので修正

6. footerはfloat出なくtextaligen rightで右へ
  - footerをtextaligenで右に寄せたことでclearfixを使わずに済むように修正

7. スクロール時にzindexで画像が後ろ側になるように
  - headerにzindex:1の記述をを加えて必ず前側になるよう修正

8. skillとSNSをfloat以外の方法で位置調整
  - display inlineblock alighn centerで中央寄せしたことで常に中央に位置するように修正