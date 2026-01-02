# AI FloodGuard: Hệ thống cảnh báo ngập lụt đô thị thông minh
Dự án môn học Xây dựng Trí tuệ Nhân tạo (Building AI course project)

## Summary
AI FloodGuard là một hệ thống sử dụng học máy để dự đoán các điểm ngập lụt trong thành phố dựa trên dữ liệu lượng mưa, triều cường và hạ tầng thoát nước theo thời gian thực. Hệ thống giúp người dân tìm lộ trình an toàn và hỗ trợ chính quyền điều tiết giao thông hiệu quả hơn.

## Background
Vấn đề: Ngập lụt đô thị do biến đổi khí hậu và bê tông hóa đang trở thành vấn đề nghiêm trọng tại các thành phố lớn (như TP.HCM, Hà Nội).

Tần suất: Xảy ra thường xuyên mỗi khi có mưa lớn hoặc triều cường, gây thiệt hại về tài sản và ách tắc giao thông.

Động lực: Tôi muốn giúp cộng đồng giảm thiểu rủi ro khi di chuyển trong mùa mưa và giúp các cơ quan chức năng có cái nhìn trực quan hơn về tình hình ngập lụt.

Tầm quan trọng: Việc dự đoán chính xác giúp tiết kiệm hàng triệu USD chi phí hư hỏng phương tiện và thời gian của người dân.

How is it used?
Giải pháp này được sử dụng dưới dạng một ứng dụng di động cho người dân và một bảng điều khiển (dashboard) cho cơ quan quản lý.

Người dân: Nhận thông báo đẩy khi cung đường sắp đi có nguy cơ ngập cao.

Chính quyền: Theo dõi bản đồ nhiệt về các điểm ngập để cử đội ứng cứu hoặc điều hướng giao thông.

Đây là ví dụ minh họa về bản đồ dự báo.

Data sources and AI methods
Nguồn dữ liệu:

Dữ liệu lịch sử khí tượng (lượng mưa, độ ẩm) từ các trạm quan trắc.

Dữ liệu cảm biến mực nước tại các cống thoát nước.

Dữ liệu từ người dùng báo cáo trực tiếp qua ứng dụng (Crowdsourcing).

## Kỹ thuật AI:

Sử dụng Linear Regression (Hồi quy tuyến tính) để dự đoán mực nước dựa trên lượng mưa.

Sử dụng Random Forest hoặc Neural Networks để phân loại mức độ nguy hiểm của các đoạn đường.

##Challenges
Hạn chế: Hệ thống phụ thuộc lớn vào mật độ cảm biến mực nước trong thành phố. Nếu cảm biến hỏng, độ chính xác sẽ giảm.

Đạo đức: Cần đảm bảo tính bảo mật vị trí của người dùng khi họ báo cáo điểm ngập.

Sai số: AI có thể dự đoán sai nếu hệ thống thoát nước vừa được cải tạo mà dữ liệu chưa cập nhật kịp.

## What next?
Tích hợp trực tiếp vào các ứng dụng bản đồ phổ biến như Google Maps hoặc Apple Maps.

Cần sự hợp tác từ Sở Giao thông Vận tải để truy cập dữ liệu camera giao thông nhằm phân tích hình ảnh ngập lụt tự động bằng Computer Vision.

### Acknowledgments
Cảm ơn khóa học Elements of AI / Building AI của Đại học Helsinki và Reaktor.

Truyền cảm hứng từ các dự án dữ liệu mở về đô thị thông minh.
Đặc biệt tôi muốn cẳm ơn đến khóa học và đội ngũ vận hành khóa học.
