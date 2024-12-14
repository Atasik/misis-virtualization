1. Создаем двух юзеров и папку content для тестирования. Как можно видеть, при их создании так же появились и соответстующие им группы:
<img width="311" alt="Снимок экрана 2024-12-13 в 02 54 40" src="https://github.com/user-attachments/assets/d8f4c65c-a903-4ad1-897c-31d84fbcfc84" />
<img width="332" alt="Снимок экрана 2024-12-13 в 02 55 05" src="https://github.com/user-attachments/assets/54df8768-a1d6-4fff-8ed3-55d8df7c03a1" />

2. Выдаем соответствущие права группам:
<img width="255" alt="Снимок экрана 2024-12-13 в 05 56 29" src="https://github.com/user-attachments/assets/91cff59d-4263-42b8-977d-c11637fdc303" />

3. Проверяем права consumer'а:
<img width="188" alt="Снимок экрана 2024-12-13 в 05 59 10" src="https://github.com/user-attachments/assets/2926c9c5-8f93-4b1b-a412-7963907bde78" />

Действительно, файлы нельзя создавать в соответствии с разрешениями юзер группе.

4. Проверяем права producer'а:
<img width="189" alt="Снимок экрана 2024-12-13 в 06 01 57" src="https://github.com/user-attachments/assets/6507c779-0f6c-4380-9015-bcf29dcf5814" />

Как и ожидалось, нельзя зайти в директорию, так как нет прав на execute.



