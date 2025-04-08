<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/font.css">
    <title>기초종합실습</title>
    <style>
        body{
            font-family: "Noto Sans KR", sans-serif;
        }
        #wrap{
            width: 960px;
            margin: 0 auto;
            border: 1px solid #000;
            padding: 10px;
        }
        h1{
            width: 160px;
        }
        h1 img {
            width: 100%;
        }
        table, tr, td{
            border: 1px solid #000;
            border-collapse: collapse;
        }
        table{
            width: 600px;
        }
        td{
            padding: 15px;
        }
    </style>
</head>
<body>
    <div id="wrap">
        <header>
            <h1><img src="./images/jenny.png" alt="사람"></h1>
        </header>
        <main>
            <section>
                <h2>웹 개발자 MCSSAM</h2>
                <p>
                    indopop@naver.com
                </p>
                <p>
                    훈련교사 재직중
                </p>
            </section>
            <section>
                <h2>SNS</h2>
                <ul>
                    <li><a href="#">facebook</a></li>
                    <li><a href="#">Youtube</a></li>
                    <li><a href="#">Pinterest</a></li>
                    <li><a href="#">Twitter</a></li>
                </ul>
            </section>
            <hr>
            <section>
                <h2>Skills</h2>
                <ul>
                    <li>사용언어
                        <ul>
                            <li><mark>HTML</mark></li>
                            <li><mark>CSS</mark></li>
                            <li>javascript</li>
                            <li>jQiery</li>
                        </ul>
                   </li>
                    <li>사용툴
                        <ul>
                            <li><span>VS CODE</span></li>
                            <li>eclipse</li>
                            <li><span>SQL Developer</span></li>
                        </ul>
                    </li>
                </ul>
            </section>
            <section>
                <h2>Academin</h2>
                <table>
                    <tr>
                        <td>출신학교</td>
                        <td>전공</td>
                        <td>기간</td>
                        <td>졸업구분</td>
                    </tr>
                    <tr>
                        <td>이젠 고등학교</td>
                        <td>해당사항없음</td>
                        <td>2020.01.01</td>
                        <td>졸업</td>
                    </tr>
                    <tr>
                        <td>이젠 고등학교</td>
                        <td>컴퓨터 공학</td>
                        <td>2023.01.01</td>
                        <td>졸업</td>
                    </tr>
                </table>
            </section>
        </main>
        <hr>
        <footer>
            <p>
                COPYRIGHT &copy; ALL RIGHTS RESERVED.
            </p>
        </footer>
    </div>
</body>
</html>
