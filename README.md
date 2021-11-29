<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MinYee</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script>
        $(document).ready(function () {

            $("#btn1").click(function () {
                $("#div1").hide(1500);
            });
        });
    </script>
</head>

<body>
    <h1>DORAEMON</h1>
    <h1 class="heading" style="color: rgb(219, 168, 168)" onclick="alert('你點選了h1標籤')">
        介紹
    </h1>
    <p>
        哆啦A夢原本是黃色的，只是因為哭鬧掉漆，而變成藍色，但是哆啦A夢在還沒上漆之前是 黃色的。 他的頭上本來有一雙耳朵，但是在睡覺時被機器老鼠咬了。
    </p>

    <h1 class="heading" style="color: rgb(139, 140, 231)" onclick="alert('你點選了傳播途徑')">
        寓意
    </h1>

    <p>來自未來的哆啦A夢，為了滿足大雄的夢想和願望，拿出未來道具幫助大雄，但常常會引發騷動，大雄、胖虎、小夫等人過度依賴未來科學技術的結果，經常在最後會引起不好的效果，這種常出現的結局，被認為是作者想要在作品中傳達「雖然文明進步，但最重要還是使用的人」之思想。
    </p>
    <br>
    <div>
        <button id="btn1">Hide 哆啦A夢</button>
        <div id="div1">
            <img class="smaller-image thin-red-border"
                src="data:image/png;base64,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">
        </div>

</body>

</html>
