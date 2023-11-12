# PlayerSpawnsPZ
New places of player spawn in game Project Zomboid
## RU description
Сайт откуда взяты координаты для спавна игроков: https://map.projectzomboid.com
Берем эти файлы и закидываем в папку `C:\Program Files (x86)\Steam\steamapps\common\ProjectZomboid\media\maps`
В этих папках хранятся 5 файлов (`thumb.png`, `spawnpoints.lua`, `maps.info`, `title.txt`, `discription.txt`), где
*  `thumb.png` - Фото которое будет отображаться  при выборе места спавна
*  `spawnpoints.lua` - Точки спавна координаты из представленных для каждой профессии, оно выбирает рандомное из предложенных координат
*  `maps.info` - Информация о карте название и описание (можно как раз сделать с помощью файлов `title.txt`, `discription.txt`, точнее ссылок на них из папки translations) (у меня не вышло буду рад вашим рекомендациям в разделе Discussions)
*   `title.txt` - Название локации спавна
*   `discription.txt` - Описание локации спавна
  
Какие локации(точки) есть в данном репозитории:
* Abandoned - Заброшенные здания
* Allneed - Райончик вдали от города, где есть магазины, кафе и тд
* Camp - Лагери (Детский, туристический и военный)
* Criminal - Огражденный домик по истории одной криминальной личности
* Electricity - Электростации
* Factory - Комплекс заводов
* Hospital - Больница Луисвиля
* Hunter - Охотние угодья
* Movie - Поблизости кинотеатр открытого типа
* RadioStation - Радио-метео станция
* Random - Одно из предложенных ранее мест
* Rich - Богатые дома
* Shrek - не стану рассказывать, сами узнаете
* TrainStation - Станция поездов
* Random - Одно из предложенных ранее мест
* Unknown - Отдаленный участок карты, откуда выбраться не так уж и легко

В директории res находятся файлы примерного описания каждой из локаций.

Может работать не стабильно, если помещение в котором вы спавнитесь закрыто, это так же относится и к "Shrek"
## ENG description
The site where the coordinates for spawning players are taken from: https://map.projectzomboid.com
We take these files and put them in the folder `C:Program Files (x86)SteamsteamappscommonProjectZomboidmediamaps`
These folders contain 5 files (`thumb.png`, `spawnpoints.lua`, `maps.info`, `title.txt`, `discription.txt`), where
* `thumb.png` - Photo that will be displayed when choosing a spawn location
* `spawnpoints.lua` - Spawn point coordinates from those presented for each profession, it selects a random one from the proposed coordinates
* `maps.info` - Information about the map name and description (can be done using the files `title.txt`, `discription.txt`, or rather links to them from the translations folder) (it didn’t work out for me, I’ll be glad for your recommendations in the Discussions section)
* `title.txt` - Name of the spawn location
* `discription.txt` - Description of the spawn location

What locations (points) are in this repository:
* Abandoned - Abandoned buildings
* Allneed - An area away from the city where there are shops, cafes, etc.
* Camp - Camps (Children's, tourist and military)
* Criminal - A fenced house based on the story of a criminal figure
* Electricity - Power stations
* Factory - Complex of factories
* Hospital - Louisville Hospital
* Hunter - Hunting grounds
* Movie - There is an open-air cinema nearby
* RadioStation - Radio weather station
* Random - One of the previously proposed places
* Rich - Rich houses
* Shrek - I won’t tell you, you’ll find out for yourself
* TrainStation - Train station
* Random - One of the previously proposed places
* Unknown - A remote area of ​​the map, from where it is not so easy to get out

The res directory contains files with approximate descriptions of each location.

May not work stably if the room you spawn in is closed, this also applies to 'Shrek'
