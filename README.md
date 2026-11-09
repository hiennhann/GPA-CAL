# 🎓 Công Cụ Tính & Hoạch Định GPA (GPA Calculator)

🌍 **Live Demo:** [https://hiennhann.github.io/GPA-CAL/](https://hiennhann.github.io/GPA-CAL/)

## 💡 Ý Tưởng Dự Án
Việc theo dõi bảng điểm và tính toán GPA thủ công thường mất nhiều thời gian, đặc biệt là khi sinh viên có các môn học lại, học cải thiện hoặc những môn không tính vào trung bình chung (như Thể chất, Giáo dục Quốc phòng).

**GPA Calculator** là một công cụ tiện ích nhỏ gọn chạy hoàn toàn trên trình duyệt, được tạo ra để tự động hóa quá trình này. Thay vì phải nhập tay từng con điểm, người dùng chỉ cần tải lên file Excel bảng điểm. Hệ thống sẽ tự động bóc tách dữ liệu, chuẩn hóa tên môn, lọc bỏ các môn không cần thiết và tính toán GPA hiện tại. Đồng thời, công cụ cung cấp tính năng mô phỏng để sinh viên dễ dàng hoạch định số tín chỉ và mức điểm cần đạt cho các học kỳ tới nhằm chạm mốc GPA mục tiêu.

## 🚀 Chức Năng Hiện Tại
*   **Đọc dữ liệu Excel:** Xử lý trực tiếp file `.xlsx` hoặc `.xls` ngay trên trình duyệt.
*   **Lọc & Gộp môn học:** Tự động nhận diện các môn học lại, học cải thiện (chỉ lấy điểm cao nhất) và loại trừ các môn không tính điểm (Thể dục, GDQP,...).
*   **Bảng điều khiển trực quan:** Phân chia rõ ràng danh sách môn đã hoàn thành và môn đang học/chưa có điểm.
*   **Mô phỏng điểm số:** Cho phép người dùng thử thay đổi điểm các môn chưa hoàn thành (hoặc môn cần cải thiện) để xem GPA tổng thay đổi như thế nào theo thời gian thực.
*   **Tính toán mục tiêu:** Đưa ra con số cụ thể về số tín chỉ điểm A, B cần đạt để hoàn thành mục tiêu GPA mong muốn.

## 🛠️ Công Nghệ Sử Dụng
Dự án được phát triển theo hướng thuần Client-side, ưu tiên sự tối giản, tốc độ phản hồi nhanh và bảo mật thông tin người dùng (dữ liệu không gửi lên bất kỳ máy chủ nào).

*   **Giao diện (UI):** HTML5, CSS3 (sử dụng Flexbox và thiết kế đáp ứng cơ bản).
*   **Xử lý logic:** Vanilla JavaScript (ES6+).
*   **Thư viện bên thứ ba:** [SheetJS](https://sheetjs.com/) - Hỗ trợ phân tích và trích xuất dữ liệu từ file Excel.
*   **Triển khai (Deployment):** GitHub Pages.

---
*Phát triển bởi Nguyễn Văn Hiền Nhân.*
