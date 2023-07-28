### ✓ Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
![list](./screenshots/list.png)
### ✓ Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
![get](./screenshots/get.png)
### ✓ Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
![add](./screenshots/add.png)
### ✓ Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
 ![remove](./screenshots/remove.png)
