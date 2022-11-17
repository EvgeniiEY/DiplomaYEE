## Краткое описание

Это приложение было разработано в качестве димпломного проекта. Приложение сделано по типу социальной сети.

## Стек
* MVVM
* Fragments
* Material Design
* Coroutines
* Room
* Retrofit
* LiveData, Flow
* Paging
* Workmanager
* Hilt
* ImagePicker, Glide, Intent

## Возможности приложения
Для входа в приложение вам необходимо аутентифицироваться. Вы можете зайти под тестовым пользователем:

* __Логин__ 111111
* __Пароль__ 111111

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/signIn.jpg)

 Так же Вы можете зарегистрировать нового пользователя с добавлением аватара или без него. После регистрации вам необходимо пройти процедуру аутентификации.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/transitionToRegistration.png)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/signUp.jpg)


 После аутентификации вам станут доступны: 
 1. Лента постов.
 2. Лента событий.
 3. Список существующих пользователей.
 4. Ваш профиль.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/posts.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/events.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/users.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/myProfile.jpg)

__Лента постов__

Вы можете просмотреть все посты пользователей, в том числе и свои. 
 - Используйте меню, чтобы удалить и отредактировать свой пост или скройте чужой пост.
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/myMenuPost.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/ownerMenuPost.jpg)
 - Проставляйте лайки на постах, которые вам понравились. Под постом вы увидите первых двух пользователей, которые оценили пост. Нажмите на список, чтобы просмотреть всех пользователей, которым понравился пост.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/likePost.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/listLike.jpg)
 - Просматривайте отмеченных менторов в постах. Нажмите на список, чтобы просмотреть всех отмеченных пользователей.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/mentors.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/listMentors.jpg)
 - Просматривайте координаты, оставленные в посте в "Яндекс. Карты". Нажмите на иконку, чтобы просмотреть.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/CoordPost.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/mapPost.jpg)

 - Вы можете сделать репост себе на стену или отправить его другу с помощью другого приложения.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/repostAndShare.jpg)
 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/share.jpg)
 - Ознакамливайтесь с рекламой прямо в ленте постов.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/ad.jpg)

 __Лента событий__

 Вы можете просмотреть все события пользователей, в том числе и свои. Совершайте в событиях те же действия, что и в постах. А еще:
 - Нажмите на иконки форматов событий и перейдите на сайт встречи или просмотрите координаты.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/coordAndWebEvent.jpg)
 - Нажмите на иконку, чтобы присоединиться к событию. Под событием вы увидите первых двух пользователей, которые будут участвовать в мероприятии. Нажмите на список, чтобы просмотреть всех участников.

 ![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/joinEvent.jpg)
 
 __Список пользователей__

Просматривайте список пользователей и переходите к ним в профиль.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/users.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/userProfile.jpg)

__Мой профиль__

- Просмотрите список работ и свои посты

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/profileSections.jpg)
- Создавайте новое: Место работы, Событие, Пост.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/new.jpg)
- При необходимости выйдите из профиля.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/exit.jpg)

__Создание работы__

- Заполните поля.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/newJob.jpg)
- Указывая период работы, нажмите на поле и выберите дату в календаре.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/calendar.jpg)
- Если вы укажите некорректную ссылку в поле "Сайт", приложение сообщит об этом.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/linkErrorJob.jpg)

__Создание события__

- Заполните поля.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/newEvent.jpg)
- Указывая дату и время, нажмите на поле и выберите необходимое в календаре и часах.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/time.jpg)
- Выберите формат из списка. В зависимости от варианта, укажите ссылку на событие или координаты на карте.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/formatEvent.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/coordEvent.jpg)
- Для добавления координат нажмите на место в картах, а затем на знак плюс или добавьте точку длительным нажатием на место. Если вам необходимо найти свое местоположение, нажмите на кнопку "моя локация"

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/mapAddPlace.jpg)
- Укажите спикеров. Нажмите на поле и установите флажки на юзерах.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/listSpeakers.jpg)
- Добавьте вложение.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/attachmentChooser.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/imageChooser.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/videoChooser.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/attachmentVideo.jpg)
![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/attachmentAudio.jpg)
- Если обязательные поля не заполнены, приложение сообщит об этом при сохранении.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/errorEvent.jpg)

__Создание поста__

Напишите о том, что для вас важно. Вы можете сделать вложение (фото, аудио, видео), оставить координаты и отметить людей.

![Image alt](https://github.com/EvgeniiEY/DiplomaYEE/blob/main/screenshots/newPost.jpg)



