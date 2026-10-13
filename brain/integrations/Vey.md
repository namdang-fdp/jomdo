---
type: integration-hypothesis
status: future
updated: 2026-10-13
---
# Khả năng tích hợp Jomdo với Vey

> Đây là **ý tưởng dài hạn**, chưa thuộc phạm vi MVP.

Vey là sản phẩm độc lập với định hướng **lớp trí tuệ cuộc họp và ngữ cảnh công việc**. Tài liệu nguồn: https://github.com/namdang-fdp/vey/blob/main/vey-brain/product/tam-nhin.md

## Ranh giới sản phẩm
- **Jomdo:** khám phá dự án, đăng cơ hội, kết nối người tham gia, làm rõ quyền lợi và giới thiệu thành quả được phép công bố.
- **Vey:** vòng đời cuộc họp, quyết định, tính liên tục của bối cảnh và đối chiếu trạng thái làm việc giữa các công cụ.
- Không ép người dùng Jomdo phải sử dụng Vey; không biến Jomdo thành công cụ quản lý dự án toàn diện.

## Hành trình tích hợp có thể thử sau này
1. Nhóm tìm thấy nhau trên Jomdo và xác nhận bắt đầu hợp tác.
2. Nếu cần, nhóm **tự lựa chọn** kết nối Vey để hỗ trợ các cuộc họp và quá trình ra quyết định.
3. Chỉ các cột mốc hoặc thành quả được nhóm cho phép mới có thể xuất hiện trên hồ sơ Jomdo.

## Quyền riêng tư và kỹ thuật
- Không tự công khai transcript, quyết định nội bộ, thông tin khách hàng hoặc dữ liệu thành viên của Vey.
- Không chia sẻ database trực tiếp. Nếu tích hợp, ưu tiên API, phân quyền và sự đồng ý rõ ràng.
- Chưa quyết định endpoint, định danh xuyên hệ thống, cách tính phí hoặc thiết kế luồng tích hợp.
- **Không đưa tích hợp Vey vào MVP Jomdo.**
