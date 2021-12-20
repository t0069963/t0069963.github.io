- 储存格式發展
plain text->csv->csv->XML->JSON

- SQL tigger

- Subqueries

-資料異動

-資料一致性

-最佳化

-做報表

-nosql

DataNucleus

查NULL不能用 所以等於要用IS

Prepared Statements

DB最佳化

DCL(資料控制)
DDL(資料定義)
DML(資料操作)

固定資料跟不固定資料

<c:set var="numRows" value="${param.numRows}" />
<c:set>用於保存數據
<fmt:>用來格式化資料

EJB 重量級 把你編寫的軟體中那些需要執行制定的任務的類，不放到客戶端軟體上了，而是給他打成包放到一個伺服器上了

MYsql純中文存編碼要用 UTF8m64 不要用UTF8

mysqldump 備份資料結構或是資料

view是虛擬TABLE

盡量用:=做變數附值不要用 =

langth 是看位元
char_length 是看字元

CHAR() 最大255 bite
VARCHAR() 最大65535 bite -2 紀錄長度 -1 null

mysql 整數
bigint 64 
int 32
smailint 16
mediunint 24
tinyint 8

mysql 浮點數
float 32
double 64
decimal  128

mysql 時間time  -838:59:59 to 838:59:59

SALF UPDATA 可以用-U使用
防呆機制

沒有索引的話找資料會從頭找

Consistent 要有一致性

BEGIN 
UPDATE
INBERT
COMMIT or ROLLBACK

usertransaction

最佳化會因使用環境改變

loaddata infine


