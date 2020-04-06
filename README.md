## Проектная работа № 12 Яндекс.Практикум

Работа посвящена использованию инструментов webpack для организации кода веб-сайта, веб-приложения. В качестве сайта используются наработки проектной работы № 9, в которой создавалась страница с карточками, функционалом просомтра, установки/снятия лайка, подсчета количества лайков, возможности удаления только собственных карточек.

Перед началом В целях выполнения задания исходные файлы были скачаны со страницы проектной работы. На сайте GitHub.com в профиле Tatiana81 создан репозиторий Осуществлено клонирование средствами сайта GitHub.com

Предустановки (что было установлено на локальный компьютер) Во-первых, для корректной работы, выполнения команд был установлен GitHub Desktop Во-вторых, установлен пакет npm В-третьих, свободно распространяемый редактор кода Visual Studio Code После успешного клонирования в рабочей папке GitHub на локальном компьютере создастся каталог с названием репозитория. Копируем в эту папку скачанные файлы сайта

### Структура проекта

./src/index.html

./src – папка с файлами проекта

./src/blocks – папка, содержащая структуру папок и файлов стилей в соответствии со спецификацией БЭМ

./src/images – папка с изображениями

./src/js – папка с файлами скриптов javascript

./src/pages – папка с файлом index.css (основной файл стилей)

./src/vendor – папка с файлами шрифтов

./images – папка с изображениями для build сборки


### Этапы установки

1. Клонировать репозиторий 

    git clone https://github.com/Tatiana81/YP-project-11.git

2. Установить пакеты, указанные в разделе Используемые пакеты, с помощью npm install

3. В зависимости от решаемой задачи

        a. Запустить веб-сервер разработчика командой npm run dev для визуального контроля изменений.

        b. Запустить сборку проекта командой npm run build

        c. Разместить проект gh-pages командой npm run deploy


### Конфигурационные файлы проекта:

    webpack.config.js содержит правила обработки файлов js, css, файлов изображений и шрифтов

    package.json – общие настройки npm, включая скрипты запуска, точку входа, установленные модули.

    babel.config.js – настройка поддержки javascript браузерами

    postcss.config.js - настройка поддержки css браузерами

    .nojekyll – обеспечение совместимости со структурой проекта, выполненной в соответствии с спецификацией БЭМ

### Используемые модули
    @babel/cli: 7.8.4
    @babel/core: 7.9.0
    @babel/preset-env: 7.9.0
    babel-loader: 8.1.0
    css-loader: 3.4.2, 
    exports-loader: 0.7.0, 
    file-loader: 6.0.0, 
    gh-pages: 2.2.0, 
    html-webpack-plugin: 3.2.0, 
    image-webpack-loader: 6.0.0, 
    imports-loader": 0.8.0, 
    mini-css-extract-plugin: 0.9.0, 
    optimize-css-assets-webpack-plugin: 5.0.3, 
    postcss-import": 12.0.1, 
    postcss-loader": 3.0.0, 
    postcss-preset-env: 6.7.0, 
    style-loader: 1.1.3, 
    svg-inline-loader: 0.8.2, 
    webpack: 4.42.0, 
    webpack-cli: 3.3.11, 
    webpack-dev-server: 3.10.3, 
    webpack-md5-hash: 0.0.6

#### Версия: 1.0.0

### Ссылка на адрес страницы: https://tatiana81.github.io/YP-project-11/

### Автор: Суроева Татьяна
