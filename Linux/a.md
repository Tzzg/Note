## grep 查询多行
### 查询上下
```
git log |grep "xxxx" -C 5
```


### 查询往后 after
```
git log |grep "xxxx" -A 5
```
### 查询往前 before
```$xslt
git log |grep "xxxx" -B 5
```


