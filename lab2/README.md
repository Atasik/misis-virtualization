Поднятый docker репозиторий:
<img width="1222" alt="Снимок экрана 2024-12-12 в 03 39 20" src="https://github.com/user-attachments/assets/262a3f61-b4bb-463b-9383-0ae776fab170" />
Это сервис под названием productcatalogservice, который можно найти в папке src в оригинальном репозитории(https://github.com/GoogleCloudPlatform/microservices-demo)

Нашел два основных способа, которыми можно просмотреть файлы внутри:
1. docker exec:
<img width="1322" alt="Снимок экрана 2024-12-12 в 03 40 22" src="https://github.com/user-attachments/assets/8cde8c1e-aa3d-4054-a3a5-9679a17ec438" />
Не работает в силу того, что внутри контейнера нет оболочки командной строки при запуске со стандартным докер файлом из репозитория.
Если бы оболочка была, то дальнейший алгоритм заключался в использовании cd по пути и/или cat/nano/vim на файл.
Через докер десктоп консоли, как и ожидалось, тоже нет:
<img width="1243" alt="Снимок экрана 2024-12-12 в 03 49 14" src="https://github.com/user-attachments/assets/44d0174c-90f3-41f5-b148-6b690faa49d0" />
2. Docker Desktop:
Нажать Files в соответствующем контейнере достаточно, чтобы посмотреть его содержимое:
<img width="1483" alt="Снимок экрана 2024-12-12 в 03 37 19" src="https://github.com/user-attachments/assets/879d777e-9245-44cc-aa46-e647c4b3aaff" />
