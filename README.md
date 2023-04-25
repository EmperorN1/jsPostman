# jsPostman

Наша задача - при помощи Endpoints -> Get Current User получить данные пользователя

Этот Endpoint работает только в случае авторизации пользователя

![image](https://user-images.githubusercontent.com/88553862/234386111-76cd1e7a-4b36-4350-b0f8-6f046d89beee.png)

Чтобы получить результат, необходимо: 
1) Создать аккаунт
2) Авторизоваться
3) Повторить вопрос

1 - При помощи POST метода /users создаём новый аккаунт пользователя

![image](https://user-images.githubusercontent.com/88553862/234386780-134e62f1-8789-42c9-a0f7-f1e83a352c86.png)

2 - Авторизовываемся используя POST метод /users/login

![image](https://user-images.githubusercontent.com/88553862/234387013-a6584d23-4498-4ae0-9a61-71d881e5e75d.png)

Полученный при авторизации токен вводим в разделе Autorization

![image](https://user-images.githubusercontent.com/88553862/234387241-7c80b26b-5750-4eb4-aa5b-5b8e26982f0d.png)

3 - Выполняем GET запрос /user

![image](https://user-images.githubusercontent.com/88553862/234387410-24befd8a-b725-47ef-92af-7d3fe5efc65c.png)
