
# Лабораторная работа 4  
  
Содержимое Dockerfile:  
![Screenshot from 2024-12-02 18-08-53](https://github.com/user-attachments/assets/66c4c620-8bb7-4b04-9914-98699581679f)  
  
Билдим контейнер с aafire:  
![Screenshot from 2024-12-03 15-31-14](https://github.com/user-attachments/assets/271ca834-638b-4a33-9796-6b53cc452915)  
  
Вводим ```sudo docker run --it aafire``` и смотрим результат:  
![Screenshot from 2024-12-03 15-34-06](https://github.com/user-attachments/assets/4017f09f-db3a-4d24-9274-ae8108239633)  
  
Новое содержимое Dockerfile с добавленной утилитой ping:  
![Screenshot from 2024-12-05 16-25-59](https://github.com/user-attachments/assets/8c3eebd2-979d-4012-aae0-ce4f8af9640b)  
  
Вводим ```sudo docker build -t aafire .``` и создаем 2 новых контейнера:  
![Screenshot from 2024-12-03 15-45-19](https://github.com/user-attachments/assets/b8de5251-1344-466d-9394-6fa4a7eee19f)  
  
Создаем сеть myNetwork и подключаем к ней оба контейнера:  
![Screenshot from 2024-12-03 15-47-50](https://github.com/user-attachments/assets/e59e56e8-2052-4495-8367-aceb9b58619b)  
  
Заходим в root одного из контейнеров и пингуем из него другой:  
![Screenshot from 2024-12-03 15-52-05](https://github.com/user-attachments/assets/c7a6e7b2-138c-434a-97d3-6427d124796e)  
  
Получили желаемый результат, удаляем оба контейнера:  
![Screenshot from 2024-12-03 15-52-58](https://github.com/user-attachments/assets/e84fd6cc-65a8-4523-b009-5e02e8606c3a)  
