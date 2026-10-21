<div align="center">

# 👋 Xin chào, tôi là Vương Quốc Hòa (Vuong Quoc Hoa)
### 🚀 Junior Applied AI & Full-Stack Software Engineer
**Đại học Công nghệ TP.HCM (HUTECH) — Chuyên ngành Trí tuệ Nhân tạo (2025 - 2029)**

[![Portfolio](https://img.shields.io/badge/Live-Portfolio%20Website-00f0ff?style=for-the-badge&logo=google-chrome&logoColor=black)](https://vuongquochoa.github.io/portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-VuongQuocHoa-181717?style=for-the-badge&logo=github)](https://github.com/VuongQuocHoa)
[![Email](https://img.shields.io/badge/Email-hoalkasd%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hoalkasd@gmail.com)
[![Phone](https://img.shields.io/badge/Phone%20%2F%20Zalo-0399911382-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:0399911382)

<p align="center">
  <em>"Thu hẹp khoảng cách giữa mô hình AI lý thuyết và hệ thống sản xuất thực tế (Production Systems) — Tối ưu hóa suy luận biên (Edge AI), loại bỏ nghẽn cổ chai thời gian thực và kiến trúc phần mềm chuẩn mực."</em>
</p>

</div>

---

## 🛠️ Công Nghệ & Nền Tảng Kỹ Thuật (Tech Stack)

<div align="center">

| Lĩnh vực | Công nghệ cốt lõi & Frameworks |
| :--- | :--- |
| **Edge AI & Computer Vision** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![YOLOv11](https://img.shields.io/badge/YOLOv11-00FFFF?style=flat-square&logoColor=black) ![InsightFace](https://img.shields.io/badge/InsightFace-FF6F00?style=flat-square) |
| **Tối ưu hóa & Lượng tử hóa** | ![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white) ![OpenVINO](https://img.shields.io/badge/OpenVINO-00C7FD?style=flat-square&logo=intel&logoColor=white) ![INT8 PTQ](https://img.shields.io/badge/INT8_Quantization-10B981?style=flat-square) ![Decoupled 60FPS](https://img.shields.io/badge/Decoupled_Pipeline-60_FPS-purple?style=flat-square) |
| **GenAI & Autonomous Agents** | ![Coze API](https://img.shields.io/badge/Coze_API_v3-Streaming_SSE-blueviolet?style=flat-square) ![Gemini](https://img.shields.io/badge/Google_Gemini_1.5-8E75C2?style=flat-square&logo=google&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_Storage-orange?style=flat-square) |
| **Backend & Microservices** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Frontend, Mobile & UI** | ![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![JavaScript](https://img.shields.io/badge/Vanilla_JS-ES6_Modules-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Android APK](https://img.shields.io/badge/Android_CyberHUD-APK-3DDC84?style=flat-square&logo=android&logoColor=white) |

</div>

---

## 🌟 Các Dự Án Thực Chiến Nổi Bật (Featured Engineering Projects)

### 1. [🚀 Lockheed DACS — Xưởng Lắp Ráp & Đánh Chặn Tên Lửa 3D](https://github.com/VuongQuocHoa/lockheed-dacs)
> **Mô phỏng đồ họa 3D WebGL (Three.js), lắp ráp 6 mô-đun & Hệ thống xung lực ngang Lockheed Martin DACS**
- **Đồ họa & Vật lý:** Xây dựng bằng **Three.js (WebGL)**, mô phỏng 6 bậc tự do, định luật dẫn đường tỷ lệ (Proportional Navigation), bẻ hướng siêu thanh bằng các vòi xả khí $O_2$ ngang DACS.
- **Trải nghiệm game:** Cơ chế điều khiển camera TPS bẻ hướng theo chuột (chuẩn **PUBG / Free Fire** với Pointer Lock API), làm chậm thời gian **Bullet-Time 0.2x [Q]** và bộ tổng hợp âm thanh thủ tục bằng **WebAudio API**.
- **Demo:** Mở trực tiếp [index.html](https://github.com/VuongQuocHoa/lockheed-dacs) hoặc chạy máy chủ Node.js (`npm start`).

### 2. [⚖️ Edge AI Predict Mass](https://github.com/VuongQuocHoa/predict-mass)
> **Dự đoán khối lượng vật thể 3D qua Camera & AI học máy theo 5 giai đoạn công nghiệp**
- **Điểm đột phá:** Kiến trúc **Decoupled Asynchronous Pipeline** tách luồng Camera Grabber (60 FPS) khỏi luồng AI Worker (35 FPS), triệt tiêu 100% độ trễ tích lũy khung hình (< 17ms latency).
- **Thuật toán:** Phân đoạn mặt nạ YOLOv11n-seg, khớp Ellipse fitting, tính tỷ lệ Pixel-to-Metric (PPM) qua ArUco Marker 50mm, bù góc nghiêng quang học $\cos(\theta)$ và mạng nơ-ron hồi quy MLP 12 chiều đặc trưng.
- **Tối ưu phần cứng:** Lượng tử hóa sau huấn luyện (PTQ) FP32 sang **INT8** bằng ONNX Runtime, giảm 50% RAM và tăng tốc 1.8x qua OpenVINO Execution Provider.
- **Demo:** Giao diện Streamlit Dashboard thời gian thực (`app.py`) & script camera công nghiệp (`run_camera.py`).

### 2. [👁️ InsightFace FaceID CyberHUD](https://github.com/VuongQuocHoa/detect-face)
> **Microservice nhận diện khuôn mặt FastAPI + ChromaDB Vector Storage + Android CyberHUD APK**
- **Kiến trúc:** Dịch vụ REST API bất đồng bộ trích xuất 512D embedding bằng InsightFace (Buffalo_l), chuẩn hóa L2 và đối soát độ tương đồng Cosine Similarity trên ChromaDB Persistent Database.
- **Client Di động:** Đóng gói ứng dụng độc lập **FaceID CyberHUD APK** cho điện thoại Android, tự động kết nối AI server qua mạng Wi-Fi nội bộ (LAN).
- **Thuật toán ổn định:** Bộ lọc chống nhiễu *anti-ghosting* và *stranger pinning* chống rung giật khung hình khi người dùng di chuyển nhanh. Độ trễ nhận diện < 50ms/khuôn mặt.

### 3. [🌾 MobiAgri — Quản Lý Vùng Nguyên Liệu](https://github.com/VuongQuocHoa/mobiagri-app)
> **Nền tảng ERP nông nghiệp số hóa hộ canh tác và chuỗi cung ứng chuẩn VietGAP**
- **Full-Stack Stack:** React 18 + Vite, Node.js Express, Prisma ORM, SQLite.
- **Chức năng:** Số hóa hồ sơ nông hộ, quản lý nhật ký bón phân/phun thuốc BVTV, theo dõi chu kỳ mùa vụ, dự báo sản lượng và B2B Dashboard kết nối siêu thị, thương lái.

### 4. [🤖 Coze AI Agent & Streaming Gateway](https://github.com/VuongQuocHoa/coze-agent)
> **Trợ lý AI Coze API v3: Web Chat đa phiên, Reverse Proxy chống CORS (Node.js & Vercel) & Số hóa nhật ký canh tác VietGAP**
- **Kiến trúc đa tầng:** Web SPA (TailwindCSS, Marked, Highlight.js) + Zero-Dependency Node.js Server (`server.js`, Hot-Reload `.env`) + Vercel Serverless Function (`api/coze.js`) + Python CLI Client (`chat.py`).
- **Xử lý luồng thời gian thực:** Thuật toán khử trùng lặp (Deduplication) Server-Sent Events (SSE) giữa `delta` và `completed`, duy trì ngữ cảnh đa lượt hội thoại với `conversation_id`.
- **Nghiệp vụ VietGAP:** Kịch bản đàm thoại chuyên biệt tự động hướng dẫn nông dân ghi chép và trích xuất thực thể canh tác [Cây trồng, Lô thửa, Hoạt động, Liều lượng, Người thực hiện].

### 5. [⏱️ Chronos Pro Life OS](https://github.com/VuongQuocHoa/chronos-life-os)
> **Hệ điều hành quản trị 1.440 phút trong ngày — 100/100 Google Lighthouse**
- **Kiến trúc tinh gọn:** Pure Vanilla JavaScript ES6 Modules (Zero external dependencies), kích thước tải trang < 50KB.
- **Trực quan hóa:** Vòng tròn 24 giờ tính toán góc lượng giác SVG/Canvas, cảm biến trình duyệt và Native Rule Engine Chatbot không độ trễ.

### 6. [🎯 Shopee Deal Sniper & Scraper](https://github.com/VuongQuocHoa/shopee-deal-sniper)
> **Bot quét giá Flash Sale TMĐT đa luồng & bắn cảnh báo tức thời qua Telegram Webhook**
- Thuật toán chấm điểm deal hời `filterAndScoreItems`, cơ chế tránh chặn IP và circular buffer 100 deals bảo vệ bộ nhớ RAM. Thông báo đến điện thoại < 3 giây.

### 7. [💬 Facebook Fanpage AI Assistant](https://github.com/VuongQuocHoa/fb-ai-bot)
> **Trợ lý tư vấn bán hàng & tự động thu thập Lead tích hợp Google Gemini 1.5 Flash**
- Kết nối Messenger Graph API Webhook, phân tích nhu cầu và tự động chốt đơn / lấy số điện thoại khách hàng 24/7 kèm bảng điều khiển Live Transaction Logging.

### 8. [📰 Autonomous Market News AI Agent](https://github.com/VuongQuocHoa/ai-market-agent)
> **Agent tự động cào tin tài chính, tóm tắt thông minh qua LangChain & phát bản tin Telegram**
- Tự động quét RSS từ nhiều nguồn báo chí kinh tế, tinh gọn nội dung bằng mô hình ngôn ngữ lớn và lập lịch tự động bằng APScheduler.

---

## 📈 Thống Kê Hoạt Động GitHub (GitHub Metrics)

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=VuongQuocHoa&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="VuongQuocHoa's GitHub Stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VuongQuocHoa&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />

</div>

---

## 📬 Kết Nối Với Tôi (Get in Touch)

- **Họ và tên:** Vương Quốc Hòa
- **Vị trí:** Junior AI / Computer Vision / Full-Stack Engineer
- **Điện thoại / Zalo:** `0399911382`
- **Email:** `hoalkasd@gmail.com`
- **Địa chỉ:** TP. Thủ Đức, TP. Hồ Chí Minh
- **Hình thức làm việc:** Remote (Làm việc từ xa) / Sẵn sàng nhận việc ngay!
