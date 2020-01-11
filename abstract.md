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

Asynchroner Code ist nie wirklich angenehm zu schreiben. Es verstecken sich dort zu oft subtile kleinere und größere Fehlerchen.
Async/await brachte hier in JavaScript eine große Erleichterung im Vergleich zu Callbacks und Promises. Der Code bleibt aber asynchron und ist somit erfahrungsgemäß immer noch fehlerträchtig.
Holger hat sich in seinen Projekten einmal zu oft über ein fehlendes await geärgert! Dies nimmt er nun zum Anlass sich noch einmal die Funktionsweise von async/await, dessen Historie, mögliche Fallstricke und Lösungen dafür anzuschauen. Hoffentlich ärgern wir uns dann nicht mehr so oft über ein fehlendes await.

## Vorkenntnisse:
Grundlegende JavaScript-Kenntnisse. 

## Lernziele:
Funktionsweise von Async/Await und Promises in JavaScript besser verstehen. Fehlern in asynchronem Code besser auf die Schliche kommen.

## Kurzbio
Holger ist seit über 15 Jahren passionierter Softwareentwickler. Fasziniert vom Web, egal ob JS-Frontend oder Java-Backend. Podcastet bei @autoweirdfm.