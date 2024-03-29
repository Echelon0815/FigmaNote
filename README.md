# Webdesign

文字不屬於 點陣圖or向量圖
重點：用色板、濾淨、疊圖...去做電腦自動選取、做遮色片。

# Photoshop 
1. 寬高 使用 像素   
2. 創新檔案→要大量處理不同檔案→可以勾選工作畫板   
3. 左下角`...`可以找到工具   
4. 上方`視窗(W)`也可以   
5. Photoshop 的 key feature 是`選取區`，固定我們做操作的範圍\\使用 選取→反轉 讓選取區完全反轉
6. 背景圖層是一個像素圖層 智慧型圖層也是，但是智慧型圖層不能被編輯，必須更改智慧型圖層的母檔   
7. 存檔時存檔到雲端，就可以使用 版本記錄功能 ，命名版本 回復到特定版本
8. 使用選取工具的時候 `shift`可以加選`alt`可以減選   
9. 做演算的智慧工具會破壞圖層，不能使用在智慧型圖層之上   
10. 圖層→解開鎖頭→圖層會從"文件"變成像素圖層。 圖層可以使用快速動作：去背→圖片會被分成兩的 圖層&遮色片   
11. 遮色片只利用 黑色和白色 在遮色片上使用黑色筆刷 就可以調整去背的範圍和透明度(透過黑色的黑白比例)   
12. 可以使用純色的背景 <img src="https://user-images.githubusercontent.com/95067506/202880386-ea1db158-6106-41fa-8d8c-a00af2a1b3ec.png" style="height:100px;width:100px">   
13. `ctrl+` `ctrl-` 或 `alt` 滾輪 可以調整縮放 `ctrl+r` 可以顯示或隱藏尺標   
14. 用選取工具 拉圓形或任何圖形 其起點都在圖形的左上角。如果要讓滑鼠所在位置變成中心，就加上`alt`鍵   
15. 用磁性套索//快速索取...先抓住特定物件，再到圖層下方 按下製作遮色片/色版的icon 就可以製作遮色片    
16. 影像→調整→符合顏色 可以用第二張圖調整圖片的色調   
17. 也可以在右下角色調部分建立遮色片去調整色調   
18. 可以用套索工具+ 編輯→內容感知填色 去修掉圖片中的特定物件   
19. 影像→影像尺寸→調整解析度(先不勾重新取樣)；調整完再勾 並調整新的大小
20. 檔案→指令碼→將檔案載入堆疊→轉存為 可以載入多張圖片，勾選多圖層一次轉存
21. 唯有路徑工具能輸出`svg`，點陣圖無法
22. 切片工具可以右鍵設定 下刀的位置，設定切線後，可以使用 檔案→轉存→儲存為網頁用
23. 可以從 視窗→時間軸 製作關鍵影格 再藉由 儲存為網頁用 做成`gif`檔 (記得設定顏色(bit)&邊緣調和(圖案邊緣))
24. 也可以用視訊時間軸→演算視訊 輸出影片<img src="https://user-images.githubusercontent.com/95067506/202997608-4c940930-fd24-44a1-8222-502494e2cec6.png" style="height:100px;width:100px">

## Figma

1. figma的工作區域，叫做frame，支援多種裝置類型，可以任意打斜，也可以放進其他frame做巢狀結構

2. frame 有 resize-to-fit 功能，可以縮小frame到符合內容的大小；這時候按 `ctrl+g`就可以組成群組，用`alt+滑鼠`控制整體大小

3. 使用`shift+r`顯示尺規，按住`alt`畫線，用`shift+滑鼠`拉出形狀。

4. 劃出圖案後，設定**__限制 constrains__** 可以讓物件在 frame 裏頭的大小或位置固定or變化

5. 按住 `alt` 可以移動複製 `ctrl+d`大量複製出對齊的圖形，就算亂掉也可以使用`tidy up` (`ctrl+shift+alt+t`)

6. 可以再畫出的圖形上，選取`fill`，將顏色 改成 圖片，將圖片塞入畫好的圖形中

7. 可以用 plugin `google sheet sync`，將畫好的名稱輸入成 #(試算表欄位名.編號) 就可以自動輸入表單中的連接(圖片) ![圖片](https://user-images.githubusercontent.com/95067506/203200269-c94659fb-d59e-428a-ba5d-c253d132f7cb.png)

8. 輸出(export)時，可以用slice輸出元件的一小部分，也可以只share一個元件或只輸出一個元件的圖檔

9. 要裁切圖片時，按住`ctrl`將frame拉成想要的大小，再在右手邊按下clip-contene 便可以裁切frame裏頭的內容，將多個元件拆開後組合(使用`右鍵→selection`)

10. 選取複數物件時，會啟用智慧選取，可以調整特定物件的大小或整理的間隔

11.移動物件時按住`space`，讓物件不會被塞進另一個物件裏頭

12. `i`是滴管

13. 操作向量工具時，按住`shift+x`，可以編輯路徑，編輯邊所在的位置 (inside,center,outline)

13. 操作向量工具時(雙擊物件以編輯)，刪除錨點時按住`shift`可以製作出一個"封閉"的圖形 沒按住則會就缺一角

14. 顏色，文字大小等等的設定，可以設定名字和內容，讓所有物件使用 <image src="https://user-images.githubusercontent.com/95067506/203242221-95e15831-d3cf-4e7f-8e46-138b1e20c0c2.png" style="height:100px;width:100px;">
  
15. 物件可以加上special effect如模糊、陰影 <image src="https://user-images.githubusercontent.com/95067506/203247290-ef244ed2-6643-4e9d-a0e4-70d3126d6ef4.png" style="height:100px;width:100px;">

16. 將物件製作成componet，將其複製，複製出來的物件叫做子元件，每當母元件被更改，所有子元件都會被更改(可以把母元件放進style guide)
 
17. 利用auto-layout 可以製造出類似flex的效果，簡單的排版<image src="https://user-images.githubusercontent.com/95067506/203250637-96e30e8a-4f12-432a-8889-23c65cfb0912.png" style="height:100px;width:100px;">
 
18. 包住兩個以上componet，可以用create variable components，便可讓figma知道這是同一份元件，只是有設定不同屬性名，爾後子元件就能直接變更屬性<image src="https://user-images.githubusercontent.com/95067506/203253822-b02e1d8c-d616-4599-9352-64561610f8e2.png" style="height:100px;width:100px;"><image src="https://user-images.githubusercontent.com/95067506/203256048-3b30bf9d-bf64-40dc-a658-15b2ff05e88c.png" style="height:100px;width:100px;">

  
19. 善用auto-layout 在各個母容器和子元素之間 (就像container vs item)，可以自由做出彈性或固定的排版 (寬會不會變)

20.  **__編輯子原件時，要先點右鍵→`detach instance`才能更改，並做成新原件__**
  
21. **__用Prototype可以互相連接不同物件作互動，不論是滾動，或連接到新物件__**
  
  
  <image src="https://user-images.githubusercontent.com/95067506/203725608-2835963d-1a69-4d51-9dfd-9e64105078f8.png" style="height:100px;width:100px;">※可以有多個Prototype設定,甚至可以做成逐格動畫










