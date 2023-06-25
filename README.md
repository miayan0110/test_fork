# test_fork


📢 來熟悉一下git怎麼用


## 指令


- clone git repository from web
```
git clone url
```


- check branch
```
git status                  // check present branch
git checkout branch         // check specific branch
```


- add change
```
git add .                   // add all
git add file                // add file
```


- add comment
```
git commit -m "comment"
```


- push
```
git push
```
如果遠端資料庫上的資料版本比本地還新 使用push時就會出錯
要解決這個問題有兩種辦法
1. 先拉再推 先使用pull再push
> git push會將遠端資料庫的版本先拉下來並和本地端合併
>
> 合併過後的本地版本就會和遠端相同 這時自然能就使用git push
2. 強制執行
> 使用 git push -f / git push -force
>
> 強制執行git push會將遠端版本覆蓋掉 使用時須注意


- pull
```
git pull
```
會執行git fetch和git merge 相當於這兩個指令的結合


- fork

目前直接在遠端按下fork按鈕就行

fork之後自己的遠端資料庫中就會新增該專案