# EpicGames 自動白嫖每周免費遊戲
![image](https://user-images.githubusercontent.com/4411977/74479432-6a6d1b00-4eaf-11ea-930f-1b89e7135887.png)

## 使用教程
1. 下載[DeviceAuthGenerator](https://github.com/xMistt/DeviceAuthGenerator/releases/)
2. 啟動DeviceAuthGenerator，在開啟的瀏覽器視窗中登入Epic Games帳號並進行授權。完成後會在該資料夾生成"device_auths.json"的檔案
3. Fork或者手動導入這個Repository，看你喜好
4. 啟用Actions，創建一個叫做"AUTH_JSON"的Secret，並將之前的"device_auths.json"檔案内容貼上
5. 修改.github/workflows/claim.yml檔案，視自己的需求更動裡面的設置，例如修改自動領取時間之類的

## DeviceAuthGenerator相關附註
若對於其exe檔有安全疑慮的話也可以把他的程式下載下來以python自行檢查執行

## 致謝
感謝Revadike大佬的[epicgames-freebies-claimer](https://github.com/Revadike/epicgames-freebies-claimer),本Repository是在他設計的基礎上修改而来的
