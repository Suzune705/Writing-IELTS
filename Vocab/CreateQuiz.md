Tôi sẽ gửi LIST TỪ VỰNG IELTS. Hãy chuyển đổi danh sách này thành chuỗi JSON chuẩn hóa để import trực tiếp vào thẻ Flashcard theo đúng cấu trúc bên dưới.

QUY TẮC ĐỊNH DẠNG (BẮT BUỘC):
1. ĐẦU RA: Chỉ xuất ra DUY NHẤT 1 block JSON hợp lệ (Valid JSON). TUYỆT ĐỐI KHÔNG thêm văn bản giải thích ngoài JSON.
2. CÁC TRƯỜNG TRONG JSON KHỚP 100% VỚI FLASHCARD UI:
   - `term` (Thuật ngữ): Từ/cụm từ tiếng Anh gốc (giữ nguyên không đổi).
   - `definition` (Định nghĩa): Định nghĩa tiếng Anh ngắn gọn, dễ hiểu kèm nghĩa tiếng Việt theo note trong ngoặc: `<Định nghĩa tiếng Anh súc tích>. (<Nghĩa tiếng Việt theo note >)`.
   - `pronounce` (Phát âm): Phiên âm IPA chuẩn quốc tế.
   - `word_type` (Loại từ): Từ loại tiếng Anh (e.g. "verb phrase", "noun phrase", "phrasal verb", "phrase", "idiom",...).
   - `example` (Ví dụ): 1 câu ví dụ tiếng Anh tự nhiên, sinh động, chuẩn ngữ pháp, gắn với ngữ cảnh đời sống/học tập/công việc thực tế  , ko áp dúng quá nhiều từ vựng chuyên ngành , ví dụ đơn giản dễ  hiểu có liên quan đến thuật ngữ .
   - `synonyms` (Từ đồng nghĩa): Mảng các chuỗi (Array of strings) chứa 1-2 từ/cụm từ đồng nghĩa phổ biến BẰNG TIẾNG ANH (e.g. `["maintain health", "keep fit"]`). KHÔNG DÙNG TIẾNG VIỆT Ở ĐÂY.

VÍ DỤ MẪU JSON CHUẨN FLASHCARD:
{
  "title": "IELTS Vocabulary Flashcards",
  "words": [
    {
      "term": "staple food",
      "definition": "A food that makes up the main part of a person's regular diet (Lương thực chính, thực phẩm thiết yếu hàng ngày).",
      "pronounce": "/ˈsteɪpl fuːd/",
      "word_type": "noun phrase",
      "example": "Rice is the primary staple food for more than half of the world's population.",
      "synonyms": ["basic food", "dietary staple"]
    },
  ]
}

TIÊU CHÍ CHẤT LƯỢNG NỘI DUNG:
- **Tiêu đề**: Passage mới = Tăng DAY +1 trong "title" (e.g. "DAY 02 – TEST 1").
- **Đầy đủ**: Làm đúng và đủ tất cả các từ trong danh sách được cung cấp.
- **Thuật ngữ**: Giữ đúng từ/cụm từ gốc (phần trước dấu 2 chấm).
- **Văn phong**: Giải thích và ví dụ phải dễ hiểu, trực quan cho người học mọi độ tuổi, tránh dịch máy thô cứng.
---

topic: Climate

cyclone: lốc xoáy (a large-scale air mass that rotates around a strong center of low atmospheric pressure)
`
move across: di chuyển qua(to travel from one side to another)

likelihood of something: khả năng xảy ra của cái gì (the probability or chance of something happening)

mudslide: lũ bùn, sạt lở bùn đất (a mass of mud and earth that moves down a slope, often caused by heavy rain)

storm surge: nước dâng do bão (a rise in sea level caused by a storm, often leading to coastal flooding)

get swept somewhere: bị cuốn trôi/thổi bay đến đâu (to be carried away by a current or force, often water or wind)

casualty: người thương vong, sự thương vong (a person injured or killed in an accident or disaster)

come onto land: đổ bộ vào đất liền (to reach the shore or land from the sea)

drown: chết đuối (to die by being submerged in water)

flaw: khuyết điểm, thiếu sót (a defect or weakness in something)

toughen up: trở nên cứng cỏi, mạnh mẽ lên (to become stronger or more resilient in the face of challenges)

take something personally: để bụng, tự ái, phật ý (to feel offended or upset by something that was said or done)


