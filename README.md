
# База телеграм-каналів русні

> Вебсайт в розробці | [Телеграм](https://t.me/rusnya_tg) — слідкувати за оновленнями

**Це — єдина база всіх «Z-каналів», пропагандистів, псевдо-українськіх каналів, ворожих батальонів, зборів, «воєнкорів» та всіх хто працює проти України на інформаційному фронті.**

Канали збираються методом парсингу репостів в російських каналах (русня репостить русню). Я постарався перевіряти кожен канал, але їх так багато, що міг десь і помилитися — пишіть якщо шось потрапило випадково.

З псевдо-українськими каналами найважче перевірити, тому тут я спираюся на те що публікували СБУ та інші.

Сподіваюся, що ця інформація стане в нагоді **журналістам, OSINT-дослідникам, правоохоронним органам** — та всім пильним громадянам. База постійно поповнюється, тому будь-ласка, при копіюванні залишайте посилання.

## TODO
 - [x] Дообробити списки СБУ та Центру протидії дезінформації
 - [ ] Обробити що там накидали Детектор медіа
 - [ ] Парсити, парсити і ще раз парсити
 - [ ] Зробити простенький вебсайт
 - [ ] Придумати що робити з каналами без юзернейму
 - [ ] Вигружати також зображення профілю?

## Як допомогти
- **Доповнюйте** базу каналами, які я пропустив. Поки що таких каналів ще
   дуже багато.
- Краще відправляти одразу **пачкою**, а не по одному :)
- Не треба кидати дуже малі канали, якщо це не шось важливе (наприклад, телеграми батальонів, зборів, тощо). Акцент на **5000+** тисяч підписників.
- Якщо ви зібрали канали автоматичним шляхом, будь-ласка, базово
   **перевірте** кожен канал, що це дійсно руснявий канал.
- **Розповсюджуйте** базу, щоб більше людей дізналися про її існування.

## Що я не додаю в базу (гайдлайн):
 - **Опозиційні** російські канали (приклад: Фейгин, Невзоров). 
 - Якщо людина просто **мудак** і підтримує війну (приклад: Артемий Лебедев), але канал присвячений іншій тематиці, і не займається активно висвітленням війни та пропагандою.
 - Українці, які критикують владу і тд. **Канал має бути очевидно руснявий**. Для тих каналів, що мімікрують під українців, орієнтуюся на списки СБУ і тд. Не хочу ні на кого випадково наклепати.

## Виключення (channel_exceptions.txt)
Під час перевірки каналів, деякі я не додаю в загальну базу, а закидую в channel_exceptions.txt (щоб парсер їх знову мені не видавав). Рішення тимчасове, в майбутньому треба буде придумати щось краще.

 - **Зовсім ліві** — канали, які взагалі не підходять по тематиці (наприклад, історичні) або попалися випадково (через рекламу, наприклад).
 - **Не про Україну** — сюди потрапляють русняві канали, які дуже мало торкаються теми України. Частина з них відверто пропагандистські, але направлені на іншу тематику. Можете додавати їх в свої дослідження.
 - **Нейтральні** — кидаю сюди окремі російські канали, які, як мені здалося, відносно нейтральні (Приклад: @bmpd_cast).
 - **Інше** — те що я не знаю куди дівати.
 - **Невеликі канали** — малих каналов дуже багато, вони з'являються і зникають, часто повторюють один одного, і якщо вони не представляють собою нічого особливого, я їх кидаю сюди, щоб не роздувати основну базу. Можете додавати їх в свої дослідження.

Поки що так, далі щось придумаю `¯\_(ツ)_/¯`

## Канали без юзернейму
Через те що база збиралася парсером, такі канали в неї поки що не потрапили. Якось треба зайнятися цим окремо.
