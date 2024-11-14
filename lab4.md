# Лабораторная работа 4

В рамках лабораторной работы мне нужно было работать с Docker. Я работала с ним в виртуальной машине с дистрибутивом Ubuntu.

### Ход работы
1. Создала Dockerfile с установкой aafire и ping
2. Собрала образ с тегом mycontainer1, запустила контейнер на основе собранного образа, подключилась в него и запустила команду aafire:
![Screenshot 2024-11-14 113016](https://github.com/user-attachments/assets/ac8eb7bd-f630-4318-9ab2-d2facfbfe7c2)

3. Собрала образ mycontainer2, запустила оба контейнера:
![Screenshot 2024-11-14 115200](https://github.com/user-attachments/assets/1de313f3-85a3-43cd-8ad8-11b8a9986c9c)

4. Создала сеть myNetwork и подключила к ней контейнеры. После посмотрела настройки сети
![Screenshot 2024-11-14 115127](https://github.com/user-attachments/assets/37d0b31e-d6ae-4f9e-aad9-04bb9a3aa7fd)

5. Командой ping проверила соединение из первого контейнера во второй и из второго в первый

![Screenshot 2024-11-14 115448](https://github.com/user-attachments/assets/d8122cef-02fb-4b57-8bb6-fec17b98b6e1)
![Screenshot 2024-11-14 115548](https://github.com/user-attachments/assets/42224c60-c5d0-48f7-bb82-1ef11fed120c)

