# REFramaworkExcel2Datarow


### - Excel 데이터(datatable)를 읽어 데이터(Datarow) 활용하기


#### 1. GetTransactionData
```
 - TransactionNumber가 1인 경우는 트랜젝션이 처음 도는 경우이다. 프로젝트를 처음 intialize할때 데이터를 저장해도 
 되지만 여기서 해도 상관없다.
 - 여기서 Excel 파일을 읽어 DataTable을 가져온다.
 - 현재의 트랜젝션 번호인 TransactionNumber 값 보다 가져온 DataTable의 row 수가 작다면 out_Transaction을 
 out_transaction으로 크다면 datatable을 넘어섰다는 의미가 되므로 out_transaction은 할게 없으니 Nothing으로 
 바꿔준다.
```

#### 2. Process
```
 - in_TransactionItem.Item("엑셀에서 불러올 colume명").ToString을 읽어서 반복될 작업을 수행하면 됨
```
 
