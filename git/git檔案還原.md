

在過去的git版本，checkout除了能夠用來切換分支之外，也能夠進行檔案的還原。而後續為了避免指令的混淆，分支的切換可以利用`switch`來替代，而檔案的還原也能夠用`restore`來處理。


+ `--worktree` - 捨棄當前工作區的修改，直接將這個修改回復到`該檔案`上一次commit的狀態

```bash
git restore --worktree <filename>
```

在使用`restore`指令時，他預設的模式會是還原worktree中的檔案或資料夾。也就是說，以下指令其實跟上面指令具有相同的作用
```bash
git restore <filename>
```

那如果今天檔案已經被加入到暫存區中變成stage的狀態了呢?只要在使用restore時，加上`--stage`的參數，就可以對暫存區的內容進行還原!

```bash
git restore --staged <filename>
```

藉由兩個參數`worktree`、`stage`，來達成還原。