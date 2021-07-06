```startuml
@startuml erd
entity "購入テーブル詳細" as purchase_detail<d_purchase_detail><<T,TRANSACTION_MARK_COLOR>>{
+ detail_id[PK]
--
order_id[FK]
item_code
price
num
}
<<T,TRANSACTION_MARK_COLOR>>
@enduml 
```
