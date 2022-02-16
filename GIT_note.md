# Git基本流程

- 安裝git : install git
- 設定基本資料 : git config(和github連接)
    - nickname
    - email
- 資料夾git 初始化 : git init
    - 暫存區 : 調整那些檔案要做版控(暫存區外->暫存區內) : git add 檔案名稱
    - 儲存庫(本地) : 從暫存區移到儲存庫   : git commit
    - 儲存庫(雲端) : 從本地上傳到github   : git push

- 雲端(Github)拉東西到本地 : 
    - 第一次拉 : git clone
    - 之後每次拉 : git pull

# 多人開發branch

- master------1/1-----------1/2---------1/3
               |
             branch(dev)1/1-------1/1上午-------1/1下午     

- master : 先做好環境配置(index.html, about.html, header.html, footer.html)
- 開dev分支 : 每位開發人員都從這個dev中開一支自己的分支

- EX:
            __(2)merge__
            |          |
master---- dev ------ devA -------------- devB -----devC
                       |push(1)             |pull(3)
                      index                index


# source tree
- add 加入既有的儲存庫
- create 從無到有
- commit 輸入上傳註解
- push  上傳到github
- branch 建立分支

