БОТ ПОМОЩНИК
Инструкция по использованию


Установка
Для работы бота помощника нужна версия python 3.9.0+
 

Функционал
Бот помощник позволяет сохранять/редактировать/удалять контакты и записки, узнавать, у кого из контактов в ближайшее время будет день рождения. А также умеет проводить сортировку в выбранной директории.


После установки бота помощника, его можно вызвать в консоле, введя команду(?????????????). 
Создайте свой первый контакт либо заметку. Для этого введите соответствующую команду (см. далее). 
После того как будет создан первый экземпляр контакта/заметки, станут доступны остальные функции контактов/заметок.

Чтобы взаимодействовать с ботом, нужно вводить команды в командную строку. Бот распознает не только точные команды, но и команды, написанные с несколькими ошибками, если совпадение с изначальным текстом команды 75% и более.

add_contact - Добавить контакт. Дополнительных аргументов вводить не нужно. Вы можете создать контакт только с именем и телефоном (обязательные поля) можете также добавить адрес, электронную почту, дату рождения. 
Поле “Телефон” имеет проверку на правильность введения, и будет сохранять введенные номера в формате +380*********, независимо, вводили вы код страны или нет. Можно добавить более чем один телефон.
Поле “Электронная почта” имеет проверку на правильность, состоящую в том, что должны использоваться английские буквы, присутствует символ @ и есть точка и названние домена не менее 2х символов
Поле “День рождения” проверяет, чтобы введенное количество дней/месяце не превышало 31/12.
У поля “Адрес” и “Имя” проверок нет

delete_contact - Удалить контакт. Вы вводите значение поля “Имя” контакта, и бот удаляет запись с таким названием.

change_contact - Изменить контакт. После вызова функции вам нужно будет ввести имя контакта, которое вы хотите изменить. Далее появиться выбор полей, которое вы хотите изменить. Для этого введите соответствующую цифру. Заполнение полей аналогично заполнению при создании контакта, за исключением того, что после каждого изменения, помощник будет спрашивать, нужно ли изменить что - то еще.

find_contact - найти контакт по имени и вывести его на экран.

show_contacts - функция выведения на экран записанных контактов. После вызова функции на экран выводятся все записанные контакты.

show_birthday - Выведение на экран контактов, у которых день рождения на этой  неделе. 

add_note - Добавить заметку. Вам нужно ввести имя заметки, ее содержание, можно добавить теги.

delete_note - Удаление заметки. Введите имя заметки и она будет удалена. (Если конечно вы ввели правильное имя)

change_note - Изменение существующей заметки. Введите имя заметки а потом имя поля, которое нужно изменить.

search_note - Поиск заметки по имени или тегу. Введите имя или тег, искомой заметки, что бы ее найти. 

show_notes - Вывод всех заметок на экран. (Если есть хоть одна)

