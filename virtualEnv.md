# Virtual Environment 
為了下次換機的時候，不用重新 google 的小筆記
- lang : Python3 
- IDE : VScode

## 安裝 pyenv & virtualenv
### pyenv
```

```
### virtualenv
```python
pip3 install virtualenv
```
## 環境設置

1. 列出可供下載的版號

    `pyenv install --list`

2. 下載

    `pyenv install 3.x.x`

3. 查看目前 pyenv 擁有的版號
    `pyenv persions`
    - 下載前
    
        只有 **＊system**

        ![下載前](../PYnote/img/virtualEnv1.png)

    - 下載後

        ![下載後](../PYnote/img/virtualEnv2.png)

4. 換到所需版後

    `pyenv global 3.x.x`
    
    - global : 全域設定
    - local : 區域設定
    - shell : 當前 shell 設定

    