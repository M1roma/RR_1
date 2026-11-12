Боц Ілля РБ-61
Завдання №1 (Варіант 2) 
<img width="1102" height="281" alt="image" src="https://github.com/user-attachments/assets/6160e365-609b-4eef-b358-78e8ec94cb48" />


У цій частині програми підключаємо бібліотеки вводу-виводу та локалізації, оголошуємо змінні для збереження введених значень a, N, результату суми S і допоміжної змінної term, яка відповідає за поточний доданок ряду. Початкове значення суми S дорівнює 1.0 відповідно до формули.
<img width="953" height="248" alt="image" src="https://github.com/user-attachments/assets/8ead16a8-b333-46b5-8ebf-9e80dfd2258e" />
Далі зчитуємо з клавіатури дійсне число a та ціле число N. Також додаємо перевірку умови $N \ge 1$: якщо введене число менше одиниці, програма виводить повідомлення про помилку та завершує роботу.
<img width="752" height="307" alt="image" src="https://github.com/user-attachments/assets/cf08a6ad-744a-493a-a57c-b4d19d27d49f" />
У циклі for від 1 до N обчислюємо кожен наступний член ряду рекурентно через попередній, без використання стандартних математичних функцій. При n = 1 перший доданок дорівнює a, а на кожному наступному кроці ми змінюємо знак на протилежний, домножуємо на a та ділимо на n (-term * a / n), після чого додаємо отримане значення до загальної суми S.
<img width="1032" height="264" alt="image" src="https://github.com/user-attachments/assets/d5d71440-80a2-4d7c-b221-bc86aafd9e0f" />

Наприкінці виводимо обчислене значення суми ряду на екран з точністю до 6 знаків після коми і завершуємо виконання програми.
<img width="515" height="125" alt="image" src="https://github.com/user-attachments/assets/2ad9f47f-4fd2-4c6d-bc45-3f5fedce50b3" />

Результат роботи:

<img width="652" height="168" alt="image" src="https://github.com/user-attachments/assets/e9690be9-63e9-4beb-bc80-658a745da68d" />


Завдання №2 (Варіант 2)
<img width="1099" height="277" alt="image" src="https://github.com/user-attachments/assets/c7d19f3f-ac7a-4bbb-848d-00399362bce8" />


У цій частині програми підключаємо бібліотеку вводу-виводу та локалізації, описуємо окрему функцію sum_negative(), яка приймає одновимірний масив arr[] та його розмір size. Всередині функції за допомогою циклу for перевіряємо кожен елемент: якщо він менший за нуль (arr[i] < 0), додаємо його до змінної sum, після чого повертаємо отриманий результат.
<img width="896" height="411" alt="image" src="https://github.com/user-attachments/assets/74ac155c-514a-4054-b343-2e6289822ec4" />

У головній функції main() оголошуємо статичний масив фіксованого розміру (наприклад, на 100 елементів) та зчитуємо з клавіатури фактичну кількість елементів n. Додаємо перевірку, щоб n не виходило за межі виділеного розміру масиву.
<img width="743" height="341" alt="image" src="https://github.com/user-attachments/assets/bdc88c3b-5554-4f0c-aa3a-f00353bee4c3" />

Далі в циклі for зчитуємо елементи масиву з клавіатури, викликаємо функцію sum_negative(arr, n), передаючи їй масив та його розмір, і виводимо знайдену суму від'ємних елементів на екран.
<img width="667" height="281" alt="image" src="https://github.com/user-attachments/assets/5cd26113-90cd-4848-b271-3d7b87031b95" />

Результат:

<img width="646" height="292" alt="image" src="https://github.com/user-attachments/assets/804e8fcd-735f-4eab-ad03-cfe585776da7" />
