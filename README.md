# Airline-Passenger-Satisfaction
## Objective
Ushbu loyihaning maqsadi yoki maqsadi aviakompaniyani mijoz yoki yo'lovchilar qoniqishiga ta'sir qiluvchi muhim omillarni aniqlashga yo'naltirishdir. <br/>
Mijozlarning qoniqishi kompaniyaning biznesiga ta'sir qilishda katta rol o'ynaydi, shuning uchun mijozlar ehtiyojini qondirish bilan chambarchas bog'liq bo'lgan omillarni tahlil qilish va takomillashtirish kompaniyaning o'sishi va obro'si uchun muhimdir. <br/>

*Ushbu loyihada* ***CRISP-DM metodologiyasi*** *biznes muammosiga tegishli yechim topish uchun amalga oshiriladi. U olti bosqichda amalga oshiriladi - biznesni tushunish, ma'lumotlarni tushunish, ma'lumotlarni tayyorlash, ma'lumotlarni modellashtirish, baholash va joylashtirish.*

## About Data
Ushbu loyiha uchun ma'lumotlar to'plami Kaggle'dan olingan bo'lib, u turli omillarga asoslangan yo'lovchilar/mijozlarning qoniqish darajasi bo'yicha aviakompaniyalar tomonidan o'tkazilgan so'rovdan olingan ma'lumotlarni o'z ichiga oladi. Maʼlumotlar toʻplami Yosh, jins, sayohat klassi, kelish va joʻnab ketish kechikishlari kabi 25 ta ustundan, shuningdek, bortda xizmat koʻrsatish, tozalik, oʻrindiqning qulayligi, yukni tashish va h.k. kabi mijozlar qoniqish darajasiga taʼsir qiluvchi xususiyatlardan iborat. <br/>
Ma'lumotlar to'plami mijozning umumiy qoniqish darajasini tavsiflovchi *** "qoniqish"*** nomli ustun yoki xususiyatdan iborat. U ikkita qiymatga ega: "neytral yoki norozi" va "qoniqarli". Bu ***qoniqish*** xususiyati yorliq xususiyati hisoblanadi, chunki u boshqa funksiyalar uchun berilgan baholar asosida mijozning umumiy tajribasini bildiradi. Ma'lumotlar to'plami mos ravishda poezd va testdagi 103904 va 25976 yozuvlardan iborat.

## Data Cleaning and Visualisation
Ma'lumotlarni tozalash mashinani o'rganish modelining natijasini olishda muhim rol o'ynaydi. Odatda ma'lumotlarni tozalash chegaralarni aniqlash va o'chirish yoki yo'q qilish, etishmayotgan qiymatlarni o'chirish yoki almashtirish, takroriy qiymatlarni o'chirish, ahamiyatsiz yoki ahamiyatsiz qiymatlarni o'chirish kabi jarayonlardan iborat. <br/>
Ushbu loyihada *"Daqiqalarda yetib borish kechikishi"* ustunida 310 ta etishmayotgan qiymat mavjud. Ushbu etishmayotgan qiymatlar bir xil ustunning etishmayotgan qiymatlarining o'rtacha qiymatlari bilan hisoblanadi. <br/>
Ma'lumotlarni vizualizatsiya qilish ma'lumotlarni tushunishda muhim rol o'ynaydi, chunki u modelni amalga oshirishdan oldin ma'lumotlarning umumiy ko'rinishini beradi. Ma'lumotlar to'plami uchun tadqiqot ma'lumotlarini tahlil qilish amalga oshiriladi.

## Feature Selection
Xususiyatlar orasidagi korrelyatsiya korrelyatsiya xaritasini yaratish orqali topiladi. Eng yaxshi o'nta xususiyat Chi-Square usuli yordamida tanlanadi. Xususiyatlarning ahamiyati Wrapper usuli va xususiyatni almashtirish muhimlik texnikasi yordamida aniqlanadi.

## Models
Maksimal samaradorlikni tekshirish uchun ushbu loyihada sakkizta modeldan foydalaniladi. Ular,
- Logistic Regression
- Naive Bayes
- KNN
- Decision Tree
- Neural Network
- Random Forest
- XGBoost
- AdaBoost

## Conclusion
Random Forest va AdaBoost teng darajada ishladi va yuqori ROC_AUC ball (~ 90%) ishlab chiqdi. Ammo *** Tasodifiy o'rmon*** AdaBoost tomonidan olingan vaqtga qaraganda kamroq vaqt oldi. Shunday qilib, Random Forest eng yaxshi model deb xulosa qilishimiz mumkin. <br/>


###### ***Izoh: Bu mening Suniy Intelect hamda Data Since moduli bo'yicha amaliy topshirig'imning bir qismi edi - talaba: Abdualimov Botir Anarboy o'g'li tomonidan tayyorlandi. O'zbekiston Milliy Universiteti Jizzax filiali Talabasi hamda Jizzax shahar 1- sonli maktab informatika o'qituvchisi, Jizzax:2023.***

