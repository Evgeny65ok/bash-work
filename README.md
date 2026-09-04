<img width="431" height="295" alt="Снимок экрана 2026-09-04 103556" src="https://github.com/user-attachments/assets/e65eacbd-4083-432b-80b3-a8277979c773" /><img width="695" height="262" alt="Снимок экрана 2026-09-04 102521" src="https://github.com/user-attachments/assets/58d1e180-483f-4aa2-8340-2d16aa9b7deb" /># Самостоятельная работа по командной строке Bash
**Выполнил:** Белевитин Евгений Александрович

---

## 📁 Структура проекта и команды автоматизации

В данном репозитории представлены выполненные задания по созданию файловой структуры с помощью команд Bash.

### 1. Блог (blog/)

**Схема структуры:**
```text
blog/
├── posts/
├── pages/
├── images/
├── css/
└── js/
```
![alt text](image-5.png)
**Bash-скрипт для создания:**
```bash
mkdir -p blog/{posts,pages,images,css,js}
```

---

### 2. Интернет-магазин (shop/)
![alt text](image-6.png)
**Схема структуры:**
```text
shop/
├── products/
│   ├── electronics/
│   └── clothing/
├── users/
│   └── profiles/
└── orders/
```

**Bash-скрипт для создания:**
```bash
mkdir -p shop/{products/{electronics,clothing},users/profiles,orders}
```

---

### 3. Веб-проект (webapp/)

**Схема структуры:**
```text
webapp/
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── logo.png
│   └── icons/
│       └── favicon.ico
├── pages/
│   └── about.html
└── index.html
```

**Bash-скрипт для создания:**
```bash
mkdir -p webapp/{css,js,images/icons,pages}
touch webapp/css/style.css webapp/js/script.js webapp/images/logo.png webapp/images/icons/favicon.ico webapp/pages/about.html webapp/index.html
```
![alt text](image-7.png)
---

### 4. Фреймворк (framework/)

**Схема структуры:**
```text
framework/
├── src/
│   ├── core/
│   │   ├── config/
│   │   │   └── settings.json
│   │   └── helpers/
│   │       └── utils.js
│   └── modules/
│       ├── auth/
│       │   └── login.js
│       └── api/
│           └── router.js
├── tests/
│   ├── unit/
│   └── integration/
├── docs/
└── .github/
    └── workflows/
        └── test.yml
```
!![alt text](image-8.png)
**Bash-скрипт для создания:**
```bash
mkdir -p framework/{src/{core/{config,helpers},modules/{auth,api}},tests/{unit,integration},docs,.github/workflows}
touch framework/src/core/config/settings.json framework/src/core/helpers/utils.js framework/src/modules/auth/login.js framework/src/modules/api/router.js framework/.github/workflows/test.yml
```

---

### 5. Проект X (project-x/)

**Схема структуры:**
```text
project-x/
├── src/
│   ├── app/
│   │   ├── controllers/
│   │   │   ├── user.js
│   │   │   └── product.js
│   │   └── models/
│   │       └── db.js
│   └── lib/
│       ├── helpers/
│       │   └── logger.js
│       └── config/
│           └── settings.js
├── tests/
│   ├── unit/
│   │   └── app.test.js
│   └── e2e/
│       └── flow.test.js
├── .env
├── Dockerfile
└── docker-compose.yml
```
![alt text](image-9.png)
**Bash-скрипт для создания:**
```bash
mkdir -p project-x/{src/{app/{controllers,models},lib/{helpers,config}},tests/{unit,e2e}}
touch project-x/src/app/controllers/{user.js,product.js} project-x/src/app/models/db.js project-x/src/lib/helpers/logger.js project-x/src/lib/config/settings.js project-x/tests/unit/app.test.js project-x/tests/e2e/flow.test.js project-x/{.env,Dockerfile,docker-compose.yml}
```
### 6 как в заметках

ГРУППА 1: Управление терминалом
<img width="695" height="262" alt="Снимок экрана 2026-09-04 102521" src="https://github.com/user-attachments/assets/8ea46fc5-c7c9-47f2-b6b3-12550fcb2655" />
history
<img width="610" height="670" alt="Снимок экрана 2026-09-04 102502" src="https://github.com/user-attachments/assets/3f9a328b-f48b-4d13-afe5-7a602825bea1" />

ГРУППА 2: Файловые операции
<img width="492" height="482" alt="Снимок экрана 2026-09-04 102555" src="https://github.com/user-attachments/assets/60cbb8a7-fde6-4068-a9ed-8d1a5b5265a7" />

ГРУППА 3: Создание и удаление
<img width="462" height="774" alt="Снимок экрана 2026-09-04 102710" src="https://github.com/user-attachments/assets/1045c29d-1ebc-4c8e-89ae-f6dd7291819f" />
<img width="533" height="901" alt="Снимок экрана 2026-09-04 102705" src="https://github.com/user-attachments/assets/fac7fdf6-0b38-4cbc-b907-c36b77b4ea2d" />
ГРУППА 4: Структура проекта (Brace Expansion)
<img width="372" height="377" alt="image" src="https://github.com/user-attachments/assets/90be94c6-591b-421c-a568-f66c837ff58d" />
ГРУППА 5: Копирование и перемещение

<img width="567" height="427" alt="image" src="https://github.com/user-attachments/assets/c44034e3-1077-4560-95a6-2e0d1fa968ac" />

ГРУППА 6: Системные команды (Linux)
<img width="428" height="213" alt="Снимок экрана 2026-09-04 103713" src="https://github.com/user-attachments/assets/9d13ceae-a942-40ce-941c-f4d3a7e99a6a" />


ГРУППА 8: Работа с файлами (продолжение)

<img width="431" height="295" alt="Снимок экрана 2026-09-04 103556" src="https://github.com/user-attachments/assets/9fc4c819-0d5d-42fa-89d4-b83f3214100a" />





---

## 🛠 Использованные команды

Основные команды, применённые в работе:
* `mkdir -p` — создание вложенных директорий без ошибок, если родительские папки ещё не существуют.
* `touch` — создание пустых файлов.
* `{,}` — раскрытие фигурных скобок (Brace Expansion) для массового создания папок и файлов одной строкой.

---

## 📦 Результат

Все структуры успешно созданы на локальной машине с помощью терминала Bash, проверены командой `tree` и загружены в удалённый репозиторий GitHub.
