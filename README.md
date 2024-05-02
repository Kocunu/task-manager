# task-manager

## Aufgabenstellung JS Task-Manager

Erstelle ein einfaches JS Programm, das als Taskamanger agiert.
Das Programm sol ausschließlich auf dem CLI verwendebar sein.
Kein HTML, CSS 

* Verwende dabei arrow Functions, ? conditions, und ES6 soweit wie möglich.

  
### Folgende Funktionen sollen möglich sein

* Hinzufügen von Aufgaben:
  * Mit der Funktion addTask("Einkaufen"); soll es möglich sein Tasks hinzu zu fügen
 
* Auflisten von Aufgabe
  * list(); soll es möglich sein alle Aufgaben die man vorhin gespeicher hat aufzulisten
 
* Löschen von Aufgebn
  * delete("Einkaufen"); löschen von Aufgaben es soll nur möglich sein Aufgaben zu löschen die ich auch vorhin hinzugefügut habe
 
Alles soll in CLI Ausgeführt werden, also beim der Funktions aufrufung
```js
addTask('Einkaufen');
addTask('Putzen');
listTasks();
deleteTask(2);
listTasks()
```
```bash
node main.js
Task "Einkaufen" added Succesfully
Task "Putzen" added Succesfulyy
Tasks:
1. Einkaufen
2. Putzen
Task: "Putzen" is deletet
Tasks:
1. Einkaufen
```

### Bonus Punkte

Mache die Funktions aufrufe Synchron das heisst du schreibst die Funktionen im 
CLI und rufst sie so auf ohne in den Code zu gehen nur im CLI.

