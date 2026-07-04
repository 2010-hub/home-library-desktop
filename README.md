# Home Library Desktop
Приложение для каталогизации домашней библиотеки. Также у нас есть [**версия для сервера**](https://github.com/2010-hub/home-library-app) (она позволяет пользователям работать через интернет в веб-версии. В ней больше функций) <!-- описание репозитория -->
<!--Блок информации о репозитории в бейджах-->
![Static Badge](https://img.shields.io/badge/by-SerpentBot_Laboratory-purple?logo=github)
![GitHub top language](https://img.shields.io/github/languages/top/2010-hub/home-library-app)
![GitHub](https://img.shields.io/github/license/2010-hub/home-library-desktop)
![GitHub Repo stars](https://img.shields.io/github/stars/2010-hub/home-library-desktop)
![GitHub issues](https://img.shields.io/github/issues/2010-hub/home-library-desktop)

<!--Пользовательская документация-->
## Документация

### 📚 Управление книгами
-  Добавление книг с обложкой (загрузка изображений)
-  Редактирование и удаление книг
-  Автоматический поиск по ISBN (Google Books API) (функция находится в разработке)
-  Поля: название, автор, ISBN, жанр, серия, издательство, год издания, кол-во страниц, место хранения, ссылка на электронную версию

### 🖼️ 3 режима просмотра каталога
| Режим | Описание |
|-------|----------|
|  **Карточки** | Визуальный просмотр с обложками |
|  **Таблица** | Все данные в виде таблицы |
|  **Галерея** | Крупные обложки для быстрого поиска (видно только название и обложка) |

### 🔎 Поиск и сортировка
- Поиск по названию, автору, ISBN, жанру, серии, издательству, месту хранения
- Сортировка по любому полю (по возрастанию/убыванию)

### ⚙️ Настройки
- Изменение названия библиотеки
- Выбор темы оформления (светлая/тёмная)
- Настройка количества книг на странице
- Экспорт данных (JSON/CSV)
- Импорт данных из бэкапа

### 🔒 Безопасность
- Данные хранятся в JSON файлах
- Простая установка

<!--Установка-->
## Установка
У вас должны быть установлены [**зависимости проекта**](https://github.com/2010-hub/home-library-desktop#зависимости)

**1. Скачайте приложение**

Скачайте необходимый для Вас [**релиз приложения**](https://github.com/2010-hub/home-library-desktop/releases). В каждом обновлении есть **Установщик приложения** (требует установки на ПК), **portable версия** (работает без установки на ПК) и **ZIP архив** (необходимо распаковать в нужной папке) для Windows, а так же другие форматы файлов для Linux.

**2. Привязка папки**

Откройте приложение. Появится окно с выбором папки. Если Вы хотите использовать синхронизацию через Google drive, выберите папку **Library** (подробнее смотреть в [**зависимости проекта**](https://github.com/2010-hub/home-library-desktop#зависимости)). Если Вы работаете локально, перейдите в папку **Документы** и создайте там папку **Library**. Выбереите её в приложении.

**3. Готово!**

После этого откроется само приложение. Вам открываются все возможности программы. Теперь вы можете удобно создавать и каталогизировать свою домашнюю библиотеку. 

<!--Поддержка-->
## Поддержка
Если у вас возникли сложности или вопросы по использованию приложения, создайте 
[**обсуждение**](https://github.com/2010-hub/home-library-desktop/issues/new/choose) в данном репозитории или напишите нам в сообщения канала в [**Telegram**](https://t.me/Serpent_lab).

<!--зависимости-->
## Зависимости
Эта программа позволяет Вам синхронизировать данные библиотеки с помощью **Google Drive Desktop**. Ниже представлен гайд по установке Google Drive Desktop. Если Вы хотите работать локально, пропустите эту инструкцию.

**1. Установка Google Drive Desktop**
   
Перейдите на [**официальный сайт**](https://support.google.com/a/users/answer/13022292?hl=en) и скачайте нужную версию. Установите её.

**2. Войдите в аккаунт**
   
Для продолжения Вам необходимо войти в свой Google акктаунт в приложении Google Drive Desktop

**3. Создание папки**
   
Создайте папку **Library** на Google Drive (или любую другую по своему усмотрению)

## Скриншоты
![Скриншот 1](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_BOe4B00Imx.jpg)
![Скриншот 2](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_TQVYlye5nl.jpg)
![Скриншот 3](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_WRkHAVb1ws.jpg)
![Скриншот 4](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_Z8HVltYRi0.jpg)
![Скриншот 5](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_N055wqmpCe.jpg)
![Скриншот 6](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_pKBKOytjgI.jpg)
![Скриншот 7](https://github.com/2010-hub/home-library-desktop/blob/f893e0f068caf8dd07d7548611387a5678f1c80a/images/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D1%8F%D1%8F_%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0_osNVW1PEhu.jpg)

