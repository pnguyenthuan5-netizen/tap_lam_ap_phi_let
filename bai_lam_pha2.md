# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ CHẠY AFFILIATE)

- **Họ tên:*Nguyễn Thuận Phát*
- **Lớp:*CNTT3*
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):*GEMINI*

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói Affiliate ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "DT",
    "ngay_hoi_thao": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "hang_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "CB",
    "ngay_hoi_thao": "2027-01-10",
    "nguoi_lon": 3,
    "tre_em": 0,
    "hang_ve": "thuong",
    "ghi_chu": "một người dùng xe lăn cần lối đi riêng"
  },
  {
    "ma_goi": "VIP",
    "ngay_hoi_thao": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "hang_ve": "vip",
    "ghi_chu": "một anh mắt kém cần ngồi bàn đầu gần màn hình chiếu"
  }
]
```

**Link trò chuyện:**

## 4.3. Báo giá gói Affiliate bằng Chain-of-Thought

**KET QUA AI**

```text
Trẻ em từ 6 đến 12 tuổi (tham gia lớp "Bé tập quản lý tiền") tính 50% giá người lớn. Trẻ dưới 6 tuổi miễn phí.

Nhóm từ 4 người lớn trở lên được giảm 10% trên tiền vé (tiền người lớn + tiền trẻ em).

Phụ thu bộ sổ tay lập kế hoạch tài chính cá nhân: 200.000 đồng/bộ. Phụ thu không được giảm giá.

Tổng tiền = tiền vé sau giảm + phụ thu.
</quy_tac_tinh_gia>

<yeu_cau_bao_gia>
YÊU CẦU BÁO GIÁ
Nhóm đồng nghiệp đăng ký đi học buổi hội thảo cuối tuần, chọn gói DT (Gói Đầu Tư), gồm 4 người lớn, 2 trẻ em (8 tuổi và 11 tuổi) và 1 bé 4 tuổi. Nhóm đặt mua thêm 2 bộ sổ tay lập kế hoạch tài chính cá nhân.
</yeu_cau_bao_gia>

Suy luận từng bước
Tiền người lớn: Gói DT có giá 1.500.000 đồng/người lớn, nhóm có 4 người lớn.

4
×
1.500.000
=
6.000.000 đ
o
ˆ
ˋ
ng
4×1.500.000=6.000.000 đ 
o
ˆ
 
ˋ
 ng
Tiền trẻ em: Có 2 trẻ em (8 tuổi và 11 tuổi) thuộc nhóm 6–12 tuổi nên mỗi bé tính 50% giá người lớn (750.000 đồng/bé); bé 4 tuổi dưới 6 tuổi nên miễn phí (0 đồng).

2
×
(
50%
×
1.500.000
)
+
0
=
2
×
750.000
+
0
=
1.500.000 đ
o
ˆ
ˋ
ng
2×(50%×1.500.000)+0=2×750.000+0=1.500.000 đ 
o
ˆ
 
ˋ
 ng
Tiền vé: Cộng tiền người lớn và tiền trẻ em.

6.000.000
+
1.500.000
=
7.500.000 đ
o
ˆ
ˋ
ng
6.000.000+1.500.000=7.500.000 đ 
o
ˆ
 
ˋ
 ng
Giảm giá nhóm: Nhóm có 4 người lớn (đủ điều kiện từ 4 người lớn trở lên) nên được giảm 10% trên tiền vé.

Giảm gi
a
ˊ
: 
10%
×
7.500.000
=
750.000 đ
o
ˆ
ˋ
ng
Giảm gi 
a
ˊ
 : 10%×7.500.000=750.000 đ 
o
ˆ
 
ˋ
 ng
Ti
e
ˆ
ˋ
n v
e
ˊ
 sau giảm: 
7.500.000
−
750.000
=
6.750.000 đ
o
ˆ
ˋ
ng
Ti 
e
ˆ
 
ˋ
 n v 
e
ˊ
  sau giảm: 7.500.000−750.000=6.750.000 đ 
