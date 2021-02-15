# 01-03-01-WarriorProject
A fejlesztő csapat munkája után elkészült két osztály UML diagramja. Ön azt a feladatot kapta, hogy fejlessze ki az osztályokat!    

![alt text](https://github.com/csarp-dotnet-core-oop-feladatok/01-03-01-WarriorProject/blob/main/Warrior.png "UML diagram")    

Munkája ellenőrzéseként használja a következő kódot:   
```
Position position = new Position(2,-1);
position.ToConsole();
Warrior warrior = new Warrior("Peter the Iron Man", position);
warrior.ToConsole();
warrior.MoveHorizontal(3);
warrior.MoveVertical(-2);
warrior.ToConsole();'''
```

A kód kimenete a következő kell legyen:    
(2,-1)    
Peter the Iron Man, position (2,-1)    
Peter the Iron Man, position (5,-3)    
