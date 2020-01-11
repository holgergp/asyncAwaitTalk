##Outline
- Das ist einer der häufigste Fehler, den ich Code von JS Neulingen sehe, aber auch bei alten Hasen.
  - Da müssen wir was machen. 
- Warum async/await
  - Welches Problem lösen wir?
    - Asynchrone Programmierung in JavaScript
  - Historie
    - Callbacks
    - Promises
  - Async/Await
    - Welche Probleme löst Async/Await
- Wann wird Async/Await zum Problem
  - Ist das asynchron? Sieht synchron aus
  - Triviales Problem, aber große Auswirkung, schwer zu finden
  - Beispiel
- Wie gehe ich damit um
  - Ist async/await immer das Richtige?
    - Manchmal machen Promises oder vielleicht auch Callbacks durchaus Sinn.
  - Verstehen (Brain-Mode on)
  - IDE Unterstützung
  - Linter
    - Missing async selten ein Problem
    - Missing await
      - No-Floating-Promises
  - Unit Tests
  - Bonus Content Callback auf Await umbauen

## Abstract
Da fehlt noch ein await: async/await und Promises zähmen.

 Asynchronen Code zu schreiben ist nun wirklich nicht angenehm. Zu oft verstecken sich dort subtile, kleine und größere Fehlerchen, die dann mit dem ein oder anderen Ärgernis verbunden sind. In Vergleich zu Callbacks und Promises brachte async/await bereits eine große Erleichterung mit sich. Der Code bleibt jedoch asynchron und ist erfahrungsgemäß immer noch fehleranfällig.
Holger hat sich in seinen Projekten einmal zu oft über ein fehlendes await geärgert! Dies nimmt er es sich zum Anlass, um die Funktionsweise von async/await und dessen Historie noch einmal genauer zu betrachten. Er wird außerdem häufige Fallstricke und mögliche Lösungswege vorstellen. Danach ärgern wir uns alle hoffentlich seltener über ein fehlendes await.


## Vorkenntnisse:
Grundlegende JavaScript-Kenntnisse. 

## Lernziele:
Funktionsweise von Async/Await und Promises in JavaScript besser verstehen. Fehlern in asynchronem Code besser auf die Schliche kommen.

## Kurzbio
Holger ist seit über 15 Jahren passionierter Softwareentwickler. Fasziniert vom Web, egal ob JS-Frontend oder Java-Backend. Podcastet bei @autoweirdfm.