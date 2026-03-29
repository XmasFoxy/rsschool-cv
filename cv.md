# *Anton Andreykovets*

## *Front-End Developer* (in the future ^_^)

---

### Контакты
- **Телефон:** +375 (29) 777-77-77  
- **Email:** royalhsik@gmail.com  
- **Telegram:** @XmasFox  
- **GitHub:** [XmasFoxy](https://github.com/XmasFoxy)

---

### Обо мне

Начинающий разработчик, который любит:

- **Спорт** – футбол, волейбол, настольный теннис, баскетбол, шахматы  
- **Животных** – особенно лис 🦊  
- **Музыку** – любимый артист: JuiceWRLD  
- **Вредные привычки** – фастфуд (стараюсь реже)

---

### Навыки
- HTML  
- CSS  
- JavaScript (основы)  
- Git (основы)

---

### Опыт работы

> Ведущий инженер по информационной безопасности.  
> Знаю, как работают сети и интернет, домены, firewalls, DLP/PAM-системы.  
> Сейчас стремлюсь стать *Front-End разработчиком*.

---

### Языки
- Английский – *B1*  
- Русский – *Родной*  
- Белорусский – *Родной*

---

### Образование

Выпускник **Белорусского государственного университета транспорта**  
Специальность: *Программист, бизнес-аналитик*  
Изучаю английский через Duolingo

---

### Пример кода на JavaScript

**Задача:** Написать функцию, которая проверяет, является ли слово палиндромом.

```javascript
// Решение: функция проверки палиндрома
function isPalindrome(word) {
  const cleaned = word.toLowerCase().replace(/[^а-яa-z]/g, '');
  const reversed = cleaned.split('').reverse().join('');
  return cleaned === reversed;
}

// Проверка
console.log(isPalindrome('казак'));     // true
console.log(isPalindrome('привет'));    // false
console.log(isPalindrome('A man, a plan, a canal, panama')); // true
