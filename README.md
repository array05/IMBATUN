<div align="center">
  <img src="https://raw.githubusercontent.com/array05/IMBATUN/main/icon.png" width="96" height="96" alt="IMBATUN">
  <h1>IMBATUN</h1>
  <p><strong>VPN там, где нужен. Игры — напрямую.</strong></p>
  <p>Discord, Telegram, YouTube и зарубежные сервисы через VPN.<br>Российские сайты и распознанные игры — через обычное подключение.</p>
  <p>
    <img src="https://img.shields.io/badge/Windows-10%20%2F%2011%20%C2%B7%20x64-7de8c2?style=flat-square" alt="Windows 10 и 11, x64">
    <a href="https://github.com/array05/IMBATUN/releases/latest"><img src="https://img.shields.io/github/v/release/array05/IMBATUN?style=flat-square&color=b696ff&label=release" alt="Последняя версия"></a>
    <a href="https://t.me/imbavpn_bot"><img src="https://img.shields.io/badge/Telegram-IMBA%20VPN-7de8c2?style=flat-square" alt="Бот IMBA VPN"></a>
  </p>
  <p><a href="https://github.com/array05/IMBATUN/releases/download/v2.1.7/IMBATUN-2.1.7-Windows-x64.zip"><strong>↓ Скачать для Windows</strong></a> &nbsp; · &nbsp; <a href="https://t.me/imbavpn_bot">Получить доступ</a> &nbsp; · &nbsp; <a href="https://github.com/array05/IMBATUN/releases">Все выпуски</a></p>
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/array05/IMBATUN/main/preview.png" width="960" alt="Интерфейс IMBATUN: подключение, выбор сервера и правила маршрутизации">
  <br><sub>Предварительный просмотр интерфейса. Показатели на изображении приведены для примера.</sub>
</p>

## Одно приложение для связи и игр

| Подключение | Маршрутизация | Контроль |
| :--- | :--- | :--- |
| Автоматический поиск рабочего сервера или выбор локации вручную | Зарубежные сервисы через VPN, российские адреса и игры напрямую | Статус соединения, задержка и журнал событий |
| Вход через Telegram без ручного копирования ключей | Исключения для отдельных сайтов и приложений | Игровой оверлей и горячая клавиша |
| Обновление из самого приложения | Обновляемые списки адресов | Проверка связи и добровольные отчёты об ошибках |

## Начать за минуту

1. **Скачайте** [IMBATUN для Windows](https://github.com/array05/IMBATUN/releases/download/v2.1.7/IMBATUN-2.1.7-Windows-x64.zip) и распакуйте архив целиком.
2. **Запустите `IMBATUN.exe`** из распакованной папки. Оставьте рядом папку `core` — она нужна для работы приложения.
3. **Войдите через Telegram:** отсканируйте QR-код или откройте бота, выберите действующую VLESS-подписку и подтвердите вход.
4. **Нажмите кнопку подключения.** Можно оставить «Автоматически» или выбрать нужную локацию.

Нужны Windows 10/11 x64, права администратора для виртуального адаптера и Microsoft Edge WebView2 Runtime. Если WebView2 отсутствует, приложение предложит его установить. Доступ оформляется в [боте IMBA VPN](https://t.me/imbavpn_bot).

## Уже установлен IMBATUN?

Нажмите **«Проверить обновления» → «Установить»** в приложении. IMBATUN скачает и проверит пакет, заменит файлы и перезапустится. Сохранённый вход и настройки остаются на месте.

В **2.1.7** добавлен резервный DNS через VPN и проверка полного пути соединения, включая DNS. Подробности — в [описании выпуска](https://github.com/array05/IMBATUN/releases/tag/v2.1.7). История изменений вынесена в [CHANGELOG](https://github.com/array05/IMBATUN/blob/main/CHANGELOG.md).

## Как идёт трафик

| Что открываете | Маршрут по умолчанию |
| :--- | :--- |
| Зарубежные сайты и приложения | Через VPN |
| Российские домены и IP-адреса из списков | Напрямую |
| Распознанные игры и добавленные игровые `.exe` | Напрямую |
| Лаунчеры и загрузки | По общим правилам адресов |
| Сайты и приложения с ручными исключениями | По вашему правилу |

Правила можно изменить в **«Настройки»**. Страна определяется по адресам, а не языку сайта; списки могут ошибаться. Другой одновременно включённый VPN может влиять на маршрут.

<details>
<summary><strong>Вопросы и помощь</strong></summary>

### Какой архив скачивать?

В [последнем выпуске](https://github.com/array05/IMBATUN/releases/latest) откройте **Assets** и выберите **`IMBATUN-2.1.7-Windows-x64.zip`**. Это готовое приложение с EXE и необходимыми компонентами.

**`Source code (zip)`**, **`Source code (tar.gz)`** и **Code → Download ZIP** — автоматические архивы содержимого репозитория. Здесь размещены документация и выпуски; исходный код оболочки IMBATUN не опубликован. Поэтому архив старого тега может содержать только README. Для установки используйте готовый Windows ZIP из Assets.

### Что делать, если подключение не работает?

Обновите приложение, попробуйте другую локацию и откройте **«Логи» → проверка соединения**. Не включайте одновременно несколько VPN при проверке. Если проблема повторяется, напишите в [Issues](https://github.com/array05/IMBATUN/issues), указав версию IMBATUN, Windows и текст ошибки. Не публикуйте ключи, пароли и ссылки подписки.

### Где игровой оверлей?

Он включается в настройках. По умолчанию горячая клавиша — **Ctrl + Shift + O**. Оверлей работает в оконном режиме и безрамочном полноэкранном режиме; совместимость зависит от игры.

### Подойдёт ключ WireGuard?

Windows-клиент IMBATUN использует VLESS-доступ из бота. Ключи WireGuard для него не подходят.

### Какие данные отправляются в отчётах?

Автоматические отчёты выключены до вашего согласия. Адреса доменов/IP включаются только с отдельного разрешения. Отчёты можно отключить в настройках; сервер хранит их семь дней. Ключи, пароли и содержимое страниц в отчёты не включаются.

</details>

## Компоненты

IMBATUN использует [Xray-core](https://github.com/XTLS/Xray-core), [sing-box](https://github.com/SagerNet/sing-box), [Wintun](https://www.wintun.net/) и списки адресов [MetaCubeX](https://github.com/MetaCubeX/meta-rules-dat). Лицензии компонентов включены в Windows ZIP.

<p align="center"><a href="https://t.me/imbavpn_bot">Telegram</a> · <a href="https://github.com/array05/IMBATUN/releases/latest">Скачать</a> · <a href="https://github.com/array05/IMBATUN/issues">Сообщить о проблеме</a></p>
