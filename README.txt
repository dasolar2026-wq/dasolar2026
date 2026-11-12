BẢN HỢP ĐỒNG — CÔNG TY TNHH D.A SOLAR
Tạo ngày 4/11/2026

NỘI DUNG
- index.html              Ứng dụng (một file duy nhất)
- brand.json              Thông tin công ty, logo, màu — sửa/xuất từ tab "Cài đặt công ty"
- manifest.webmanifest, sw.js, icon-*.png   Để cài lên màn hình điện thoại và chạy khi mất sóng

CÁCH ĐƯA LÊN MẠNG (GitHub Pages)
1. Tạo kho (repository) mới trên GitHub, bật Pages (nhánh main, thư mục gốc).
2. Tải TẤT CẢ file trong zip lên kho (giữ nguyên tên, để cùng một thư mục).
3. Mở địa chỉ https://<tên-tài-khoản>.github.io/<tên-kho>/ bằng Chrome/Safari, bấm "Cài lên màn hình".

ĐỔI LOGO / THÔNG TIN VỀ SAU
- Mở app → tab "Cài đặt công ty" → sửa → "Lưu cài đặt" (chỉ áp dụng trên máy đó), hoặc
- bấm "Xuất brand.json" rồi thay file brand.json trong kho: mọi máy sẽ dùng chung.
- Nếu thay logo thì thay luôn icon-192.png / icon-512.png / icon-maskable-512.png (hoặc đóng gói lại bằng công cụ).

CẬP NHẬT PHIÊN BẢN APP
- Thay file index.html mới (đóng gói lại bằng công cụ để giữ thương hiệu) và đẩy lên kho.

DỮ LIỆU HỒ SƠ nằm trong trình duyệt của từng máy; dùng "Cài đặt → Sao lưu" trong app để sao lưu.
