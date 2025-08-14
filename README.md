# 🖥️ threejs-inspect-server-room

一個使用 [Three.js](https://threejs.org/) 製作的互動式 3D 專案，  
提供 **第一人稱漫遊**、**碰撞偵測**、**物件標註** 與 **遮擋檢查** 功能，  
讓你可以在虛擬「伺服器機房」中自由探索並添加註解。

---

## ✨ 功能特色
- 🎮 **第一人稱移動**：鍵盤 / 螢幕按鈕控制移動、旋轉、抬頭低頭  
- 🛑 **碰撞偵測**：不可穿牆，模擬真實移動體驗  
- 🏷 **標註系統**：點擊物件新增標籤與文字說明  
- 👀 **遮擋判斷**：標籤被物件擋住時自動隱藏  
- 🌐 **Web 部署**：可直接使用 GitHub Pages 預覽

---

## 📷 預覽
<img width="595" height="344" alt="截圖 2025-08-14 下午3 56 32" src="https://github.com/user-attachments/assets/6d972c25-b75d-47ec-b306-0fbc2c68857c" />

---

## 📦 安裝與執行

### 1️⃣ 下載專案
git clone<br>
cd threejs-inspect-server-room

### 2️⃣ 啟動本地伺服器
建議使用 VS Code + Live Server 外掛，或用任意靜態伺服器：<br>
npx http-server .
### 3️⃣ 瀏覽器開啟

## 📂 3D 模型來源
本專案的伺服器機房 GLB 檔案來自 Sketchfab<br>
🔗 [Server Room – by BlackIceHUN](https://sketchfab.com/3d-models/server-room-57a480597a20476f9f303fda4a089f86) 

## 🛠 技術細節
Three.js – 3D 場景建立與渲染<br>
GLTFLoader – 載入 .glb 格式模型<br>
CSS2DRenderer – 渲染 2D 標籤（可互動）<br>
Raycaster – 用於碰撞偵測與物件點擊選取

