потрібно зверстати це завдання по аналогії з попереднім завданням.

створити новий репозиторій на GitHub для цього завдання і робити регулярно коміти і пуші з коментарями що було додано в даному коміті

Вимоги:
- сайт по ширині ніколи не має виходити за межі екрану і не має скролитись в бік
- по висоті він має бути на весь екран, але може мати мінімальну висоту вказану наприклад 1000px. вертикальний скрол допускається.
- він повинен бути адапнивним для лептопу, планшету, і телефону
лептоп: ширина екрану 1024px і більше, планшет: 768рх - 1023рх, і телефон: до 767рх включно

хедер:
- елементи в хедері повинні звужуватись до поки це можливо для десктопу, для планшету лого (сірий квадрат з чорною рамкою має бути  на свому місці, а 3 оранжеві елементи дропнутись на новий рядок і бути трьом в одному рядку, а для телефону кожен елемент в хедері має бути з нового рядка і оранжеві елементи мають зайняти всю допустиму ширину кожен.
- лого розміру не має змінювати

середня секція:
- ці елементи мають для десктопу мають бути з певним інтервалом один від одного, інтервал має бути сталим, а ширина блоків (карток) має бути такою, щоб для екрану 1440рх вони влізли всі в 1 ряд але при тому їхня мінімальна ширина має бути до прикладу 250рх і при звуженні екрану вони мають дропатись на новий рядок
по аналогії з елементами хедеру мають бути адаптивними для мобільного телефону і встати кожна з нового рядку, і на всю ширину екрану, і мають мати тільки відступи одна від одної (горизонтальні)

футер
- абсолютно аналогічно
- в футері коричневі квадрати всі одинакові мають бути

- використовувати SCSS і всі кольори мають бути винесені як змінна, щоб кожного разу не хардколити колір, а використовувати змінні
- використовувати вкладеність в SCSS
- унікальні елементи стилізувати за айдішкою, назви айдішок і класів мають охарактеризовувати що це таке (наприклад .card, замість .red-block) в назвах класів і айдішок не має бути вказано колір елементу

детальніше з неймінгами можна почитати тут, і старатись слідувати цій методології: https://ru.bem.info/methodology/quick-start/

- юзати універвальні класи які надають якісь дефолтні параметри, наприклад падінги або флексбокси

- position: absolute можна юзати тільки для елементів, які вкзані в скріншоті absolute allowed.png

- використати flex-grow (є підказки в яких місцях)

- код повинен виглядати гарно, всі відступи мають бути дотримані

- не повинно бути описано класів або айдішок, які ніде не використовуються

- всі пункти мають бути дотримані

дедлайн понеділок 20 червня
