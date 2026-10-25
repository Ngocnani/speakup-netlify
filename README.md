# SpeakUp – website demo

Website demo cho đồ án Thương mại điện tử (UFM). Trang tĩnh `index.html` + một Netlify Function `netlify/functions/chat.js` gọi Gemini API cho chatbot.

## Deploy lên Netlify
1. Đưa thư mục này lên một repo GitHub.
2. Netlify → Add new project → Import from Git → chọn repo (không cần build command).
3. Site configuration → Environment variables → thêm `GEMINI_API_KEY` = key lấy từ aistudio.google.com.
4. Deploys → Trigger deploy. Mở web, bấm "Tư vấn" và gõ một câu hỏi.

Nếu chưa có key hoặc AI lỗi, chatbot tự chuyển về chế độ trả lời theo kịch bản.
Không commit API key vào repo.
