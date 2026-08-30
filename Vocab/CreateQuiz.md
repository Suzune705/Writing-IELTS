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




drill : khoan, máy khoan (to make a hole; or a tool used for drilling)

don't worry just yet : đừng lo lắng vội (no need to worry for now)

extra earwax : ráy tai thừa (too much wax built up in the ear)

be doomed : tiêu đời rồi, chắc chắn thất bại (bound to fail or be destroyed)

online trolling : sự quấy rối trực tuyến (deliberately provoking people online)

munching on the go : vừa đi vừa ăn vặt (eating snacks while on the move)

antioxidants : chất chống oxy hóa (substances that protect cells from damage)

pushback : sự phản đối, sự chống lại (resistance or opposition to a plan or idea)

geeky : mọt sách, cuồng công nghệ (nerdy or obsessed with tech/niche topics)

sedentary lifestyle : lối sống ít vận động (an inactive lifestyle with little physical exercise)

mood disorders : rối loạn tâm trạng (mental conditions that affect emotional state)

steeped in something : đắm chìm trong cái gì đó (deeply immersed in something)

sarcastic : mỉa mai, châm biếm (using irony to mock or convey contempt)
