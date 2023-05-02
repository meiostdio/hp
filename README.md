# hp

タグについて

* 記事タイトル見出しはh1, それ以外の見出しはh2-4
* 段落はできるだけ<p></p>で囲んだらのちのち助かるかもしれない
* プログラムのコードは<pre class="prettyprint"></pre>で挟む　要テンプレ参照
* <pre>タグでは<br>で改行しなくても、テキストのかたちがそのまま反映されます
* 引用するときは<blockquote></blockquote>で囲むとよい
* 空白の改行を打ちたい場合は<dd></dd>と打つ　なにも挟まない


以下テンプレート

<!DOCTYPE html>
<html lang="ja">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Zen+Kaku+Gothic+New:wght@300&display=swap" rel="stylesheet">



    <title>記事タイトル</title>



</head>

<body>
    <div class="wrapper">
        <div class="wh">
            <div class="head">
                <a href="../index.html">
                    <div class="rabel">MEIO STDIO</div>
                </a>
                <div class="dummy"></div>
            </div>


            <div class="article">
                <h1>記事タイトル</h1>
                <p>

                </p>
                <h2>見出し</h2>
                <p>
                    
                </p>

                <pre class="prettyprint">
System.out.println("hello");
</pre>









                <dd></dd>
                <dd></dd>
                <dd></dd>
            </div>
        </div>



    </div>



    <script src="https://cdn.jsdelivr.net/gh/google/code-prettify@master/loader/run_prettify.js?skin=desert"></script>

</body>

</html>
