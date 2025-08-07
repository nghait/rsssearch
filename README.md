CÁCH DÙNG:

# 1. Tìm kiếm với chuỗi từ khóa bất kỳ, mặc định là 3 ngày
python rs.py --keywords "sốt xuất huyết, bạch hầu" --days 5
python rs.py --keywords "Hà Nội, thanh niên, tử vong"
python rs.py --keywords "a, b, c ,f" --days 3
python rs.py --keywords "Bại liệt, cúm gia cầm, dịch hạch, đậu mùa, bệnh tả, tay chân miệng, sốt phát ban, sởi, sốt xuất huyết, bạch hầu, ho gà, viêm não nhật bản, viêm não vi rút, thủy đậu, cúm A, cúm B, cúm mùa, não mô cầu, bệnh lạ, viêm phổi nặng, bệnh mới nổi, chưa rõ tác nhân gây bệnh, bùng phát ca bệnh, gia tăng số ca bệnh, gia tăng số lượng người nhập viện, hàng loạt ca bệnh, ổ dịch, vụ dịch, phản ứng nặng sau tiêm vắc xin, tử vong do bệnh truyền nhiễm, tử vong không rõ nguyên nhân, tử vong sau tiêm vắc xin, động vật ốm chết hàng loạt, gia cầm ốm chết, unknown disease, emerging disease, re-emerging disease, reemerging disease, avian influenza, H5N1, Bird Flu, Ebola, MERS, public health emergency, pandemic threat" --days 5

python "C:\yourfoldername\rs.py" --keywords "Trump, hòa bình, Zelensky" --days 5

# 2. Tìm kiếm theo từ khóa định nghĩa trước
python rss_keyword_search.py --keywords sebs --days 3
python "C:\yourfoldername\rs.py" --keywords "ytsk" --days 5
python "C:\yourfoldername\rs.py" --keywords "gddt" --days 5
python rs.py --keywords "aicn, Elon Musk, y tế" --days 2
python rs.py --keywords "sebs, Trump, weather" --days 3
python rs.py --keywords "sebs, aicn" --days 3

# 3. Ghi kết quả ra tệp TXT
python rss_keyword_search.py --keywords "Hà Nội, thanh niên, thời tiết" --days 3 > ketqua02082025.txt

# 4. Đọc tệp kết quả TXT với lệnh start hoặc notepad:
C:\yourfoldername>start ketqua02082025.txt
hoặc
C:\yourfoldername>notepad ketqua02082025.txt

# 5. Mở liên kết trong cmd standard output bằng tổ hợp CTRL + SHIFT + Cursor Click


Quick start

python rs.py --keywords "sebs" --days 5
python rs.py --keywords "thời tiết, bão, thấp, dự báo thời tiết, nắng nóng, Trung Quốc, Campuchia, Lào" --days 7
python rs.py --keywords "aicn" --days 30


Xử lý kết quả bằng AI:

Dựa vào tài liệu kèm theo, bạn hãy chọn ra 3 tin nổi bật nhất về tình hình dịch bệnh trong nước.  Với mối tin, bạn trình bày theo cấu trúc (chú ý: lấy tiêu đề chính xác của tin, lấy liên kết có trong tài liệu của tin đó và không sáng tạo thêm):
Tin thứ 1, 2, hoặc 3.
Tiêu đề:
Ngày đăng:
Liên kết:
Tóm tắt:

