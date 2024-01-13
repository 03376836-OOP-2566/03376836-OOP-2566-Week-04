# HOMEWORK 12/21/2023
```plantuml   
@startuml
class  Person{
-Name
-ID
+Tellname()
}
class Teacher{
Department
Teach()
}
class Student{
Stuid
Study()
}
class HouseKeeper{
compang
cleaning()
}
class Guard{
Safety()
}
Person <|-- Teacher
Person <|-- Student
Person <|-- HouseKeeper
Person <|-- Guard
@enduml
```
![image](https://github.com/likunzz/03376836-OOP-2566-Week-04/assets/144196696/de79d3dc-3441-4acb-9f48-8e404ac73d01)

