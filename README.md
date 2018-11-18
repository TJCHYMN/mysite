# mysite

## 簡介
此專案為練習Django之紀錄，並參考官網教學進行( https://docs.djangoproject.com/zh-hans/2.1/intro/tutorial01/ )，目前進度到第4部分。

## 環境需求
* Python 3.*
* Django



以下步驟以Windows系統為主(使用Power Shell)
### 創建虛擬環境(Windows)
```
cd ..
python -m venv django_venv
```

### 啟動虛擬環境(Windows)
#### 第一次啟動前先進行原則變更設定
以系統管理員開啟Power Shell，並輸入以下指令
```
Set-ExecutionPolicy RemoteSigned
```
#### 啟動venv
```
.\django_venv\Scripts\Activate.ps1
```

### 安裝Django
```
pip install django
```

### 啟動網站
```
python .\manage.py runserver
```




