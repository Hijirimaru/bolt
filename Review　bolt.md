# section11 bolt(PC)
## 全体

1. 画像の下の隙間は埋める
  - 画像の下の隙間をvertical-align:bottomで解消

2. タイトルはは専用のタグで
  - 見出しをhタグに変更

3. スキルセクションとSNSはリストのタグで
  - スキルとSNSのタグをliタグを使った書き方に修正

4. aタグのheight１００％消してdisplay:inlineblockに
  - aタグにdisplay:inlineblockをつけて親要素と大きさが揃うように修正

5. paddingは一行でかく
  - ２行に分けて書いていたpaddingを１行に

6. sectionのアイフォーンをdivでくくる
  - iPhone画像と隣のテキストがいい割合で横並びするよう調整。widthが４０％：６０％に。

7. articlebox nthchild書き方スマートに。4nは不適切な関数
  - nthchildをコンマで並べることで一つにまとめる
  - margin-left:0が3n+1番目ごとに適用されるように修正

8. ホバーで黒字になるクラスは,で区切ってまとめられる
  - ホバーで黒字になるという同じ内容のmailとcontactのクラスを一箇所にまとめる

9. SNSでheightいらない
  - SNSアイコンの位置をpaddingで中央寄せを表現