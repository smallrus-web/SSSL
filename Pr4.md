# Практическая работа №4
## Выполнил студент группы ББМО-01-23 Архипов Дмитрий Евгеньевич
### Скачиваем и разворачиваем стенд:
![Screenshot_1](https://github.com/user-attachments/assets/3d0be623-a7d6-4f68-b0cb-d852f65cdd99)
### Интерфейс AC-hunter
![Screenshot_2](https://github.com/user-attachments/assets/6a0ea583-0a91-43a6-8260-d3ebd9dcfed1)
### Загружаем датасет с первой лабараторной
![image](https://github.com/user-attachments/assets/f6b8a8f6-6f4e-40a5-941d-d1d68d3f208c)
### Выбираем датасет в AC-hunter
![image](https://github.com/user-attachments/assets/d3478996-5302-4e57-9b62-40c3d47e68bc)
### Первый адресс: выглядит достаточно подозрительным из-за высокого показателя beaconscore
![image](https://github.com/user-attachments/assets/55d2faa4-e14a-4704-8762-bec1019cd280)
### Второй адресс: относится к Windows и имеет низкий показатель beaconscore
![image](https://github.com/user-attachments/assets/d2ead394-b6c8-4935-9e36-6ddaddcd3159)
### Третий адресс: относится к Windows и имеет низкий показатель beaconscore
![image](https://github.com/user-attachments/assets/9b03474b-057b-41aa-af52-525a9624ce06)
### Четвертый адресс: относится к Windows и имеет низкий показатель beaconscore
![image](https://github.com/user-attachments/assets/6e653bc6-48ac-423e-a95a-a6ce08b8c9eb)
### Пятый адресс: относится к Windows и имеет низкий показатель beaconscore
![image](https://github.com/user-attachments/assets/b9430f4a-412e-474f-9b18-4bcd150e6ff1)
### Шестой адресс: относится к Windows и имеет низкий показатель beaconscore
![image](https://github.com/user-attachments/assets/35430b29-83fd-4536-807e-6d12c53565cc)
### Седьмой адресс: относится к Windows и имеет низкий показатель beaconscore
![image](https://github.com/user-attachments/assets/985af5f8-1af4-4062-9504-ab6360590ff0)
### В связи с тем что первый адресс похож на нелегетимный обратимся к модулю long connections
![image](https://github.com/user-attachments/assets/3b2b51f6-1864-4e9d-94a8-05cb47e4001e)
### Мы видим что у нас существует только 2 адресса проверим их через virustotal
![image](https://github.com/user-attachments/assets/23bad24e-3f16-4532-b280-73932497a478)
![image](https://github.com/user-attachments/assets/45fe2703-2142-42cf-93e5-bf0f0f3304ad)
### Проверив первый адресс еще раз с помощью AbuseIPDB видим что на него было 2 жалобы как на нелегетимный
![image](https://github.com/user-attachments/assets/2d3be5d7-0a90-41c1-a101-c3b4b74dc625)
### В конечном итоге можно сделать вывод что Соединение с 167.71.97.235 выглядят подозрительно тк как высокий показатель beacon score, не было обнаружено поля «хост» в HTTP-заголовке, длинная запутанная строка URI и так же имеются жалобы на вредоносность данного ресурса.
### Загружаем датасет со второй лабороторной
![image](https://github.com/user-attachments/assets/ed7736e4-85c6-47ad-b523-9953f2e32f34)
![image](https://github.com/user-attachments/assets/ec886708-19f0-4d7d-bf70-62c7b4d5639f)
### Переходим во вкладку DNS 
![image](https://github.com/user-attachments/assets/e4001dee-9f71-4ad7-ba84-bbf0defc1c3d)
![image](https://github.com/user-attachments/assets/a967ee93-7ab0-4e41-b094-bb17f0d191a4)








