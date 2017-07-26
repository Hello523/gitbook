# css换行问题解决方案
### 1.使用display解决

## html代码
```
<div>twrwwrwerwerwrwrwrwrwrwrwrwerwerwr</div>
```
## css代码
```
div{
    display: table;
    width: 100%;
    table-layout: fixed;
    word-wrap: break-word;
}
body{
    width:200px;
}
```
那么为什会在div里文本不换行呢？
