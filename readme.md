## Bootstrap5でレスポンシブなウェブサイトを作ってみよう
https://www.youtube.com/watch?v=8u-nhouM9cw

## index.html
! の補完で、初期設定を展開

## Bootstrap Hp
https://getbootstrap.jp/docs/5.0/getting-started/introduction/

## スタイルシートの準備
CSS
スタイルシート <link> をコピーして、他のスタイルシートの前にある <head> に貼り付けて、CSS を読み込みます。
`html
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
`

link.cssの自動補完で、
｀html
<link rel="stylesheet" href="style.css">
`

## navbarを以下からbodyに貼り付ける
https://getbootstrap.jp/docs/5.0/components/navbar/

###  fluidを外す
fluidは、画面サイズが小さくなってもそのままの形を保持する。はずすと、調整してくれるようになる
<div class="container-fluid">　　⇒　<div class="container">

## navbarのメニューを右側に寄せたいとき
           <ul class="navbar-nav ms-auto mb-2 mb-lg-0">　　ms-auto指定にする
