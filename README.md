<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
    box-sizing: border-box;
}

/* Add a gray background color with some padding */
body {
    font-family: Arial;
    padding: 20px;
    background: #f1f1f1;
}

/* Header/Blog Title */
.header {
    padding: 30px;
    font-size: 40px;
    text-align: center;
    background: white;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
    float: left;
    width: 75%;
}

/* Right column */
.rightcolumn {
    float: left;
    width: 25%;
    padding-left: 20px;
}

/* Fake image */
.fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 20px;
}

/* Add a card effect for articles */
.card {
     background-color: white;
     padding: 20px;
     margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Footer */
.footer {
    padding: 20px;
    text-align: center;
    background: #ddd;
    margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
    .leftcolumn, .rightcolumn {   
        width: 100%;
        padding: 0;
    }
}
</style>
</head>
<body>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Список тем задачника Кудрявцева</h2>
      <h3>1. Выход есть</h3>
      <p>1. Множества <br>
     2. Операции над множествами <br>
    3. Эквивалентные и неэквивалентные множества <br>
    4. Упорядоченные множества <br>
    5. Размещения и перестановки <br>
    6. Сочетания<br>
    7. Случайные события и их вероятности</p>
    <h3>2. Выхода нет</h3>
      <p>1. Множества <br>
     2. Операции над множествами <br>
    3. Эквивалентные и неэквивалентные множества <br>
    4. Упорядоченные множества <br>
    5. Размещения и перестановки <br>
    6. Сочетания<br>
    7. Случайные события и их вероятности</p>
    </div>
  </div>



  <div class="rightcolumn">
    <div class="card">
      <h2>О себе:</h2>
      <p>Уже сказать и нечего</p>
    </div>
    <div class="card">
      <h3>Контакты: </h3>
      <p>Место для ссылок</p>
    </div>
  </div>



</div>

<div class="footer">
  <h5>Мог бы решать мат. анализ...</h5>
</div>

</body>
</html>



