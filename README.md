# Домашнє завдання, тема 5

1. Напишіть SQL запит, який буде відображати таблицю order_details та поле customer_id з таблиці orders відповідно для кожного поля запису з таблиці order_details.
Це має бути зроблено за допомогою вкладеного запиту в операторі SELECT.

![Screenshot_1](https://github.com/user-attachments/assets/8136b58b-4fed-4ba9-9de9-ce44df71e702)


2. Напишіть SQL запит, який буде відображати таблицю order_details. Відфільтруйте результати так, щоб відповідний запис із таблиці orders виконував умову shipper_id=3.
Це має бути зроблено за допомогою вкладеного запиту в операторі WHERE.

![Screenshot_2](https://github.com/user-attachments/assets/df29229b-2f36-4236-b312-676c5754fb10)


3. Напишіть SQL запит, вкладений в операторі FROM, який буде обирати рядки з умовою quantity>10 з таблиці order_details. Для отриманих даних знайдіть середнє значення поля quantity — групувати слід за order_id.

![Screenshot_3](https://github.com/user-attachments/assets/a869248b-f58c-4a86-9acd-3e1035a106ec)

![Screenshot_4](https://github.com/user-attachments/assets/84f29464-89ca-4004-972e-e14dd3991442)



4. Розв’яжіть завдання 3, використовуючи оператор WITH для створення тимчасової таблиці temp. Якщо ваша версія MySQL більш рання, ніж 8.0, створіть цей запит за аналогією до того, як це зроблено в конспекті.

![Screenshot_5](https://github.com/user-attachments/assets/d1626b6e-3c01-49a8-b139-2fb3c0cf2d12)


5. Створіть функцію з двома параметрами, яка буде ділити перший параметр на другий. Обидва параметри та значення, що повертається, повинні мати тип FLOAT.
Використайте конструкцію DROP FUNCTION IF EXISTS. Застосуйте функцію до атрибута quantity таблиці order_details . Другим параметром може бути довільне число на ваш розсуд.

![Screenshot_6](https://github.com/user-attachments/assets/5752b394-cd25-4f3f-844a-b2ddbf2de693)
