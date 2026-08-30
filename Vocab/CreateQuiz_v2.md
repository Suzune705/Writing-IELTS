Tôi sẽ gửi LIST TỪ VỰNG IELTS Reading. Hãy chuyển đổi danh sách này thành chuỗi JSON chuẩn hóa để import trực tiếp vào thẻ Flashcard theo đúng cấu trúc bên dưới.

QUY TẮC ĐỊNH DẠNG (BẮT BUỘC):
1. ĐẦU RA: Chỉ xuất ra DUY NHẤT 1 block JSON hợp lệ (Valid JSON). TUYỆT ĐỐI KHÔNG thêm văn bản giải thích.
2. CÁC TRƯỜNG TRONG JSON KHỚP 100% VỚI FLASHCARD UI (ĐÃ ĐẢO VỊ TRÍ TERM & EXAMPLE):
   - `term` (Mặt thuật ngữ / Mặt trước thẻ): 1 câu ví dụ tiếng Anh tự nhiên, ĐỘ DÀI VỪA PHẢI (khoảng 10 - 18 từ, súc tích, tránh quá dài/rườm rà). BẮT BUỘC làm nổi bật cụm từ vựng/cấu trúc bằng cách đặt trong cặp dấu ngoặc vuông đậm `【...】` (e.g. `【staple food】`, `【made up her mind】`).
   - `definition` (Định nghĩa): BẮT BUỘC lồng nghĩa tiếng Việt trong ngoặc ở cuối: `<Định nghĩa tiếng Anh>. (<Nghĩa tiếng Việt trong ngoặc đơn>)`.
   - `pronounce` (Phát âm): Phiên âm IPA chuẩn của từ vựng gốc (nếu là cụm có placeholder như `sth`, `sb` thì phiên âm ở dạng tổng quát chuẩn hoặc dạng từ khóa).
   - `word_type` (Loại từ): Từ loại tiếng Anh của từ vựng gốc (e.g. "verb phrase", "noun phrase", "phrasal verb", "idiom", "collocation",...).
   - `example` (Mặt ví dụ / Mặt từ vựng gốc): Dạng nguyên mẫu của từ/cụm từ/cấu trúc gốc lấy chính xác từ danh sách (viết bình thường không có ngoặc `【】`, e.g. `shortly have something`, `stay healthier`).
   - `synonyms` (Từ đồng nghĩa): Mảng các chuỗi (Array of strings) chứa các từ/cụm từ đồng nghĩa BẰNG TIẾNG ANH (chỉ tối đa 2 từ synonyms) (e.g. `["basic food", "dietary staple"]`). KHÔNG DÙNG TIẾNG VIỆT Ở ĐÂY.

3. QUY TẮC ĐẶT CÂU VÍ DỤ:
   - ĐỘ DÀI VỪA PHẢI & GỌN GÀNG: Câu ngắn gọn, súc tích (khoảng 10 - 18 từ), đủ ngữ cảnh rõ nghĩa, KHÔNG viết câu quá dài hay ghép nhiều mệnh đề phức tạp làm tràn màn hình flashcard.
   - XỬ LÝ PHRASAL VERB, IDIOM, COLLOCATION & CẤU TRÚC:
     * TUYỆT ĐỐI KHÔNG bê nguyên xi các placeholder (`something`, `somebody`, `sth`, `sb`, `one's`, `do sth`,...) vào câu ví dụ.
     * BẮT BUỘC thay thế placeholder bằng danh từ/tân ngữ cụ thể, tự nhiên và chia thì động từ phù hợp:
       - SAI: `We expect to 【shortly have something】 to announce regarding the company's expansion plans.`
       - ĐÚNG: `The company expects to 【shortly have an update】 on the project.`
       - SAI: `She needs to 【make up one's mind】 soon.`
       - ĐÚNG: `She finally 【made up her mind】 to study abroad.`
   - Cặp ngoặc `【...】` bao bọc trọn vẹn cụm/cấu trúc đã được chia hoặc thay thế linh hoạt trong câu.

VÍ DỤ MẪU JSON CHUẨN FLASHCARD:
{
  "title": "DAY 01 – TEST 1",
  "words": [
    {
      "term": "Rice is the primary 【staple food】 for most Asian countries.",
      "definition": "A food that is eaten routinely and constitutes a dominant portion of a standard diet (Thực phẩm chính).",
      "pronounce": "/ˈsteɪpl fuːd/",
      "word_type": "noun phrase",
      "example": "staple food",
      "synonyms": ["basic food", "dietary staple"]
    },
    {
      "term": "The company expects to 【shortly have an update】 on the project.",
      "definition": "To receive or possess information/results in a short time (Sớm có được điều gì đó).",
      "pronounce": "/ˈʃɔːrtli hæv ˈsʌmθɪŋ/",
      "word_type": "verb phrase",
      "example": "shortly have something",
      "synonyms": ["soon receive", "obtain soon"]
    },
    {
      "term": "She finally 【made up her mind】 to accept the new job offer.",
      "definition": "To make a final decision about something (Đưa ra quyết định).",
      "pronounce": "/meɪk ʌp wʌnz maɪnd/",
      "word_type": "idiom",
      "example": "make up one's mind",
      "synonyms": ["decide", "reach a decision"]
    }
  ]
}

QUY TẮC :
- Passage mới = Tăng DAY +1 trong tiêu đề "title".
- Làm đúng và đủ các từ trong danh sách.
- `term` phải là câu ví dụ ngắn gọn, súc tích (10 - 18 từ), ngữ cảnh rõ nghĩa, tự nhiên và bao bọc từ vựng trong `【...】`.
- `example` là cấu trúc/từ vựng gốc chính xác từ danh sách.
---


landline : điện thoại cố định (a telephone that is connected to a network by wires and is not mobile)
