# Политика конфиденциальности «Копеечки»

*Редакция от 22 сентября 2026 года.*

«Копеечка» — приложение для учёта личных и семейных финансов. У приложения
**нет своего сервера**: разработчик не получает, не хранит и не видит ваши данные.

## Что хранится и где

Счета, операции, бюджеты, цели, долги, заказы и настройки хранятся **только на вашем
телефоне**, в личной папке приложения. Приложение не показывает рекламу, не содержит
аналитики и трекеров и никому не передаёт данные для маркетинга.

Данные уходят с телефона только в перечисленных ниже случаях — и только если вы
сами включили соответствующую функцию.

## Когда данные покидают телефон

**Резервные копии в Google Диск.** Если вы подключили Google Диск, приложение кладёт
копию данных в папку на **вашем** Диске. Доступ запрашивается к файлам, которые создало
само приложение (`drive.file`), — остальное содержимое Диска приложению недоступно.
Ключи ИИ-провайдеров в копию не попадают.

**Копия файлом.** Файл сохраняется туда, куда вы укажете, или отправляется
через выбранное вами приложение (мессенджер, почта).

**ИИ-советник и чеки по фото.** Работают, только если вы указали свой ключ выбранного
провайдера (Anthropic, OpenAI, Google, Сбер — GigaChat, Яндекс — YandexGPT или адрес
собственного сервера). Когда вы задаёте
вопрос советнику, провайдеру отправляются те данные, которые вы отметили в настройках
советника. Когда вы распознаёте чек, провайдеру отправляется фотография чека
и список ваших категорий. Данные обрабатываются по правилам этого провайдера.
Ключ хранится в защищённом хранилище телефона (Android Keystore / iOS Keychain).

**Общий бюджет («Вместе»).** Если вы завели общее пространство с другим человеком,
ваши счета и операции передаются ему — через хранилище, которое вы выбрали
(ваш Google Диск, ваш WebDAV-сервер), или напрямую по вашей локальной сети.
Черновики, правила чтения СМС и ключи не передаются. Пароль WebDAV хранится
в защищённом хранилище телефона.

**Экспорт CSV.** Файл сохраняется туда, куда вы укажете в системном диалоге.

**Курсы валют.** По кнопке «Официальные курсы» приложение запрашивает курсы с сайта
Банка России, Национального банка Казахстана или Центрального банка Узбекистана.
Ваших данных в этом запросе нет.

**Проверка покупки.** Приложение платное и распространяется через Google Play.
При запуске оно спрашивает у Google Play, куплено ли приложение на этом устройстве.
В запросе нет ваших финансовых данных; оплату и данные покупки обрабатывает Google
по своим правилам.

**Чеки по QR-коду** разбираются на телефоне и никуда не отправляются.

## Разрешения

- **Интернет** — для резервных копий, ИИ-советника и общего бюджета.
- **Уведомления** — для вечернего напоминания, если вы его включили.
- **Камера и фото** — приложение не запрашивает доступ к камере напрямую: снимок
  делает системная камера, фото выбирается системным окном, и приложению передаётся
  только выбранный снимок.
- **СМС** — только если вы сами включите «Читать банковские СМС» в настройках.
  Перед системным запросом разрешения приложение объясняет, зачем оно нужно.
  Читаются только сообщения отправителей из ваших правил банков; при включении —
  за последние 90 дней, дальше — новые по мере прихода. Текст разбирается на
  телефоне, никуда не отправляется и в резервную копию не попадает. Без разрешения
  приложение работает как прежде: сообщение банка можно вставить вручную.
- **Доступ к уведомлениям** (Android) — только если вы сами включите его в настройках
  телефона. Приложение смотрит уведомления банковских приложений, чтобы предложить
  операцию; текст уведомлений разбирается на телефоне, никуда не отправляется
  и в резервную копию не попадает. Отключить можно в любой момент там же.

## Удаление данных

Все данные удаляются вместе с приложением. Резервные копии на Google Диске вы можете
удалить сами в папке «Kopeechka» на своём Диске. Данные, отправленные ИИ-провайдеру,
удаляются по правилам этого провайдера.

## Дети

Приложение не предназначено для детей младше 13 лет и сознательно не собирает
их данные.

## Изменения и связь

Изменения этой политики публикуются в этом файле; история правок видна в репозитории
https://github.com/MerdanOchanov/kopeechka.
Вопросы можно задать через раздел Issues:
https://github.com/MerdanOchanov/kopeechka/issues

---

# Privacy policy (English)

Kopeechka is a personal finance app with **no server of its own**: the developer does not
receive, store or see your data. Everything stays on your phone, with no ads, analytics
or trackers.

Data leaves the phone only when you turn on a feature that needs it:

- **Google Drive backups** go to a folder in your own Drive; the app can only access
  files it created (`drive.file`). AI keys are never included.
- **AI advisor and receipt scanning** work only with your own provider key (Anthropic,
  OpenAI, Google, Sber GigaChat, Yandex YandexGPT or your own server). Your selected data,
  or the receipt photo with your category list, is sent to that provider and handled
  under its terms.
- **Exchange rates** are requested from a central bank website when you tap the button;
  the request contains none of your data.
- **Purchase check.** The app is paid and distributed through Google Play. On start it asks
  Google Play whether the app was purchased on this device. The request contains none of
  your financial data; payment and purchase data are handled by Google under its terms.
- **Backup to a file** goes wherever you save or share it.
- **Shared budget** sends your accounts and operations to the other member through the
  storage you chose (your Google Drive, your WebDAV server) or directly over your local
  network. Drafts, SMS rules and keys are not shared.
- **CSV export** is saved where you choose.

The app does not request camera access directly: photos come from the system camera or
picker; receipt QR codes are read on the phone. Bank SMS reading is off by default. You enable it in the settings after an explanation
and the system permission prompt; only messages from senders in your own bank rules are read
(the last 90 days when enabled, then new ones as they arrive). SMS text is parsed on the phone,
never sent anywhere and never included in backups. Without the permission you can still paste
a bank message manually.
Bank notification reading (Android) works only after you grant notification access in the
system settings; notifications are parsed on the phone and never sent anywhere.

Uninstalling the app deletes its data. Contact: https://github.com/MerdanOchanov/kopeechka/issues
