# HỆ THỐNG ĐỀ KIỂM TRA TRẮC NGHIỆM TRỰC TUYẾN QMATH-EXAM
> **Giáo viên**: ThS. Nguyễn Văn Sang - Khoa Cơ bản - Trường Cao đẳng Nghề số 1 - BQP.  
> **Nền tảng xuất bản**: GitHub Pages: [https://sanginnova9-jpg.github.io/QMath-Exam/](https://sanginnova9-jpg.github.io/QMath-Exam/)  
> **Cơ sở dữ liệu đám mây (Cloud Database)**: Google Cloud Firestore (`qmath-online`).

---

## 🚀 ĐỀ KIỂM TRA ĐANG HOẠT ĐỘNG (ACTIVE EXAM)

### 📌 Đề Tổng Ôn Chương I: Ứng Dụng Đạo Hàm Để Khảo Sát Và Vẽ Đồ Thị Hàm Số — Toán 12
- **Nguồn tài liệu**: Tuyển tập 30 đề tổng ôn chương Hàm số 12 (Ngô Đức Tài) — **Đề số 3 (Phần I)**.
- **Cấu trúc**: 12 câu trắc nghiệm nhiều phương án lựa chọn (Chuẩn GDPT 2018).
- **Thời gian làm bài**: 25 phút.
- **Link làm bài trực tuyến**: [https://sanginnova9-jpg.github.io/QMath-Exam/](https://sanginnova9-jpg.github.io/QMath-Exam/)

---

## 🌟 CÁC TÍNH NĂNG MỚI ĐƯỢC NÂNG CẤP (CLOUD DATABASE & DASHBOARD)
1. ☁️ **Lưu trữ CSDL Cloud Firebase thời gian thực**:
   - Tự động đồng bộ toàn bộ kết quả bài thi của học sinh vào Firestore collection `exam_submissions` ngay khi bấm nộp bài.
   - Bản ghi bao gồm: Họ tên, Lớp, Mã đề thi, Điểm số, Số câu đúng/sai, Thời gian làm bài, Số lần vi phạm rời tab, Lần thi và Dấu thời gian (Timestamp).
   - Cơ chế tự động sao lưu dự phòng Offline trên LocalStorage khi mất mạng.
2. 👨‍🏫 **Bảng điều khiển Báo cáo & Tra cứu điểm số dành cho Giáo viên (Teacher Dashboard)**:
   - Tra cứu danh sách toàn bộ học sinh đã làm bài với thống kê tổng hợp: Tổng số bài nộp, Điểm trung bình cả lớp, Điểm cao nhất, Tỉ lệ đạt ($\ge 5.0$).
   - Thanh tìm kiếm và lọc tức thì theo tên học sinh, lớp hoặc mã đề.
   - Nút **📥 Xuất Excel (CSV UTF-8)**: Tải bảng điểm về máy tính chỉ bằng 1 chạm, chuẩn font tiếng Việt cho Microsoft Excel.
3. 🎲 **Thuật toán đảo đề 3-Pass Fisher-Yates**: Đảo ngẫu nhiên 100% câu hỏi và 4 phương án A-B-C-D, tự động sinh mã đề mới và đồng bộ lời giải chi tiết.
4. 🛡️ **Giám sát chống gian lận (Anti-Cheat)**: 1 chu trình rời tab/màn hình tính đúng 1 lần vi phạm, cảnh báo âm thanh Beep, khóa chuột phải và phím tắt DevTools.
