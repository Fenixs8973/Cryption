Эта программа позволяет шифровать и дешифровать текст с помощью Афинского шифра.
С помощью ключей вычисляется сдвиг букв.
Ключи - набор цифр (до 9 цифр).
Для работы программы с БД, необходимо создать БД "cryption" и в программе нажать кнопку "Создать таблицы".
При шифровании и дешифровании текста, он, вместе с ключами и именем пользователя, записывается в БД.
Если авторизация в программе не выполнена, то отправка данных осуществляется через пользователя "default".
Для авторизации необходимо сначала зарегистрироваться, чтобы данные отправились в БД.
"Выгрузка из БД" - сохраняет имя пользователя, проводимую операцию над текстом, открытый(введенный) текст, закрытый(полученный) текст, первый ключ, второй ключ. 
Поле "Пароль пользователя БД" заполняется в случае, если пароль от базы данных не равен null
