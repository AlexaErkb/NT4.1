# NT4.1 Поднятие веб-сервера
# Установка и запуск веб-сервера в Linux
# Цель работы
Освоить основные навыки установки и первоначальной настройки веб-сервера в ОС Linux.
# Задания для выполнения
Используя apt-get установить Apache2 на виртуальную машину  
![image](https://user-images.githubusercontent.com/70998859/142777405-d0f7f513-01fd-4b82-a9d3-9930781e1167.png)  
С браузера хост-машины по IP-адресу виртуальной машины увидеть приветствие  
![image](https://user-images.githubusercontent.com/70998859/142777476-95cc1ecd-a567-4a14-b6e0-bed77b22d805.png)  
В настройках сервера изменить  порт на :8080  
![image](https://user-images.githubusercontent.com/70998859/142777539-7c67054d-37ad-4cfc-8ed1-eee80afb7092.png)  
![image](https://user-images.githubusercontent.com/70998859/142777593-b711df52-8235-4eff-a751-184118fd409b.png)   
Снова выполнить п 2, но с указанием порта  
![image](https://user-images.githubusercontent.com/70998859/142777601-68db16b9-9837-4cdc-a99d-76e711c9450d.png)  
Изменить порт обратно и проверить как работает заглушка  
![image](https://user-images.githubusercontent.com/70998859/142777672-9ed0e9cd-9de4-4f06-930c-8db4fcc32262.png)  
![image](https://user-images.githubusercontent.com/70998859/142777678-59032979-8f9b-410b-8950-0cc9e2c49bd5.png)   
![image](https://user-images.githubusercontent.com/70998859/142777662-d4d0fda2-c31b-44ca-a378-46f3d10a3158.png)  
В hosts хост-машины создать три домена: a1.com, b2.com, c3.com и связываем с IP виртуальной машины с Apache  
![image](https://user-images.githubusercontent.com/70998859/142777848-778bcc50-147a-48ac-aea8-94b8b7c1017d.png)  
Для каждого домена проверить всё ли правильно, с помощью ping  
![image](https://user-images.githubusercontent.com/70998859/142778432-df0057ae-1218-4222-b2bd-772bfa7ae713.png)  
![image](https://user-images.githubusercontent.com/70998859/142778456-dc6664b3-f168-4a6e-96d7-3ef7c9030d66.png)  
![image](https://user-images.githubusercontent.com/70998859/142778459-b107a719-6c8f-4055-b800-f2e83e901c5d.png)  
Зайти на все три домена, написав их вместо IP виртуальной машины  
![image](https://user-images.githubusercontent.com/70998859/142778487-cc5772b3-dcc3-408d-bef7-340b5153d21b.png)  
![image](https://user-images.githubusercontent.com/70998859/142778496-41b92fc9-78b3-4e27-9d9a-3f9ea3b4f11e.png)  
![image](https://user-images.githubusercontent.com/70998859/142778504-0dc4e767-9555-449f-9dff-c172e021f299.png)  
Создать директории /var/www/a1.com, /var/www/b2.com, /var/www/c3.com  
![image](https://user-images.githubusercontent.com/70998859/142778592-f75f5811-4214-4b89-9dfd-f3ff8c9a32e9.png)  
В каждой из них создать пустой index.html  
![image](https://user-images.githubusercontent.com/70998859/142778676-af3d7920-f042-4b44-a66c-64f6f3b3cf90.png)  
В каждом из них написать различное содержимое  
![image](https://user-images.githubusercontent.com/70998859/142778810-ed7a7b61-50e6-4b20-bffc-48f63b6b8452.png)  
![image](https://user-images.githubusercontent.com/70998859/142778815-34406f19-670e-4c58-9620-267a3f872e06.png)  
![image](https://user-images.githubusercontent.com/70998859/142778817-8f23980b-7dd1-4ec5-84be-d227e18217a4.png)  
Сделать так, чтобы из браузеров хост-машины открывались сайты из директории, а не общая заглушка
![image](https://user-images.githubusercontent.com/70998859/142778949-c1cfe445-04da-4edd-99b2-9d23c0dfaa23.png)
![image](https://user-images.githubusercontent.com/70998859/142778958-f57f15d1-707b-4a5d-a12d-666e1b783d3a.png)
Сайты открываются:
