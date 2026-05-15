# AI_Animation_In_html

> 使用 AI 生成 HTML 演示動畫的 Prompt 模板集合

[Prompts](prompt.md)

---

## 專案簡介
<img width="2560" height="1440" alt="QQ_1775901765825" src="https://github.com/user-attachments/assets/77ee698e-7e88-43b7-b048-8eed006ed278" />
<img width="2560" height="1440" alt="QQ_1775901779039" src="https://github.com/user-attachments/assets/e06a3dc6-a57f-40f6-b88b-d4da2c049f45" />
<img width="2560" height="1440" alt="QQ_1775901789295" src="https://github.com/user-attachments/assets/657be29c-2770-46e2-8780-4d28712e3683" />

本專案整理了用於生成**炫酷 HTML 動畫網頁**的 AI Prompts，涵蓋動畫效果、3D 視覺化、PPT 風格演示、UI 美化等多個類別。

配合 `web_animation/` 中的示例檔案，可以快速生成用於：

- 📹 **影片創作** — AI City 系列影片的動畫演示
- 📚 **教學演示** — 技術概念的視覺化呈現
- 🔬 **技術科普** — 網路協議、神經網路等抽象概念的圖形化展示

---

## 目錄結構

```text
AI_Animation_In_html/
├── README.md           # 專案說明檔案
├── prompt.md           # Prompt 模板集合（分類整理）
├── original-prompt.txt # 原始 Prompt 文字
├── LICENSE             # MIT 開源協議
├── UI/                 # UI 設計參考圖
│   ├── design1.png ~ design6.png
│   └── timeline.png
└── web_animation/      # 示例 HTML 動畫檔案
    ├── AI Model/               # AI 模型演示（MLP、RNN、LSTM、GRU）
    ├── Animation/              # AI/ML 概念演示（RNN、LSTM、Word2Vec、GPU 等）
    ├── BG/                     # 背景樣式模板
    ├── catch the packet/       # 資料包捕獲演示
    ├── DHCP/                   # DHCP 協議演示
    ├── nice try/               # 實驗性 Demo
    ├── PPT Template/           # PPT 風格模板（基礎版，5 個）
    │   ├── PPT cover page.html
    │   ├── PPT-Generate-1.html
    │   ├── PPT-Generate-2.html
    │   ├── PPT-Generate-3.html
    │   └── PPT-Generate-4.html
    ├── PPT Template-level2/    # PPT 風格模板（進階版，27 個）
    │   └── 1.html ~ 9-3.html  # 多種佈局變體
    ├── 3D - demonstrate.html
    ├── AI_Animation.html       # AI-Animation Skill 輸出檔案
    ├── animation.html
    ├── ethernet-frame-animated.html
    ├── HTTPS.html
    ├── ipv4_datagram.html
    ├── ipv4_datagram - 3d.html
    ├── ppp_frame_complete.html
    ├── router-routing-table-animated.html
    ├── switch-mac-table-animated.html
    └── tcp-visualization.html
```

---

## 快速開始

### 方式一：直接使用示例

```bash
# 克隆倉庫
git clone https://github.com/c22329076/AI_Animation_In_html.git
cd AI_Animation_In_html

# 在瀏覽器中打開任意 .html 檔案
# 使用 ← → 方向鍵或滑鼠滾輪翻頁
```

### 方式二：AI 生成新動畫

1. 打開 [prompt.md](prompt.md)，選擇或修改合適的 Prompt
2. 將 Prompt 傳送給 AI（推薦 [Trae](https://trae.ai/)、Claude、GPT-4o）
3. 指定輸出檔案路徑
4. 在瀏覽器中預覽

**推薦 AI 工具：**

| 工具 | 特點 | 適合場景 |
|------|------|----------|
| [Trae](https://trae.ai/) | 免費，可直接生成 HTML | 快速生成 |
| Claude | 長上下文，程式碼質量高 | 複雜動畫 |
| Codex | 圖形理解能力強 | UI 重構 |

### 方式三：UI 參考重構

1. 在 `UI/` 資料夾中選擇設計風格
2. 使用 [prompt.md](prompt.md) 中「UI 置換」類 Prompt
3. 讓 AI 參考 UI 圖片進行視覺重構

---

## 示例預覽

| 檔案 | 主題 | 特點 |
|------|------|------|
| `tcp-visualization.html` | TCP 視覺化 | 3D 效果、互動演示 |
| `ipv4_datagram - 3d.html` | IPv4 資料包 | 3D 旋轉、動態展示 |
| `router-routing-table-animated.html` | 路由表 | 表格動畫、路徑高亮 |
| `Animation/RNN-*.html` | RNN 神經網路 | 分步動畫、概念視覺化 |
| `Animation/GPU.html` | GPU 架構 | 圖形化演示 |

---

## 技術棧

- **前端**：HTML5 + CSS3 + JavaScript（原生，無框架依賴）
- **動畫**：CSS Animation / Keyframes / 3D Transform
- **圖表**：純 CSS/JS 圖形繪製，無外部庫
- **相容性**：現代瀏覽器（Chrome、Firefox、Safari、Edge）

---

## 開源協議

本專案僅供學習和研究使用，請勿用於非法用途。
請勿用於商業用途。

---

## 致謝

- AI 工具：[Trae](https://trae.ai/)、Claude、ChatGPT 等
- 所有參與測試和反饋的社群成員>.^
