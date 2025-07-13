# Robot Graph Clear – Greedy Heuristics

Dieses Projekt beschäftigt sich mit dem **Robot Graph Clearing Problem**, einem kombinatorischen Optimierungsproblem mit Anwendungsbezug zur Überwachung, Reinigung und Durchsuchung von Netzwerken oder Gebäuden durch autonome Roboter.

Das Ziel besteht darin, einen gegebenen Graphen (bestehend aus Räumen und Durchgängen) mit möglichst wenigen Robotern vollständig zu „reinigen“, wobei bestimmte Regeln für das Betreten und Bewachen von Knoten und Kanten gelten.

## 🔍 Projektbeschreibung

Im Rahmen dieses Projekts wurden verschiedene **Greedy-Heuristiken** entwickelt und implementiert, um dieses Problem effizient zu lösen. Die Algorithmen entscheiden bei jedem Schritt lokal, welcher Knoten als nächstes besucht werden soll, unter anderem nach Kriterien wie:

- Minimale Anzahl an unbesuchten Nachbarn
- Minimale erwartete Roboterkosten

Außerdem wurden die Heuristiken durch Multi-Start und Rollout Ansätzen erweitert.

Die entwickelten Verfahren wurden auf verschiedenen Graph-Instanzen getestet und miteinander verglichen.

## 🧠 Entstehung

Der Code entstand im Rahmen einer **Gruppenarbeit** im Studium im Fachbereich Wirtschaftswissenschaften/ Algorithmen und Datenstrukturen. Ziel war es, verschiedene **Greedy-Heuristiken** zu entwerfen, umzusetzen und auf praktischen Testdaten zu evaluieren.


## 📊 Genutzte Instanzen

Die Testinstanzen wurden von folgenden Instanzen ausgewählt:

👉 *(https://github.com/Kurorororo/didp-models/tree/main/graph-clear)*

## 📚 Literatur

Theoretische Grundlagen und verwandte Arbeiten zum Robot Graph Clearing Problem finden sich unter anderem in folgenden Quellen:

👉 *(https://link.springer.com/article/10.1007/s10601-018-9288-3)*

