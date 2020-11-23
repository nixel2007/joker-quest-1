Infobip Joker 2020 Quest 1 
=====================
 
В этом квесте Вам нужно помочь разработчику Валере найти в базе данных дубликаты транзакций.
 
Для этого выполните три шага:

* Чтобы не хранить пароль к базе данных в открытом виде его зашифровали, 
однако реализация алгоритма шифрования отсутствует, имплементируйте метод
`SecretDecrypter.decrypt`
* В проекте уже есть репозиторий транзакций, добавьте метод возвращающий дубликаты
`TransactionsRepository.findDuplicates`
* Список транзакций является ответом квеста, внесите его в эту [форму](https://forms.office.com/Pages/ResponsePage.aspx?id=hgrv93kxzEeEl_O13Q0p-mdhyP2HxxdAu1hjtHc3TOBUNDlTNEJUVE40TzhZQ1lHVjFHNFZHS1VIRS4u).

Installation
------------
Данный проект представляет собой Spring Boot приложение.
```$xslt
$ git clone git@github.com:infobip/joker-quest-1
$ cd joker-quest-1
$ ./mvnw install 
```
```$xslt
$ ./mvnw spring-boot:run
```
