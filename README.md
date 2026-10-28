# Software Engineering Methodology at ITMO University (2025-2027)



Стек:

* диаграммы выполнялись в Enterprise Architect 15 - UML Development Tool

## Диаграммы SAD

|Раздел|Материалы|
|-|-|
|4. Use Case View|[Варианты использования](Diagrams/UseCaseView/index.html), [классы](Diagrams/ClassDiagram/index.html), [активность](Diagrams/ActivityDiagram/index.html), [состояния](Diagrams/StateMachineDiagram/index.html), [последовательность](Diagrams/SequenceDiagram/index.html), [кооперация](Diagrams/CooperativeDiagram/index.html), [PNG](Images/UseCaseView), [нативный проект EA](Models/Casebook-Holmes-UseCase-View.eapx)|
|5. Logical View|[Общий HTML-отчёт](Diagrams/LogicalView/index.html), [состав раздела и отдельные отчёты](Diagrams/LogicalView/README.md), [PNG](Images/LogicalView), [нативный проект EA](Models/Casebook-Holmes-Logical-View.eapx)|

HTML-отчёты используют JavaScript для дерева модели. Для локального просмотра запустите в корне репозитория:

```powershell
py -m http.server 8765 --bind 127.0.0.1
```

Откройте `http://127.0.0.1:8765/Diagrams/LogicalView/` в браузере. На GitHub HTML-файлы отображаются как исходный код; PNG доступны для просмотра прямо в репозитории.

