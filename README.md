# goit-markup-hw-06

---

1. Cтвори репозиторій goit-markup-hw-06.

2. Склонуй створений репозиторій і скопіюй в нього файли попередньої роботи.

3. Додай розмітку і оформлення форм для сторінок макета домашнього завдання #6:

4. Налаштуй GitHub Pages і додай посилання на живу сторінку в шапку
   GitHub-репозиторія.

5. Критерії приймання роботи наставником

6. Проект

- «A1» Всі стилі написані в одному файлі styles.css, який знаходиться в папці
  css.

- «A2» Вихідний код відформатований за допомогою Prettier.

- «A3» Всі зображення та текстовий контент взяті з макета.

- «A4» На всіх HTML-сторінках підключений нормалізатор стилів modern-normalize.

- «A5» Код написаний з дотриманням настанови.

7. Розмітка

- «B1» Виконана HTML-розмітка всіх елементів макета.

- «B2» Теги використані відповідно до їх семантичного змісту.

- «B3» Виконана розмітка форми підписки на розсилання і всіх її елементів у
  футері.

- «B4» Виконана розмітка форми заявки та всіх її елементів в модальному вікні.

- «B5» У всіх інпутів у формах заданий атрибут name.

- «B6» Значення атрибута name описові, що точно характеризує, для чого це поле
  форми.

- «B7» У всіх інпутів є пов'язаний елемент label.

- «B8» Інпутам заданий атрибут placeholder, якщо для нього в макеті є
  текст-підказка.

- «B9» Кнопкам «відправлення» форм заданий атрибут type="submit".

- «B10» Всі нові іконки з форм додані в SVG-спрайт icons.svg.

8. Оформлення

- «C1» Виконано оформлення елементів форми підписки на розсилання у футері.

- «C2» Виконано оформлення елементів форми заявки у модальному вікні.

- «C3» При отриманні інпутом фокусу, його рамка та іконка змінюють колір (як
  показано на макеті).

- «C4» Оригінальний чекбокс про прийняття ліцензійної угоди у формі заявки
  прихований.

- «C5» Оформлення «чекбокса» про прийняття ліцензійної угоди зроблено вручну, за
  допомогою векторного зображення галочки з SVG-спрайту.

- «C6» Для всіх ефектів ховера і фокуса (колір, фон, тінь) зроблені переходи.
  час - 250ms, функція розподілу часу - cubic-bezier(0.4, 0, 0.2, 1).

---

9.

- Головний HTML-файл називається index.html

- У корені проекту є папка images з зображеннями.

- Всі стилі написані в одному файлі styles.css, який знаходиться в папці css.

- Скрипт підключений в HTML окремим файлом modal.js.

  - Вся твоя розмітка, включно з розміткою модалки

  - Ставимо перед закриваючим тегом body

  body script src="./js/modal.js" script body

---

10. CDN -
    https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css

---

11. .gitignore

---

.DS_Store

# Logs

logs _.log npm-debug.log_ yarn-debug.log* yarn-error.log* lerna-debug.log\*

# Diagnostic reports (https://nodejs.org/api/report.html)

report.[0-9]_.[0-9]_.[0-9]_.[0-9]_.json

# Runtime data

pids _.pid _.seed \*.pid.lock

# Directory for instrumented libs generated by jscoverage/JSCover

lib-cov

# Coverage directory used by tools like istanbul

coverage \*.lcov

# nyc test coverage

.nyc_output

# Grunt intermediate storage (https://gruntjs.com/creating-plugins#storing-task-files)

.grunt

# Bower dependency directory (https://bower.io/)

bower_components

# node-waf configuration

.lock-wscript

# Compiled binary addons (https://nodejs.org/api/addons.html)

build/Release

# Dependency directories

node_modules/ jspm_packages/

# TypeScript v1 declaration files

typings/

# TypeScript cache

\*.tsbuildinfo

# Optional npm cache directory

.npm

# Optional eslint cache

.eslintcache

# Microbundle cache

.rpt2_cache/ .rts2_cache_cjs/ .rts2_cache_es/ .rts2_cache_umd/

# Optional REPL history

.node_repl_history

# Output of 'npm pack'

\*.tgz

# Yarn Integrity file

.yarn-integrity

# dotenv environment variables file

.env .env.test

# parcel-bundler cache (https://parceljs.org/)

.cache

# Next.js build output

.next

# Nuxt.js build / generate output

.nuxt dist

# Gatsby files

.cache/

# Comment in the public line in if your project uses Gatsby and _not_ Next.js

# https://nextjs.org/blog/next-9-1#public-directory-support

# public

# vuepress build output

.vuepress/dist

# Serverless directories

.serverless/

# FuseBox cache

.fusebox/

# DynamoDB Local files

.dynamodb/

# TernJS port file

.tern-port

---

12. .prettierrc.json

---

{ "printWidth": 80, "tabWidth": 2, "useTabs": false, "semi": true,
"singleQuote": true, "trailingComma": "all", "bracketSpacing": true,
"jsxBracketSameLine": false, "arrowParens": "avoid", "proseWrap": "always" }

---

13. Для генерації SVG-спрайту використовуй сервіс Icomoon. - https://icomoon.io/

---

14. Для оптимізації створеного SVG-спрайту використовуй сервіс svgomg. -
    https://jakearchibald.github.io/svgomg/

---

15. Для оптимізації зображень використовуй сервіс squoosh. -
    https://squoosh.app/

---

16. Визуально скрыть элемент

position: absolute; width: 1px; height: 1px; margin: -1px; border: 0; padding:
0; clip: rect(0 0 0 0); overflow: hidden;

---

move to projects folder
