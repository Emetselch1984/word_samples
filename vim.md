#vimコマンド集
###行の入れ替え
###行のコピー
###単語をコピーして、単語を削除して貼り付け
###カーソルから指定した文字まで削除
###直前の変更、ジャンプス前の場所、ページの先頭、最後に移動
###単語の削除
###カーソルを中央に移動,ウィンドウ上、ウィンドウ下
###選択した範囲を連結
###短形選択して挿入
```
dd p
yy p
yiw w ve P
dt {char}
'. '' gg GG
daw
zz H L
J
半角なし
gJ
control + v d u i
```
##画面の移動
```
gg
GG
ctrl + b
ctrl + f
w
b
^
$
f + "string"
%
```
##置換
```
:s/Alice/Bob/
:%s/Bob/Carol/g
:s/Carol/Alice
:s/Carol/Bob
```
##ウィンドウの分割
```
:sp
:vs
```
##タブの切り替え
```
:tannew
:tabclose
gt
```
