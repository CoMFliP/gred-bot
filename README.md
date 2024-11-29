# <div><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/logo.ico" alt="logo" width="32"/><span> GredBot</span></div> 
___

## RU:
Бесплатное и простое программное обеспечение для улучшение качества ваших прямых трансляций. Скачайте и получите новый и удивительный опыт ведений прямых трансляций

### Основные функции
Данная программа имеет интеграции, которые позволяет взаимодействовать между зрителями и ведущим трансляции через баллы канала **Twitch**, заказывать или пропускать музыку из **YouTube**
<br/>
Есть возможность добавить виджет плеера через источник в **OBS** и прочие стриминговые программы

```mermaid
sequenceDiagram
Twitch API ->> GredBot: Активация события
activate GredBot
Note over Twitch API, GredBot: Может содержаться строка<br/>от награды пользователя

GredBot ->> YouTube API: Отправляет запрос<br/>на обработку
activate YouTube API
YouTube API -->> GredBot: Ответ с данными
deactivate YouTube API

GredBot -->> Twitch API: Ответ на событие
deactivate GredBot
```

Есть различные настройки и прочие дополнительные функции, для фильтрации заказываемых треков
<br/>
Так же есть возможность загрузить плейлист из **Youtube**, вставив ссылку

### Скриншоты
|Панель управления (История)|Панель управления (Плейлисты)|Плеер|
|---------------------------|-----------------------------|-----|
|<a href="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/1.png"><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/1.png" alt="screen"/></a>|<a href="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/2.png"><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/2.png" alt="screen"/></a>|<a href="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/3.png"><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/3.png" alt="screen"/></a>|

### Обратная связь
Если у Вас возникли какие-то вопросы, пробемы и прочие затруднения, можете написать [здесь](https://github.com/CoMFliP/gred-bot/issues/new) или написать мне на e-mail: comflipcontact@gmail.com

___

## EN:
> [!WARNING]  
> Currently there is no English language, more languages ​​are planned to be added in future updates
<br/>

Free and simple software to improve the quality of your live broadcasts. Download and get a new and amazing live streaming experience

### Main features
This program has integrations that allow you to interact between viewers and the broadcast host through **Twitch** channel points, order or skip music from **YouTube**
<br/>
It is possible to add a player widget via source to **OBS** and other streaming programs

```mermaid
sequenceDiagram
Twitch API ->> GredBot: Event activation
activate GredBot
Note over Twitch API, GredBot: May contain a string<br/>from the user's reward

GredBot ->> YouTube API: Sends a request<br/>for processing
activate YouTube API
YouTube API -->> GredBot: Response with data
deactivate YouTube API

GredBot -->> Twitch API: Event Response
deactivate GredBot
```

There are various settings and other additional functions for filtering ordered tracks
<br/>
It is also possible to download a playlist from **Youtube** by inserting a link

### Screenshots
|Control Panel (History)|Control Panel (Playlists)|Player|
|-----------------------|-------------------------|------|
|<a href="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/1.png"><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/1.png" alt="screen"/></a>|<a href="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/2.png"><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/2.png" alt="screen"/></a>|<a href="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/3.png"><img src="https://raw.githubusercontent.com/CoMFliP/gred-bot/main/screens/3.png" alt="screen"/></a>|

### Feedback
If you have any questions, problems or other difficulties, you can write [here](https://github.com/CoMFliP/gred-bot/issues/new) or write to me by e-mail: comflipcontact@gmail.com

___



