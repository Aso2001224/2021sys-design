```startuml
@startuml 
!define MASTER_MARK_COLOR Orange 
!define TRANSACTION_MARK_COLOR DeepSkyBlue
entity "購入テーブル詳細" as purchase_detail<d_purchase_detail><<T,TRANSACTION_MARK_COLOR>>{
+ detail_id[PK]
--
order_id[FK]
item_code
price
num
};
<<T,TRANSACTION_MARK_COLOR>>
@enduml 
```
