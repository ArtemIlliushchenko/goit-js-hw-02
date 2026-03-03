# Домашнє завдання 2 – Умови, рядки, switch

## Опис
Друге домашнє завдання з JavaScript.  
Практика роботи з умовними конструкціями, рядками, перевіркою умов та оператором `switch`.

## Технології / стек
- JavaScript (ES6+)
- Умовні оператори (`if...else`)
- Шаблонні рядки (template literals)
- Методи рядків: `length`, `toLowerCase()`, `slice()`
- Конструкція `switch`
- Повернення значень типу `boolean` та рядків

## Функціонал

| Файл       | Функція                        | Що робить функція                                                                 |
|------------|--------------------------------|------------------------------------------------------------------------------------|
| task-1.js  | `makeTransaction(quantity, pricePerDroid, customerCredits)` | Розрахунок вартості замовлення дроїдів + перевірка достатності кредитів на рахунку |
| task-2.js  | `formatMessage(message, maxLength)` | Обрізання рядка до заданої довжини з додаванням "..." (якщо потрібно)             |
| task-3.js  | `checkForSpam(message)`        | Перевірка повідомлення на наявність слів "spam" / "sale" (незалежно від регістру) |
| task-4.js  | `getShippingCost(country)`     | Визначення вартості доставки за країною (використовується `switch`)                |

## Приклади роботи (виведення в консоль)

Всі тестові виклики вже присутні в кінці кожного файлу та залишені для перевірки ментором.

Приклади результатів:

- `makeTransaction(5, 3000, 23000)` → "You ordered 5 droids worth 15000 credits!"
- `makeTransaction(10, 5000, 8000)` → "Insufficient funds!"
- `formatMessage("Curabitur ligula sapien", 16)` → "Curabitur ligula..."
- `checkForSpam("Amazing SalE, only tonight!")` → `true`
- `getShippingCost("Chile")` → "Shipping to Chile will cost 250 credits"
- `getShippingCost("Germany")` → "Sorry, there is no delivery to your country"

## Демо / перевірка

Демо можна переглянути за [посиланням](https://artemilliushchenko.github.io/goit-js-hw-02/)
