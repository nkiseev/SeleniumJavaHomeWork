# ST-Lesson_11

Software-Testing.Ru LMS<br />
Группа: sel-1<br />
<h2>Задание 11. Сделайте сценарий регистрации пользователя</h2>

**Сделайте сценарий для регистрации нового пользователя в учебном приложении litecart (не в админке, а в клиентской части магазина).**

Сценарий должен состоять из следующих частей:

1. регистрация новой учётной записи с достаточно уникальным адресом электронной почты (чтобы не конфликтовало с ранее созданными пользователями),
2. выход (logout), потому что после успешной регистрации автоматически происходит вход,
3. повторный вход в только что созданную учётную запись,
4. и ещё раз выход.

*Проверки можно никакие не делать, только действия -- заполнение полей, нажатия на кнопки и ссылки. Если сценарий дошёл до конца, то есть созданный пользователь смог выполнить вход и выход -- значит создание прошло успешно.*

*В форме регистрации есть капча, её нужно отключить в админке учебного приложения на вкладке Settings -> Security.*