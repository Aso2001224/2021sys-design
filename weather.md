```uml
@startuml
start
:天気情報 = 1;
if(天気情報== 0){
:晴れです;
}else if(天気情報 == 1){
:曇りです。;
}else if(天気情報 == 2){
:雨です;
}else{
:不明です。;
endif
end
@enduml
```
