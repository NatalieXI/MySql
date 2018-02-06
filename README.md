# MySql
影响数据库的性能
## SQL四种隔离级别
1. READ UNCOMMITED(只要数据发生变化，还没有提交的数据也能读到)
2. READ COMMITED（能读到已提交的数据，因此一个事务当中重复读可能出现不一致的数据）
3. REPEATABLE READ（一个事务当中重复读的数据一致）
4. SERIALIZABLE(会对每行操作的数据进行加锁)
