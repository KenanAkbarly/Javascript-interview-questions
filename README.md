# JS Interview Sualları

Bu repo bir frontend developerin real müsahibəyə hazırlaşarkən topladığı 499 JavaScript sualından ibarətdir. Hər sualın yanında intervyuda çıxma ehtimalı var — bu faizlər rəsmi bir mənbədən deyil, real müsahibə təcrübələrinə, populyar sual toplusuna və mövzu çəkiliyinə əsaslanır.

---

## Necə istifadə etmək olar?

`js_interview_questions.html` faylını brauzerdə aç. Axtarış qutusuna mövzu yaz (məsələn `closure`, `this`, `async`) və ya filterlər ilə sualları daralt:

- **≥75%** — bunları bilməsən müsahibə çətin keçər
- **≥60%** — standart middle/senior suallardır
- **≥40%** — gəlir, amma hər yerdə deyil
- **★ işarəli** — orijinal faylın müəllifi tərəfindən əlavə edilmiş suallar

---

## Mövzular

Suallar 31 mövzuya bölünüb:

| #   | Mövzu                 | Nə qədər vacib |
| --- | --------------------- | -------------- |
| 1   | JS Əsaslar            | Orta           |
| 2   | Tiplər                | Orta           |
| 3   | Operatorlar           | Aşağı–Orta     |
| 4   | Scope & Hoisting      | **Yüksək**     |
| 5   | Funksiyalar           | **Yüksək**     |
| 6   | this & Binding        | **Kritik**     |
| 7   | Closure               | **Kritik**     |
| 8   | Prototype & OOP       | **Kritik**     |
| 9   | Object Metodları      | Yüksək         |
| 10  | Array                 | Yüksək         |
| 11  | String                | Orta           |
| 12  | Destructuring         | Orta–Yüksək    |
| 13  | Async JS              | **Kritik**     |
| 14  | Event Loop            | **Kritik**     |
| 15  | Generators            | Orta           |
| 16  | Modules               | Orta–Yüksək    |
| 17  | Error Handling        | Orta           |
| 18  | Regex                 | Aşağı          |
| 19  | Strict Mode           | Aşağı–Orta     |
| 20  | Map & Set             | Orta           |
| 21  | DOM & Events          | Yüksək         |
| 22  | BOM                   | Aşağı–Orta     |
| 23  | Storage & Cookies     | Orta           |
| 24  | Service Workers & PWA | Aşağı–Orta     |
| 25  | Network & HTTP        | Yüksək         |
| 26  | JSON                  | Orta           |
| 27  | Performans            | **Yüksək**     |
| 28  | Console & Utils       | Aşağı          |
| 29  | TypeScript            | **Yüksək**     |
| 30  | RxJS                  | Orta           |
| 31  | Digər                 | Qarışıq        |

---

## Hansı mövzudan başlamaq lazımdır?

Vaxtın məhduddursa, prioritetlərini belə düz:

1. **this & Binding** — `call/apply/bind`, arrow vs regular, `new` binding. Demək olar hər müsahibədə çıxır.
2. **Closure** — sadəcə tərifi bilmək kifayət etmir. Loop bug-ını, memory leak-i, praktik use case-ləri bil.
3. **Event Loop** — `setTimeout(0)` vs `Promise.resolve()` sualı klassikdir. Macrotask/microtask fərqini izah edə bilməlisən.
4. **Async JS** — `Promise.all` vs `allSettled`, `async/await` error handling, parallel işlətmə.
5. **Prototype & OOP** — `__proto__` vs `prototype`, classical vs prototypal inheritance.
6. **TypeScript** — `interface` vs `type`, generics, `any/unknown/never`. Senior müsahibələrdə TypeScript artıq standartdır.
7. **Performans** — debouncing/throttling, memory leak-lər, lazy loading. Real layihə təcrübəsi ilə əlaqəli suallar.

---

## Bir qeyd

Bu sualların hamısına hazırlaşmaq məcburi deyil — xüsusilə aşağı ehtimallı hissə. Məqsəd hər şeyi əzbərləmək yox, konseptləri başa düşmək və öz sözlərinlə izah edə bilməkdir.

Müsahibədə ən çox uğur gətirən şey: sualın cavabını bilməsən belə, necə düşündüyünü göstərə bilmək.

---

## Fayl strukturu

```
📄 js_interview_questions.html   ← İnteraktiv axtarış interfeysi
📄 README.md                     ← Bu fayl
```

---

Uğurlar! 🚀
