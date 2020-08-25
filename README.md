# Записная книжка (API: randomuser.me)

## Обзор
![alt tag](https://github.com/shestakovSA/screen/blob/master/RPReplay_Final1597599422.gif "Пример работы приложения")​


## Требования
Необходимо реализовать онлайн записную книжку, состоящую из не реальных людей, используя https://randomuser.me/.
### Первый экран
1. Список с подзагрузкой из кастомных ячеек, где отображается фотография пользователя и имя ✔️
2. Если проскролили до момента, где записи кончились, то подзагружаем еще до бесконечности ✔️
3. Загружаемые данные пишем в БД
4. Фотографии должны грузится параллельно и сохраняться в кеше

### Второй экран
1. При нажатии на ячейку на первом экране открываем профиль человека ✔️
2. В профиле человека должны быть следующие данные:
   * Фотография (с возможностью открытия на полный экран) ✔️
   * Имя Фамилия ✔️
   * Пол (в виде иконки) ✔️
   * Дата рождения в виде ДД.ММ.ГГГГ (в скобках число лет) ✔️
   * Почта ✔️
   * Местное время (текущее время + смещение по часовому поясу) ✔️

### Стек
* SwiftyJSON
* Realm
* FontAwesome
