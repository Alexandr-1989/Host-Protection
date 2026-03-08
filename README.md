Задание 1  
Установите eCryptfs. Добавьте пользователя cryptouser. Зашифруйте домашний каталог пользователя с помощью eCryptfs. В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.  

Ответ:  
  
1. Установка eCryptfs.  
<img width="1085" height="479" alt="Screenshot_16" src="https://github.com/user-attachments/assets/d7ace0f4-a2fc-465c-96b6-6b82e6b81bec" />

2. Добавление пользователя cryptouser.  
<img width="699" height="380" alt="Screenshot_18" src="https://github.com/user-attachments/assets/3a96a6e0-7589-4178-9ab3-b6f39be75371" />
  
3.Создаем файлы  данных.  
<img width="621" height="200" alt="Screenshot_19" src="https://github.com/user-attachments/assets/941e2017-4007-448c-9c9d-4334822153f7" />  
  
4. Шифруем домашний каталог cryptouser.  
<img width="1170" height="981" alt="Screenshot_20" src="https://github.com/user-attachments/assets/5d153a33-6cba-4756-b06f-a0c3565dad2c" />
  
5. Проверка зашифрованных данных.  
   Смотрим данные без расшифровки.  
<img width="1332" height="181" alt="Screenshot_25" src="https://github.com/user-attachments/assets/7219ca6b-8cc3-4fff-9391-97410839ee33" />
  
   Смотрим что зашифровано   
<img width="2463" height="165" alt="Screenshot_26" src="https://github.com/user-attachments/assets/3f000251-fd71-4be0-b51b-61d117a5dbb2" />
  
6.Входим за пользователя и проверяем  
 <img width="588" height="168" alt="Screenshot_27" src="https://github.com/user-attachments/assets/53dd9e00-2119-4090-8b36-7888dc09a6b5" />
  
Задание 2  
Установите поддержку LUKS. Создайте небольшой раздел, например, 100 Мб. Зашифруйте созданный раздел с помощью LUKS. В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.  
  
Ответ:  
1. Установка поддержки LUKS (cryptsetup).  
<img width="758" height="218" alt="Screenshot_28" src="https://github.com/user-attachments/assets/6c531e52-3607-4da7-ba76-2e5500adf791" />  
2. Создание раздела.  
<img width="705" height="109" alt="Screenshot_29" src="https://github.com/user-attachments/assets/0b6ae09c-0ec2-4472-97c5-d78579a95e1c" />  
3. Подключаем файл как блочное устройство.  
<img width="701" height="305" alt="Screenshot_30" src="https://github.com/user-attachments/assets/e960dcf9-1eae-4380-8848-a725ad5da51c" />  
4. Инициализация LUKS.  
<img width="582" height="162" alt="Screenshot_31" src="https://github.com/user-attachments/assets/56fd7730-a45b-4c7b-9797-7b8119617f80" />  
5. Открытие раздела и проверка.  
<img width="622" height="109" alt="Screenshot_32" src="https://github.com/user-attachments/assets/f1fefc83-bfad-4658-8df0-c1c3768cc063" />  
6. Создаем файловую систему.  
<img width="663" height="155" alt="Screenshot_33" src="https://github.com/user-attachments/assets/28d3a7f3-8c9d-4e4f-9355-1a6da3a985a7" />  
7. Монтирование и проверка работы.  
<img width="669" height="128" alt="Screenshot_34" src="https://github.com/user-attachments/assets/f9984a4d-a113-4580-b504-9bd24495705a" />  
8. Просмотр защиты.  
<img width="670" height="142" alt="Screenshot_35" src="https://github.com/user-attachments/assets/b81fb752-6e8b-4177-b134-bd8da2ef7150" />  
  
Без cryptsetup open:  
Ядро видит только зашифрованный контейнер,файловая система недоступна.  



 



