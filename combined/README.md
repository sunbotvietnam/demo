# SUNBOT | Lớp học thông minh — Combined Expert Experience V4

**Bản thử nghiệm công khai theo đường dẫn riêng.** Bản này tích hợp mô phỏng 3D GitHub hiện có và tầng chuyên môn V3.

## Các lớp trải nghiệm

1. 3D lớp học, sa bàn 8×8, màn hình học liệu, robot và hai mẫu bản đồ theo ảnh thật. Giữ engine từ GitHub.
2. Bốn cảnh tự động ~66 giây với thuyết minh bằng bản thu của Sunbot.
3. Hồ sơ chuyên môn mở rộng, sáu tab: bài LV1-B6; chu trình tư duy; quan sát; hướng dẫn giáo viên; vai trò chuyển đổi số; nhận diện lớp học.
4. Đối chiếu ảnh thật và phối cảnh phòng mẫu; có phân biệt rõ hai loại hình ảnh.

## Nguồn đã đối chiếu

- **Sunbot Smart Classroom GitHub (main/gh-pages):** engine 3D, 8×8, audio, vật liệu.
- **SUNBOT Smart Learning Classroom Web V3 (tệp người dùng gửi):** cấu trúc sư phạm, quan sát, 3 góc nhìn stakeholder, tổ chức bài học.
- **2026 Sunbot Profile**, trang 26: 3 ảnh phối cảnh phòng STEAM Lab mẫu và phong cách phòng học (không khẳng định đã thi công).
- **LV01-ep06**: bài Khám phá khu vườn Sunbot, chậu hoa 6 bông, phân hóa nhóm tuổi, minh họa các bước.

## Giới hạn

- Không có KPI, số liệu trẻ, hồ sơ nhân sự hay nhật ký quản trị nội bộ.
- Các hoạt động trên sa bàn là mô phỏng; không phải một Digital Twin kết nối với thiết bị thật.
- Khung quan sát là tài liệu tham khảo, chưa được chuẩn hóa để chấm điểm năng lực trẻ.
- Bộ câu hỏi tự học không cấp chứng nhận giáo viên và không lưu dữ liệu lên máy chủ.
- Phụ đề cần đối chiếu nguyên văn với audio trước khi dùng làm video phát hành.

## Triển khai GitHub Pages

Đặt toàn bộ tệp trong một thư mục `/combined` trên nhánh `gh-pages`. Cần giữ thư mục `assets/` và `audio/` bên cạnh `index.html`. Không thay đổi bản `demo/index.html` hiện hành trong quá trình thẩm định.

## Kiểm thử

Phải nghiệm thu trên Chrome, Edge, Safari và điện thoại thực; kiểm tra tải Three.js từ CDN, WebGL, âm thanh sau tương tác, mở/đóng hồ sơ, nội dung giáo án, ảnh, mobile và tốc độ hiển thị.
