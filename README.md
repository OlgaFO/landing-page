# Лендинг

## Перед стартом проекта необходимо:

* Убедиться, что установлены node.js и npm, для этого достаточно в терминале написать:
> node -v
>
> npm -v

* Убедиться, что установлен gulp 4, для этого достаточно в терминале написать:
> gulp -v

* Если установлена более поздняя версия, то выполнить следующие действия:
> Uninstall previous Gulp installation and related packages, if any
>
> $ npm rm gulp -g
>
> $ npm rm gulp-cli -g
>
> $ cd [your-project-dir/]
>
> $ npm rm gulp --save-dev
>
> $ npm rm gulp --save
>
> $ npm rm gulp --save-optional
>
> $ npm cache clean
>
> Install the latest Gulp CLI tools globally
>
> $ npm install gulpjs/gulp-cli -g
>
> Install Gulp 4 into your project from 4.0 GitHub branch as dev dependency
>
> $ npm install gulpjs/gulp#4.0 --save-dev
>
> Check the versions installed. Make sure your versions are not lower than shown.
>
> $ gulp -v

## Инструкция для старта проекта:

* Склонировать данный репозиторий
> git clone https://github.com/OlgaFO/landing-page.git

* Запустить команду npm install в терминале (данная команда устанавливает все пакеты, которые указаны в файле package.json, а также все их зависимости).
