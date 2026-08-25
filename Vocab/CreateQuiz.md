Tôi sẽ gửi LIST TỪ VỰNG IELTS Reading. Hãy chuyển đổi danh sách này thành chuỗi JSON chuẩn hóa để import trực tiếp vào thẻ Flashcard theo đúng cấu trúc bên dưới.

QUY TẮC ĐỊNH DẠNG (BẮT BUỘC):
1. ĐẦU RA: Chỉ xuất ra DUY NHẤT 1 block JSON hợp lệ (Valid JSON). TUYỆT ĐỐI KHÔNG thêm văn bản giải thích.
2. CÁC TRƯỜNG TRONG JSON KHỚP 100% VỚI FLASHCARD UI:
   - `term` (Thuật ngữ): Từ/cụm từ tiếng Anh gốc.
   - `definition` (Định nghĩa): BẮT BUỘC lồng nghĩa tiếng Việt trong ngoặc ở cuối: `<Định nghĩa tiếng Anh>. (<Nghĩa tiếng Việt trong ngoặc đơn>)`.
   - `pronounce` (Phát âm): Phiên âm IPA chuẩn.
   - `word_type` (Loại từ): Từ loại tiếng Anh (e.g. "verb phrase", "noun phrase", "phrasal verb", "phrase",...).
   - `example` (Ví dụ): 1 câu ví dụ tiếng Anh ngữ cảnh chuẩn IELTS.
   - `synonyms` (Từ đồng nghĩa): Mảng các chuỗi (Array of strings) chứa các từ/cụm từ đồng nghĩa BẰNG TIẾNG ANH (chỉ tối đa 2 từ synonyms) (e.g. `["basic food", "dietary staple"]`). KHÔNG DÙNG TIẾNG VIỆT Ở ĐÂY.

VÍ DỤ MẪU JSON CHUẨN FLASHCARD:
{
  "title": "DAY 01 – TEST 1",
  "words": [
    {
      "term": "staple food",
      "definition": "A food that is eaten routinely and constitutes a dominant portion of a standard diet (Thực phẩm chính).",
      "pronounce": "/ˈsteɪpl fuːd/",
      "word_type": "noun phrase",
      "example": "Rice is the primary staple food for more than half of the world's population.",
      "synonyms": ["basic food", "dietary staple"]
    },
    {
      "term": "stay healthier",
      "definition": "To maintain better physical condition and well-being (Giữ sức khỏe tốt hơn).",
      "pronounce": "/steɪ ˈhelθiər/",
      "word_type": "verb phrase",
      "example": "Eating a balanced diet helps you stay healthier throughout the year.",
      "synonyms": ["maintain health", "keep fit"]
    }
  ]
}

QUY TẮC :
- Passage mới = Tăng DAY +1 trong tiêu đề "title".
- Làm đúng và đủ các từ trong danh sách 
- Thuật ngữ phải theo đúng trong danh sách, không được thay đổi ( trước dấu 2 chấm).
- Ví dụ phải là câu tiếng Anh chuẩn, có ngữ cảnh rõ ràng với thuật ngữ, phù hợp với IELTS Reading.
---


