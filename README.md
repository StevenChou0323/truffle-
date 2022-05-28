# truffle-bug-fix

1.因為solidity寫的是0.7.0以上版本
但cmd內下truffle version
會看到箭頭指的地方是0.5.X(以下圖為修正後的版本)

![image](https://user-images.githubusercontent.com/17786940/170810698-a4474bd6-321e-4fdb-b396-d485df5da1c5.png)

此時要去truffle-config.js去改compile的版本即可

![image](https://user-images.githubusercontent.com/17786940/170810731-a1f3635d-5b3c-45d2-be71-73f6a8ebaaf4.png)

如果先做npm uninstall -g truffle 
再去過npm uninstall truffle發現這種爆錯
![image](https://user-images.githubusercontent.com/17786940/170810785-c039f385-a04c-4216-ab22-4ceab58eb32b.png)

記得先去下載vs code
然後安裝(推測可能是C++ dll檔案損毀導致安裝truffle失敗)
![image](https://user-images.githubusercontent.com/17786940/170810811-11b22abf-50db-44bc-a7d9-477d9724cd46.png)


參考來源:
1.https://forum.openzeppelin.com/t/how-to-change-truffle-default-solc-version-0-5-8/3010
2.https://stackoverflow.com/questions/70842716/getting-error-on-installing-truffle-on-windows-10-using-npm-install-truffle-g
