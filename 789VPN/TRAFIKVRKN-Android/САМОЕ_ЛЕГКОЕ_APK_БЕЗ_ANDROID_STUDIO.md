# Самый лёгкий способ получить APK (без Android Studio)

Ты просил: «дай ZIP и чтобы сразу был готовый APK».
Я **не могу вложить готовый APK**, потому что APK нужно **собрать** (это делает сборщик Android).
Но я сделал ZIP, который собирает APK **сам на GitHub**, и тебе надо сделать **минимум кликов**.

## Что тебе нужно
- Только браузер (Chrome/Firefox)
- Аккаунт GitHub

## Шаги (максимально просто)

### 1) Создай репозиторий
- GitHub → кнопка **New** → Create repository

### 2) Загрузи файлы
- В репозитории: **Add file → Upload files**
- Загрузи папку **TRAFIKVRKN-Android/android/** (можно просто перетащить всю папку `android`)
- Нажми **Commit changes**

### 3) Нажми 2 кнопки — и APK соберётся
- Вкладка **Actions**
- Workflow: **Build Android APK (Debug)**
- Кнопка **Run workflow** → ещё раз **Run workflow**

### 4) Скачай APK
- Открой последний запуск (где зелёная галочка ✅)
- Пролистай вниз до **Artifacts**
- Скачай `TRAFIKVRKN-debug-apk`
- Внутри будет **app-debug.apk**

### 5) Установи на Redmi 12
- Перешли `app-debug.apk` на телефон
- Открой → Разреши установку “из неизвестных источников” (если спросит)

## Если нет вкладки Actions
Repo → Settings → Actions → General → включи разрешение на Actions (Allow all actions).
