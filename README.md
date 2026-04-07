# MiniX-Neo-Z83-4-Pro-Script
此腳本由Gemini AI生成，本人是Linux 小白，不會複雜命令。如果內容跟實際情況有誤差，敬請見諒

---

## 把**轉圈圈載入畫面**改為**Verbose噴字**模式
既然進不去桌面，我們要在開機的一瞬間攔截它：
1.  **先把執行檔移動到USB
1.  **強制重啟**：長按電源鍵關機，再開機。
1.  **進入 GRUB 選單**：在看到電腦品牌 Logo 時，瘋狂按 **`Esc`**（或 `Shift`）。
1.  **進入編輯模式**：看到選單後，選中第一項 `Linux Mint 22.3 Cinnamon/Xfce`，然後按鍵盤上的 **`e`** 進入編輯。
1.  **啟動**：按 **`Ctrl + X`** 或 **`F10`**。
1.  如成功進入桌面後，把**`z834_fix_boot.sh`**執行檔放在桌面，右鍵選Terminal，然後輸入：**`chmod +x final_z83_auto_boot.sh`**和**`sudo ./final_z83_auto_boot.sh`**命令。
    ```
    chmod +x final_z83_auto_boot.sh
    sudo ./final_z83_auto_boot.sh
    ```
這樣就能解決，一直卡住載入LOGO不會進入桌面問題。就能把轉圈圈載入畫面改為Verbose噴字模式。

---

為什麼會把MiniX Neo Z83-4 Pro把它Windows 10 Pro 系統換成Linux Mint 22.3?
因本機給家人使用Windows 10 長期處於空間不足，決定嘗試安裝Linux Mint 22.3 XCFE 版本。
但是安裝好系統，有一個問題解釋不到，也找不到解決方法，連Gemini AI 的腳本也沒辦法解決
```diff
- Mini PC 插入HDMI聽不到電視發出的聲音，只能用3.5mm插在Speaker收聽。
```
請教了Gemini  AI 解決不到，看有沒有人能幫我解決這個問題。

---

### 我當時的Z83-4 Pro Mini PC是官方贊助。
MiniX Neo Z83-4 Pro 是 2017年那時 香港MINIX總部有職員以Mail經Youtube Channel聯絡我。
當期時還在讀高中因個人無聊喜歡玩冷門的研究(怎樣用Kodi安裝和那些教程影片)，正好當時是樂視盒子和Kodi興起時期。
我的影片大多數沒有聲音，影片剪輯跟現在的剪片技術一樣屎(劣差)，但有一眾曾經支持過我的觀眾。
在MAIL約見 這樣就開始了，0$收入用他們產品贊助方式去錄製國中品質影片。
(沒合作之後才知道很多人都會收取費用拍攝，當時我沒有想太多 XD 只是為了好奇和興趣研究...)
