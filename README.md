
![Картинка](https://github.com/user-attachments/assets/4b9b233e-e146-4274-b746-9fae0a6888c2)

<code>
@startuml
left to right direction
actor "Денежный мешок" as client
actor "Т-банк" as gaf
rectangle ВсеМойки.ру  {
usecase "Управлять своим профилем " as UC1
usecase "Управлять своим авто " as UC2
usecase "Выбирать город" as UC3
usecase "Выбирать мойку" as UC4
usecase "дата время" as UC5
usecase "способ оплаты" as UC6
usecase "оплачивать" as UC7
usecase "отменять" as UC8
}
client --> UC1
client --> UC2
client --> UC3
client --> UC4
client --> UC5
client --> UC6
client --> UC7
client --> UC8
UC7 --> gaf
@enduml
</code>
 # User story
<p>
 Как пользователь, я хочу иметь возможность легко синхронизировать данные моего приложения на нескольких устройствах, чтобы я мог получать доступ к своей информации из любой точки мира.

Как социофоб, я хочу иметь возможность онлайн записи, чтобы быть уверенным, что у меня будет минимум социальных контактов

</p>
