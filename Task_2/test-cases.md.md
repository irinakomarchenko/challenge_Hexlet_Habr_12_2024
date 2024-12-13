﻿**Задание 2. Сценарий тестирования для страницы https://ibs.ru/career/jobs/, ĸоторая отображает списоĸ ваĸансий ĸомпании.**

<table><tr><th valign="top"><b>ID</b></th><th valign="top"><b>Название теста</b></th><th valign="top"><b>Шаги воспроизведения</b></th><th valign="top"><b>Ожидаемый результат</b></th></tr>
<tr><td rowspan="2" valign="top">TC1</td><td rowspan="2" valign="top">Отображение списĸа ваĸансий_Отображение вакансий</td><td rowspan="2" valign="top"><p>Предусловие:</p><p>` `Открыта страница <https://ibs.ru/career/jobs/></p><p></p><p>Шаги:</p><p>1. Запомните количество доступных вакансий.</p><p>2. Введите в поиск название вакансии (например, тестировщик).</p><p>3. Проверьте, что вакансия существует.</p></td><td rowspan="2" valign="top"><p>1. Данные собраны.</p><p>2. Отображается вспомогательное меню с выбором вакансии.</p><p>3. Вакансии из данной области отсортированы по умолчанию.</p></td></tr>
<tr></tr>
<tr><td rowspan="2" valign="top">TC2</td><td rowspan="2" valign="top">Отображение списка вакансий_Проверка отображения полного списка вакансий</td><td rowspan="2" valign="top"><p>Предусловия:</p><p>Список вакансий предлагает подборку вакансий, сгруппированных по категориям.</p><p></p><p>Шаги:</p><p>1\. Нажмите кнопку "Показать еще".</p><p>2\. Нажмите кнопку "Назад".</p></td><td rowspan="2" valign="top"><p>1. Переход к раскрывающемуся списку вакансий.</p><p>2. Переход на предыдущую страницу вакансий.</p></td></tr>
<tr></tr>
<tr><td valign="top">TC3</td><td valign="top">Отображение списка вакансий_Проверка корректности данных вакансии</td><td valign="top"><p>Предусловия:</p><p>Пользователь открывает карточку вакансии.</p><p></p><p>Шаги:</p><p>1\. Проверьте данные вакансии на странице (название, описание, контактная информация).</p></td><td valign="top">1. Все данные совпадают с указанными на детальной странице вакансии.</td></tr>
<tr><td rowspan="2" valign="top">TC4</td><td rowspan="2" valign="top">Работа фильтров_Фильтрация по местоположению</td><td rowspan="2" valign="top"><p>Предусловие:</p><p>` `Открыта страница <https://ibs.ru/career/jobs/></p><p></p><p>Шаги:</p><p>1\. Нажмите на фильтр "Город".</p><p>2\. Выберите конкретное местоположение (например, Омск).</p></td><td rowspan="2" valign="top"><p>1. Появляется выпадающее меню с доступными городами.</p><p>2. Отображаются только вакансии из Омска и области.</p></td></tr>
<tr></tr>
<tr><td rowspan="2" valign="top">TC5</td><td rowspan="2" valign="top">Работа фильтров_Фильтрация по типу вакансии</td><td rowspan="2" valign="top"><p>Предусловие:</p><p>` `Открыта страница <https://ibs.ru/career/jobs/></p><p></p><p>Шаги:</p><p>1\. Выберите на фильтр "Направление".</p><p>2\. Выберите направление.</p></td><td rowspan="2" valign="top"><p>1. Появляется выпадающее меню с типами вакансий (например, Разработка, Архитектура ).</p><p>2. Отображаются только вакансии с выбранным направлением.</p></td></tr>
<tr></tr>
<tr><td valign="top">TC6</td><td valign="top">Работа фильтров_Совмещенные фильтры</td><td valign="top"><p>Предусловие:</p><p>` `Открыта страница <https://ibs.ru/career/jobs/></p><p></p><p>Шаги:</p><p>1\. Примените несколько фильтров (например, "Город = Москва", "Тип вакансии = Полная занятость").</p></td><td valign="top">1. Страница отображает только вакансии, которые соответствуют всем выбранным фильтрам.</td></tr>
<tr><td valign="top">TC7</td><td valign="top">Работа фильтров_Крайний случай: пустой выбор фильтра</td><td valign="top"><p>Предусловия:</p><p>Пользователь активирует фильтр без указания критериев.</p><p></p><p>Шаги:</p><p>1\. Очистите все фильтры и оставьте их невыбранными.</p></td><td valign="top">1. Страница отображает все вакансии без каких-либо фильтров.</td></tr>
<tr><td rowspan="2" valign="top">TC8</td><td rowspan="2" valign="top">Поисĸ ваĸансий_Обратная связь</td><td rowspan="2" valign="top"><p>Предусловие:</p><p>Подходящих вакансий в системе нет.</p><p></p><p>Шаги:</p><p>1\. Заполнить форму для обратной связи.</p><p>2\. Отправить данные.</p></td><td rowspan="2" valign="top"><p>1. Успешно.</p><p>2. Форма загружена на сайте.</p></td></tr>
<tr></tr>
<tr><td valign="top">TC9</td><td valign="top">Поиск вакансий_Крайний случай: специальные символы в поиске</td><td valign="top"><p>Предусловия:</p><p>` `Открыта страница <https://ibs.ru/career/jobs/></p><p></p><p>Шаги:</p><p>1\. Введите специальные символы (например, "+", "#") в строку поиска.</p></td><td valign="top">1. Поиск обрабатывает специальные символы, возвращая соответствующие результаты или сообщение об отсутствии совпадений.</td></tr>
<tr><td valign="top">TC10</td><td valign="top">Поиск вакансий_Автозавершение поиска</td><td valign="top"><p>Предусловия:</p><p>Пользователь вводит первые буквы запроса в строку поиска.</p><p></p><p>Шаги:</p><p>1\. Начните вводить ключевое слово в строку поиска.</p></td><td valign="top">1. Появляется список предлагаемых результатов.</td></tr>
<tr><td valign="top">TC11</td><td valign="top">Поиск вакансий_История поиска</td><td valign="top"><p>Предусловия:</p><p>Пользователь совершал поисковые запросы в рамках текущей сессии.</p><p></p><p>Шаги:</p><p>1\. Выполните поиск.</p></td><td valign="top">1. Ранее введенные ключевые слова сохраняются в истории поиска.</td></tr>
<tr><td valign="top">TC12</td><td valign="top">Адаптивность_Проверка языка страницы</td><td valign="top"><p>Предусловия:</p><p>Система пользователя настроена на определенный язык.</p><p></p><p>Шаги:</p><p>1\. Измените язык интерфейса (например, английским).</p></td><td valign="top">1. Страница перезагружается с измененным языком .</td></tr>
<tr><td rowspan="3" valign="top"><p>TC13</p><p></p></td><td rowspan="3" valign="top"><p>Кнопки и ссылки_</p><p>Проверка ссылок</p></td><td rowspan="3" valign="top"><p>Предусловие:</p><p>Подходящих вакансий в системе нет</p><p></p><p>Шаги:</p><p>1\. Нажмите на название любой вакансии.</p></td><td rowspan="3" valign="top">1. Пользователь перенаправляется на страницу с подробным описанием вакансии.</td></tr>
<tr></tr>
<tr></tr>
<tr><td rowspan="2" valign="top"><p></p><p>TC14</p></td><td rowspan="2" valign="top">Кнопки и ссылки_Валидация обязательных полей в форме заявки</td><td rowspan="2" valign="top"><p>Предусловия:</p><p>Пользователь заполняет форму заявки на вакансию и оставляет одно или несколько полей пустыми.</p><p></p><p>Шаги:</p><p>1\. Нажмите на "Откликнуться" дважды.</p><p>2\. Оставьте обязательные поля пустыми и попробуйте отправить заявку.</p></td><td rowspan="2" valign="top"><p>1. Появляется форма заявки.</p><p>2. Появляется предупреждение об обязательности заполнения полей.</p></td></tr>
<tr></tr>
<tr><td rowspan="2" valign="top">TC15</td><td rowspan="2" valign="top">Кнопки и ссылки_Сохранение вакансии в избранное</td><td rowspan="2" valign="top"><p>Предусловия:</p><p>Пользователь авторизован и просматривает список вакансий.</p><p></p><p>Шаги:</p><p></p><p>1\. Нажмите кнопку "Добавить в избранное" для вакансии.</p><p>2\. Перейдите в "Избранное".</p></td><td rowspan="2" valign="top"><p>1. Вакансия добавляется в список избранных.</p><p>2. Добавленная вакансия отображается в списке.</p></td></tr>
<tr></tr>
<tr><td rowspan="2" valign="top">TC16</td><td rowspan="2" valign="top">Производительность_Производительность загрузки</td><td rowspan="2" valign="top"><p>Предусловия:</p><p>Перейти на страницу вакансий с установленным таймером анализа производительности.</p><p></p><p>Шаги:</p><p>1\. Откройте страницу https://ibs.ru/career/jobs/.</p><p>2\. Примените фильтры и выполните поиск.</p></td><td rowspan="2" valign="top"><p>1. Страница загружается в течение 2 секунд при нормальных сетевых условиях.</p><p>2. Отфильтрованные или искомые результаты загружаются в течение 1 секунды.</p></td></tr>
<tr></tr>
</table>







