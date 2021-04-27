```uml
@startuml
start
:準備;
:駅に向かう;
:切符を買う;

if(日付==今日)then(true)
:「改札を通る」;
else
:改札を通れない;
endif


@enduml
```
