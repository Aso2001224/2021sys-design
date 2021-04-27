```start
@startuml
start
if(昨日弁当を食べた)then(Yes)
:今日はゼリー飲料だ;
else if(昨日何も食べてない)then(Yes)
:お昼は弁当だ;
else(No)
:お昼はパンだ;

endif
stop

@enduml
```
