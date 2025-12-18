# SantaCode 🎅💻

歡迎來到工程師的交換禮物活動！
Welcome to the Programmer's Secret Santa!

## 📜 規則 (Rules)

1.  **目標 (Goal)**: 寫一個程式，執行後會在 Standard Output (stdout) 印出一棵聖誕樹。
    Write a program that prints a Christmas tree to stdout.
2. **語言 (Languages)**:
    - `.py (Python 3.13)`
    - `.js (Node 18)`
    - `.go (Go 1.23)`
    - `.rb (Ruby 3.3)`
    - `.sh (Alpine Shell)`
    - `.java (OpenJDK 17)`
    - `.kt (Kotlin 2.2)`
    - `.swift (Swift 5.8)`
    - `.c (GCC 12)`
    - `.cpp (G++ 12)`
    - `.cs (.NET 8.0)`
    - `.rs (Rust)`
3.  **限制 (Constraints)**:
    - **NO Internet**: 執行環境沒有網路。
    - **Standard Library Only**: 禁止安裝第三方套件 (`npm install`, `pip install` ... etc are NOT allowed)。
    - **Time Limit**: 5 秒內必須執行完畢。
    - **ID Match**: 資料夾名稱必須完全符合你的 GitHub ID。
    - **COC**: 請遵守[行為準則](https://www.facebook.com/groups/GDGKaohsiung/permalink/3401057450144799/)，違反者將會進入黑名單。

## 🚀 如何參加 (How to Join)

1.  **Fork Repo**: <a href="https://github.com/gdg-kh/SantaCode" style="color: white;">將本專案 Fork 到你的 GitHub。</a>
    *我們在 12/30 的開發者 Cafe 進行現場的 SantaCode 2025，歡迎一起參加，詳細資訊請看[高雄社群月曆](https://community-card.org/2026/calendar.html)*
2.  **Create Directory**: 在 `submissions/` 下建立一個你的 **GitHub ID** 資料夾 (e.g., `submissions/torvalds/`).
3.  **Write Code**: 放入你的程式碼 (e.g., `tree.py`)。
    *你可以參考 [submissions/example-santa/](submissions/example-santa/) 裡面的多語言範例檔案。*
4.  **Pull Request**: 發送 Pull Request。等待綠色勾勾 ✅。
5.  **📬 Watch Repository (重要！)**:
    - 點擊專案右上角的 **Watch** 按鈕
    - 選擇 **Custom** > 勾選 **Issues** ✅
    - ⚠️ **如果不 Watch，你將收不到交換完成的通知！**

## 🧪 本地測試 (Local Test)

如果你有裝 Docker，可以用以下指令模擬 CI 環境：

```bash
# Python example
docker run --rm --network none --memory 512m -v $(pwd)/submissions/YOUR_ID:/app -w /app python:3.13-slim python tree.py
```

## 🎁 交換 (Exchange)

活動截止後，Repo 管理員會按下「交換按鈕」。系統會自動亂數配對，並**自動創建 Issue 公告**！

### 📬 如何接收通知？

為了避免大量 @mention 造成困擾，我們使用 Issue 公告機制。請在參加後執行以下步驟：

1. 點擊本專案右上角的 **Watch** 按鈕
2. 選擇 **Custom** > 勾選 **Issues** ✅
3. 當交換完成時，你會自動收到通知！

這樣你就不會錯過任何更新，也不會被過多的通知打擾。
