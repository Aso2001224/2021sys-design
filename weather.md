```uml
@startuml
:'天気情報 = 晴れ';
if(天気情報== 晴れ){
:晴れです;
}else if(天気情報 == 曇り){
:曇りです。;
}else if(天気情報 == 雨){
:雨です;
}else{
:不明です。;
endif
@enduml
```
