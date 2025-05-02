<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>It-incubator precourse</title>
</head>
<body>
        <header>
        <span>IT-INCUBATOR</span>
    </header>
        <section data-cy = "hw1-section-about-pre">      
        <h1>Шкредов Егор Владимирович</h1>      
         <p>Работаю в IT-INCUBATOR-е. Люблю HTML,CSS и все , что связанно с frontend разработкой . </p>     
         <img src="./assest/img/img12.jpg" alt="img">
    </section>
    <section data-cy="hw1-section-about-pre">       
         <select name="gor" id="1">
            <option value="1">Minsk</option>
            <option value="2">Brest</option>
            <option value="3">Mogilev</option>
            <option value="4">Grodno</option>
            <option value="4">Vitebsk</option>
            <option value="4">Gomel</option>
         </select>
        <div data-cy="hw1-unordered-list-box-pre">
            <!-- 3) В этом разделе создай 2 дочерних элемента: -->
            <!-- a) Заголовок 2-го уровня (любимые книги/фильмы/блюда/страны... и т.п.) -->
             <h2>Любимые фреймворки</h2>
             <ul>
                <li>React</li>
                <li>Angular</li>
                <li>Vue</li>
             </ul>
            <!-- b) Маркированный список. В списке должно быть не менее 3-х элементов -->           
        </div>
        <div data-cy="hw1-ordered-list-box-pre">
            <!-- 3) В этом разделе создай 2 дочерних элемента: -->
            <!-- a) Заголовок 2-го уровня с другим названием (любимые книги/фильмы/блюда/страны... и т.п.) -->
             <h2>Любимые фильмы </h2>
            <!-- b) Нумерованный (упорядоченный) список. В списке должно быть не менее 3-х элементов -->
             <ol>
                <li>Побег из Шоушенка</li>
                <li>Зеленая миля</li>
                <li>Леон</li>
             </ol>
        </div>
        <div data-cy="hw1-skills-box-pre">
            <h2>Мои скиллы</h2>
            <!-- 4) Здесь создай несколько чекбоксов с подписью (не меньше 3-х). 
                - В подписи укажи названия любых тем по верстке (все, что знаешь или слышал). 
                - Каждый чекбокс должен быть связан со своей подписью. Для этого чекбокс должен находиться в элементе для подписи
                - Отметь "галочкой" (с помощью специального атрибута) темы, которые ты уже знаешь. -->
                <form>
                    <label>
                      <input type="checkbox" name="languages" value="HTML">
                       HTML
                    </label>                    
                    <label>
                      <input type="checkbox" name="languages" value="CSS">
                      CSS
                    </label>                    
                    <label>
                      <input type="checkbox" name="languages" value="JS">
                       Java Script
                    </label>
                    <label>
                      <input type="checkbox" name="languages" value="JS">
                       Jquery
                    </label>
                    <label>
                      <input type="checkbox" name="languages" value="JS">
                       React
                    </label>
                  </form>
        </div>
        <!-- 5) Создай здесь однострочное поле для ввода текста с подсказкой "Новый скилл", которая исчезает, когда начинаешь что-то печатать (для подсказки есть специальный атрибут) -->       
          <input type="1" form="erhngklojri"> 
        <!-- 6) Создай здесь кнопку “Добавить” -->
        <button>Добавить</button>
        <!-- 7) Добавь горизонтальную линию (для этого есть специальный тег) -->
        <hr>
        <table data-cy="hw-about-table-pre">
            <!-- 8) В таблице сделай 5 строк и 3 столбца. 
                        - В первой строке ячейки заголовков, в остальных обычные ячейки
                        - Добавь границы для всей таблицы с помощью специального атрибута border="". Он устарел, но работает
                        - В последнем ряду первая ячейка должна занимать 2 столбца (как должно выглядеть - смотри образец). Таблицу можно заполнять любыми данными -->                          
                        <table cellspacing="2" border="1" cellpadding="5" width="50%">
                            <thead >                              
                            <tr>
                                <th>п\п</th>
                                <th>Наименование</th>
                                <th>Количество</th>
                              </tr>
                            </thead>
                            <tbody>
                              <tr>
                                <td>1</td>
                                <td>Монитор</td>
                                <td>2</td>
                              </tr>
                              <tr>
                                <td>2</td>
                                <td>Клавиатура</td>
                                <td>1</td>
                              </tr>
                              <tr>
                                <td>3</td>
                                <td>Мышь</td>
                                <td>1</td>
                              </tr>
                            </tbody>                            
                            <tfoot>
                              <tr>
                                <td colspan="2">Итого</td>
                                <td>4</td>
                              </tr>
                            </tfoot>                         
        </table>
    </section>
    <footer data-cy="hw-footer-pre">
        <!-- 9) Создай здесь ссылку на наш сайт https://it-incubator.io/ (текст ссылки должен быть it-incubator) -->
         <p>
            <a href="https://it-incubator.io">https://it-incubator.io</a>
         </p>       
    </footer>
</body>
</html>
