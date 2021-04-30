```uml
@startuml
start
: 天気情報;
if(天気情報  < 1 )then(true){
:晴れです;
}else if(天気情報 < 2)then(false){
:曇りです。;
}else if(天気情報 < 3)then(false){
:雨です;
}else{
:不明です。;
endif
end
@enduml
```
