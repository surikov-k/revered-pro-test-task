# Тестовое задание Reverend Pro

Задача сверстать [этот небольшой макет](https://www.figma.com/file/1Wj6SMM7qcooEq31CE5jcn/Test-TASK?type=design&node-id=0%3A1&mode=dev): 

1. Сверстать адаптивно. Макетов для мобильных устройств нет. Нужно сверстать на свое усмотрение, но должно все отображаться красиво, читабельно, понятно для конечного пользователя
2. Верстка должна быть кроссбраузерной
3. Использовать минимум html, больше выносить в css (например, не прописывать класс d-flex в html к каждому flex элементу, а добавлять это свойство через css).
4. Использовать Sass или Scss. И собирать проект через какой-либо сборщик
5. Результат работы залить в гитхаб и прислать ссылку на репозиторий. В репозиторий должны попасть файлы как исходники, так и скомпилированный результат
6. Засечь сколько времени в часах (примерно) у Вас ушло на верстку с начала до полной готовности. (не пытайтесь преувеличить или преуменьшить время, это не приведет к желаемому результату. Лучше писать реальное время, не боятся отказа).
7. Все элементы на которые можно кликнуть (хотябы потенциально) должны иметь :hover эффекты на ваше усмотрение.

### Логику, которую нужно реализовать:
1. Когда страница только загружается, тарифов (блоки с ценами) не видно. Они появляются плавно один за другим после загрузки страницы.
2. Если нажать на значок $ в любом из тарифов, то значок меняется на ₽ и цены показываются в рублях. Если нажать повторно на ₽, то значок поменяется на евро и цены тоже.
   Причем смена значков и цен должна быть сразу для всех 3х тарифов, а не только для того, где нажали. Сами цены можете подставить какие хотите, например, по текущему курсу (окгрулить до целых чисел). Это не принципеально.
3. Если нажать на слово Month в тарифах, то оно меняется на Day. И цены показываются исходя из расчета: цена за месяц / 30 (округляем до целого). Так же меняется цена/слово сразу на всех тарифах одновременно.
   Таким образом можно посмотреть сколько стоит тариф в рублях в день. Или в евро за месяц. И т.п.
