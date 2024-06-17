# Relational Databases. Nested requests. Code reuse

1. Напишіть SQL запит, який буде відображати таблицю order_details та поле customer_id з таблиці orders
   відповідно для кожного поля запису з таблиці order_details.
   Це має бути зроблено за допомогою вкладеного запиту в операторі SELECT.

![1](./assets/p1.png)

2. Напишіть SQL запит, який буде відображати таблицю order_details.
   Відфільтруйте результати так, щоб відповідний запис із таблиці orders виконував умову shipper_id=3.
   Це має бути зроблено за допомогою вкладеного запиту в операторі WHERE.

![2](./assets/p2.png)

3. Напишіть SQL запит, вкладений в операторі FROM, який буде обирати рядки з
   умовою quantity>10 з таблиці order_details. Для отриманих даних знайдіть
   середнє значення поля quantity — групувати слід за order_id.

![3](./assets/p3.png)

4. Розв'яжіть завдання 3, використовуючи оператор WITH для створення тимчасової таблиці temp.
   Якщо ваша версія MySQL більш рання, ніж 8.0, створіть цей запит за аналогією до того, як це зроблено в конспекті.

![4](./assets/p4.png)

5. Створіть функцію з двома параметрами, яка буде ділити перший параметр на другий.
   Обидва параметри та значення, що повертається, повинні мати тип FLOAT.
   Використайте конструкцію DROP FUNCTION IF EXISTS. Застосуйте функцію до атрибута quantity таблиці order_details.

![5.1](./assets/p5_1.png)
![5.2](./assets/p5_2.png)
![5.3](./assets/p5_3.png)
