Tôi sẽ gửi LIST TỪ VỰNG IELTS. Hãy chuyển đổi danh sách này thành chuỗi JSON chuẩn hóa để import trực tiếp vào thẻ Flashcard theo đúng cấu trúc bên dưới.

QUY TẮC ĐỊNH DẠNG (BẮT BUỘC):
1. ĐẦU RA: Chỉ xuất ra DUY NHẤT 1 block JSON hợp lệ (Valid JSON). TUYỆT ĐỐI KHÔNG thêm văn bản giải thích ngoài JSON.
2. CÁC TRƯỜNG TRONG JSON KHỚP 100% VỚI FLASHCARD UI:
   - `term` (Thuật ngữ): Từ/cụm từ tiếng Anh gốc (giữ nguyên không đổi).
   - `definition` (Định nghĩa): Định nghĩa tiếng Anh ngắn gọn, dễ hiểu kèm nghĩa tiếng Việt tự nhiên trong ngoặc: `<Định nghĩa tiếng Anh súc tích>. (<Nghĩa tiếng Việt tự nhiên, thoát ý>)`.
   - `pronounce` (Phát âm): Phiên âm IPA chuẩn quốc tế.
   - `word_type` (Loại từ): Từ loại tiếng Anh (e.g. "verb phrase", "noun phrase", "phrasal verb", "phrase", "idiom",...).
   - `example` (Ví dụ): 1 câu ví dụ tiếng Anh tự nhiên, sinh động, chuẩn ngữ pháp, gắn với ngữ cảnh đời sống/học tập/công việc thực tế  , ko áp dúng quá nhiều từ vựng chuyên ngành , ví dụ đơn giản dễ  hiểu có liên quan đến thuật ngữ .
   - `synonyms` (Từ đồng nghĩa): Mảng các chuỗi (Array of strings) chứa 1-2 từ/cụm từ đồng nghĩa phổ biến BẰNG TIẾNG ANH (e.g. `["maintain health", "keep fit"]`). KHÔNG DÙNG TIẾNG VIỆT Ở ĐÂY.

VÍ DỤ MẪU JSON CHUẨN FLASHCARD:
{
  "title": "DAY 01 – TEST 1",
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

dementia: chứng sa sút trí tuệ (a group of symptoms affecting memory, thinking, and social abilities severely enough to interfere with daily life)

turn to: tìm đến (to seek help, support, or advice from someone or something in times of need)

crave: khao khát (to have a strong desire for something)

keep to oneself: sống khép kín (to avoid sharing personal thoughts or feelings with others; to be reserved or private)

bring someone together: gắn kết mọi người (to unite or connect people, fostering a sense of community or togetherness)

the spark for something: nguồn cảm hứng cho cái gì đó (the initial inspiration or motivation that leads to the development of an idea, project, or action)

disposable income: thu nhập khả dụng (the amount of money left after taxes have been deducted, available for spending or saving)

raven: con quạ (a large, black bird known for its intelligence and adaptability)

trustfulness: sự tin cậy (the quality of being loyal and faithful to someone or something)

steadfastness: sự kiên định (the quality of being firm and unwavering in one's beliefs or actions)

fit the bill: phù hợp (to be suitable or appropriate for a particular purpose or situation)

see right across something: nhìn bao quát toàn bộ (to be able to see clearly all the way across an area; to have an unobstructed view)

exclusive access to something: quyền sử dụng độc quyền (the ability to enter or use a place, service, or resource that is not available to the general public)