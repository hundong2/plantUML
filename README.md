# plantUML
plant UML document test page

@startuml
actor User1
database DB1
actor User2

User1 -> DB1 : BEGIN
User1 -> DB1 : INSERT [value name]
User2 -> DB1 : SELET FROM [name]
User2 <- DB1 : [value]
User1 -> DB1 : Commit

@enduml