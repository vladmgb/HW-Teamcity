# Домашнее задание к занятию 11 «Teamcity»


Развернул три ВМ в облаке:

<img width="1253" height="358" alt="image" src="https://github.com/user-attachments/assets/3c8c3d60-290c-446a-b6ba-a3778d4ffcf6" />


Авторизовал агента TeamCity

<img width="967" height="443" alt="image" src="https://github.com/user-attachments/assets/5bee22d1-2771-44ef-ba1c-b699889c71f8" />


Создал проект и `build configuration` на основе fork. Сделал autodetect конфигурации.
Изменил URL Nexus в файле на свой.
Запустил первую сборку master, проверил успешность.

<img width="1162" height="568" alt="image" src="https://github.com/user-attachments/assets/1adfe2c1-721e-47c0-886e-0874417f45ac" />


Поменял условия сборки

<img width="1282" height="640" alt="image" src="https://github.com/user-attachments/assets/71c8af5d-8303-454f-baa8-754765431df2" />


Запустил сборку.

<img width="1209" height="636" alt="image" src="https://github.com/user-attachments/assets/c89f2d1d-f3ce-48c5-bea7-3030e1a49047" />


Проверил артефакты в Nexus.

<img width="1302" height="686" alt="image" src="https://github.com/user-attachments/assets/b3ca83d5-b58e-4fd1-8761-c07f0a431164" />


Смигрировал `build configuration` в [репозиторий](https://github.com/vladmgb/example-teamcity/tree/master/.teamcity).

Создал новую ветку feature/add_reply.

<img width="914" height="626" alt="image" src="https://github.com/user-attachments/assets/fe58f561-a0fb-47de-840c-a7f5d07ba166" />


Добавил новый метод для приложения в main 

<img width="1019" height="501" alt="image" src="https://github.com/user-attachments/assets/32acef31-9f58-4d3c-88d4-972f7c62e8e4" />

Дополнил тест на поиск `hunter`

<img width="963" height="688" alt="image" src="https://github.com/user-attachments/assets/75754239-343e-4912-9da7-98db79492f71" />


Изменил версию в pom.xml и запушил все в новую ветку feature/add_reply.
В Teamcity сборка запустилась автоматически по ветке feature/add_reply, тесты прошли успешно.

<img width="1195" height="672" alt="image" src="https://github.com/user-attachments/assets/d17b0610-a716-44d2-82ef-677717e23fe7" />


Cделал слияние ветки feature/add_reply в ветку master.

<img width="791" height="589" alt="image" src="https://github.com/user-attachments/assets/510897b3-a85c-46c0-97eb-f9d71f767c58" />


В TeamCity автоматически пошла сборка в ветке master.

<img width="1213" height="531" alt="image" src="https://github.com/user-attachments/assets/8fd20c83-d99c-40e1-966d-96ec5e0a901c" />


В Nexus появилс новый артефакт с новой версией по ветке master.

<img width="1291" height="661" alt="image" src="https://github.com/user-attachments/assets/59085e98-1bc6-4843-8bce-97ca48c98e41" />


ссылка на [репозиторий](https://github.com/vladmgb/example-teamcity.git).
