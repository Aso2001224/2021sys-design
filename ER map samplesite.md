```startuml
@startuml 
!define MASTER_MARK_COLOR Orange 
!define TRANSACTION_MARK_COLOR DeepSkyBlue
!define MAIN_ENTITY #MintCream-MistyRose
entity "顧客マスタ" as customer<m_customers><<M,MASTER_MARK_COLOR>>{
+ customer_code[PK]
--
pass
name
address
tel
mail
del_flag
reg_date
}
entity "購入テーブル" as purchase<d_purchase><<T,TRANSACTION_MARK_COLOR>>{
+ order_id[PK]
--
customer_code[FK]
purchase_date
total_price
}
entity "購入詳細テーブル" as purchase_detail<d_purchase_detail><<T,TRANSACTION_MARK_COLOR>>{
+ detail_id[PK]
--
order_id[FK]
item_code
price
num
}

@enduml 
```
