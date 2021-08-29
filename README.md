
<!DOCTYPE html>
<html>
<head>
	<title>button strip</title>
	<link rel="stylesheet" href="loading strip.css">
  <style>
  *{
    box-sizing: inherit;
}
html,body{
    min-height: 100%;
    width: 100%;
    justify-content: center;
    align-items: center;
    display: flex;
}
body{
    background: #4c5870;
}
.btn {
    width: 810px;
    height: 30px;
    font-size: 25px;
    font-family: consolas;
    font-weight: 800;
    letter-spacing: 1px;
    /*text-transform: uppercase;*/
    text-align: center;
    color: #fff;
    background-size: 50px 50px;
    border: 0;
    border-radius: 50px;
    outline: none;
    overflow: hidden;
    transition: 0.8s;
    text-shadow: 3px 1px 5px #333;
    animation: strip 10s linear infinite;
}/*
.btn:hover {
    text-shadow: 3px 1px 5px #333;
    color: #ffffff;
    animation: strip 6s linear infinite;
    transition: 0.8s;
}*/
@keyframes strip {
    0% { background-position: 0% 0% }
    50% { background-position: 50% 0% }
    100% { background-position: 100% 0% }
}
button.one{
    /*background-image: linear-gradient(45deg, #5bd1d7 16.67%, #ff502f 16.67%, #ff502f 33.33%, #348498 33.33%, #348498 50%, #5bd1d7 50%, #5bd1d7 66.67%, #ff502f 66.67%, #ff502f 83.33%, #348498 83.33%, #348498 100%);*/

    /*background-image: linear-gradient(45deg, #05445c 16.67%, #5c4f74 16.67%, #5c4f74 33.33%, #f2317f 33.33%, #f2317f 50%, #05445c 50%, #05445c 66.67%, #5c4f74 66.67%, #5c4f74 83.33%, #f2317f 83.33%, #f2317f 100%);*/

    background-image: linear-gradient(45deg, #08D9D6 16.67%, #252A34 16.67%, #252A34 33.33%, #FF2E63 33.33%, #FF2E63 50%, #08D9D6 50%, #08D9D6 66.67%, #252A34 66.67%, #252A34 83.33%, #FF2E63 83.33%, #FF2E63 100%);
}
/*
button.two{
    background-image: linear-gradient(45deg, #42218E 16.67%, #F54EA2 16.67%, #F54EA2 33.33%, #7B3B8C 33.33%, #7B3B8C 50%, #42218E 50%, #42218E 66.67%, #F54EA2 66.67%, #F54EA2 83.33%, #7B3B8C 83.33%, #7B3B8C 100%);
}
  </style>
</head>

<body>
	<button class="btn one">Loading......</button>
</body>

</html>
