---
slug: shopify
categories: account_password
tags:
  - account_password
---
### 上傳工具網址

[http://192.168.1.3:3000/](http://192.168.1.3:3000/)

帳號/密碼 admin/123456

### NAS網址

[http://192.168.1.15:5003/](http://192.168.1.15:5003/)

shopify

Hs230927@

VPN

帳號: shopify

密碼:Hs230927@

ERP

app_key F09ADE0C-5791-458D-B36D-16EAA7EFFA4C

客戶代號 000015844601產品代號 OAPSP主機IP 192.168.1.6公司代號 HUSHANERP帳戶 DS

虎山ERP 主機連線(需先連到VPN)

```
ssh root@192.168.1.3
123@Inventec

安裝
curl -o- <https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh> | bash

github token
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
```

VPN 使用說明： [https://mail.google.com/mail/u/0/#inbox/FMfcgzQXKWgMStGkkHtCKxlRSGBhWChL](https://mail.google.com/mail/u/0/#inbox/FMfcgzQXKWgMStGkkHtCKxlRSGBhWChL)

ERP文件：[https://drive.google.com/drive/folders/1glA0OJB-Tn5rLGZPmL5ceUaOT71ipfPQ](https://drive.google.com/drive/folders/1glA0OJB-Tn5rLGZPmL5ceUaOT71ipfPQ)

```
shopify theme dev --store hushan-huhandle
```

重啟步驟

```
ssh root@192.168.1.3
123@Inventec

cd /var/www/hushan-erp-proxy/
pm2 start
pm2 list # 查看進程的狀態
pm2 restart # 重新開啟所有進程
```