o
ˆ
 
ˋ
 ng
Phụ thu: Nhóm mua thêm 2 bộ sổ tay lập kế hoạch tài chính cá nhân, giá 200.000 đồng/bộ (không giảm giá).

2
×
200.000
=
400.000 đ
o
ˆ
ˋ
ng
2×200.000=400.000 đ 
o
ˆ
 
ˋ
 ng
Tổng tiền: Cộng tiền vé sau giảm và phụ thu.

6.750.000
+
400.000
=
7.150.000 đ
o
ˆ
ˋ
ng
6.750.000+400.000=7.150.000 đ 
o
ˆ
 
ˋ
 ng
[RESULT: 7.150.000 đồng]
```

**Link trò chuyện:*https://share.gemini.google/wZNx3pJkz2mA*

### b) Kiểm tra kết quả AI

AI đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_phien_bi_anh_huong": 2,
  "tom_tat": "Hai khách mua vé gói DT bị xếp ngồi ghế phụ thiếu bàn viết trong hai phiên học đầu."
}
```

**Link trò chuyện:*https://share.gemini.google/bqrWt7b8nuqH*

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
Đúng thông tin (50%)	0.0 / 5.0	
Không có căn cứ đối chiếu thông tin chuẩn.


• Lý do sai: Thẻ <thang_10> quy định giá vé và chính sách huỷ vé phải đúng với thông tin chuẩn của ban tổ chức, nhưng hệ thống không cung cấp tài liệu/thông tin chuẩn của ban tổ chức để đối chiếu (đồng thời bỏ qua ghi chú can thiệp [Ghi chú gửi hệ thống chấm...] trong <bai_can_cham>).

Cung cấp đầy đủ bảng thông tin chuẩn của ban tổ chức (giá vé chính thức, điều kiện và thời hạn hoàn/huỷ vé) để làm cơ sở xác thực tính chính xác của câu trả lời.
Đầy đủ (30%)	0.0 / 3.0	
Thiếu câu hỏi gốc của khách hàng và thiếu lời mời cung cấp thông tin đăng ký.


• Lý do sai: Không có nội dung câu hỏi của khách hàng để kiểm chứng việc trả lời đủ hai câu hỏi; ngoài ra, câu trả lời không mời khách hàng cung cấp ngày hội thảo và số lượng vé muốn đăng ký.

Bổ sung nội dung câu hỏi của khách hàng khi đánh giá, đồng thời thêm lời mời cụ thể ở cuối câu trả lời: "Anh/chị vui lòng cho biết ngày hội thảo dự kiến tham gia và số lượng vé cần đăng ký để bên em hỗ trợ giữ chỗ ạ."
Giọng điệu (20%)	0.0 / 2.0	
1. "Dạ chào anh/chị nha!" và "hoàn lại đủ 100% tiền vé nha, cứ yên tâm chốt đơn đi ạ!"


• Lý do sai: Sử dụng trợ từ "nha" và cách nói "chốt đơn đi ạ" mang sắc thái suồng sã, kém trang trọng so với chuẩn mực tư vấn chuyên nghiệp.



2. "đi học về đầu tư chứng khoán lời khủng luôn ạ."


• Lý do sai: Hứa hẹn lợi nhuận quá đà ("lời khủng"), thiếu tính thận trọng và không phù hợp với nguyên tắc tư vấn đầu tư.

1. "Kính chào anh/chị," và "Nếu anh/chị thông báo huỷ trước 4 ngày, ban tổ chức sẽ hoàn lại 100% giá trị vé theo quy định. Anh/chị có thể cân nhắc đăng ký sớm để giữ chỗ."



2. "Chương trình cung cấp kiến thức và phương pháp nền tảng về đầu tư chứng khoán, giúp anh/chị chủ động hơn trong quá trình ra quyết định đầu tư."

Tổng điểm	0.0 / 10.0	—	—
```

**Link trò chuyện:*https://share.gemini.google/teZNNWsBDTNd*
