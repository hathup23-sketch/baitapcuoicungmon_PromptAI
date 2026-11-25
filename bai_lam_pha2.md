# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ CHẠY AFFILIATE)

- **Họ tên:**PHAM THI THU HA
- **Lớp:**CNTT3
- **Link repository Pha2:**https://github.com/hathup23-sketch/baitapcuoicungmon_PromptAI.git
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**Gemini

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói Affiliate ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "TT",
    "ngay_bat_dau": "2026-12-20",
    "creator_chinh": 2,
    "thuc_tap_sinh": 1,
    "hang_tai_khoan": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "SP",
    "ngay_bat_dau": "2027-01-08",
    "creator_chinh": 3,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": null,
    "ghi_chu": "cần ngồi bàn gần cửa ra vào"
  },
  {
    "ma_goi": "PRO",
    "ngay_bat_dau": null,
    "creator_chinh": 4,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": "vip",
    "ghi_chu": "cần mượn thêm đèn trợ sáng và phông xanh để quay mẫu"
  }
]
```

**Link trò chuyện:**https://share.gemini.google/vbz3wxQJij9o

## 4.3. Báo giá gói Affiliate bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền Creator chính: $4 \times 1.500.000 = 6.000.000\text{ đồng}$Tiền thực tập sinh: 2 thực tập sinh (16 tuổi và 17 tuổi, đều từ 15 đến dưới 18 tuổi nên tính 60% giá Creator chính; bé 7 tuổi dưới 15 tuổi ngồi khu chờ được miễn phí): $2 \times (1.500.000 \times 60\%) = 2 \times 900.000 = 1.800.000\text{ đồng}$Tổng tiền gói: $6.000.000 + 1.800.000 = 7.800.000\text{ đồng}$Giảm giá team: Team có 4 Creator chính (đủ điều kiện từ 4 Creator chính trở lên), giảm 10% trên tổng tiền gói: $7.800.000 \times 10\% = 780.000\text{ đồng}$ (tiền gói sau giảm là $7.800.000 - 780.000 = 7.020.000\text{ đồng}$)Phụ thu thuê mic: Thuê 2 bộ mic thu âm không dây, không áp dụng giảm giá: $2 \times 250.000 = 500.000\text{ đồng}$Tổng tiền: $7.020.000 + 500.000 = 7.520.000\text{ đồng}$[RESULT: 7.520.000 đồng]
```

**Link trò chuyện:**https://share.gemini.google/yndqo17glsL2

### b) Kiểm tra kết quả AI

AI đã trả lời đúng 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_phong",
  "so_khach": 3,
  "so_ca_bi_anh_huong": 2,
  "tom_tat": "Nhóm 3 khách hàng (Creator) phản ánh bị xếp sai sang phòng học thường thiếu đèn livestream và bị ồn trong 2 ca thực hành đầu tiên, không đúng với cam kết ban đầu."
}
```

**Link trò chuyện:**https://share.gemini.google/a0XDtNMOUHAu

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
6.5 / 10
```

**Link trò chuyện:**https://share.gemini.google/50BIuvwmMrCM
