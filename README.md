# Thư mời 20/11 – Dị ứng – MDLS

Thư mời gặp mặt tri ân Thầy Cô nhân kỷ niệm 44 năm Ngày Nhà giáo Việt Nam.
Thời gian: 17:30, thứ Năm 19/11/2026. Địa điểm: Sun Palace, 1111 Giải Phóng, Hoàng Mai, Hà Nội.

## Cấu trúc

```
index.html      trang thư mời (HTML, CSS và JS trong một tệp)
img/            ảnh album 20/11/2023 và hai logo
```

## Đăng lên GitHub Pages

1. Tạo repository mới, tải toàn bộ nội dung thư mục này lên nhánh `main`, giữ nguyên thư mục `img/`.
2. Vào Settings → Pages → Build and deployment, chọn Source: Deploy from a branch, Branch: `main`, thư mục `/ (root)`, rồi bấm Save.
3. Sau khoảng 1–2 phút, trang có tại `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Chỉnh sửa nhanh (đầu thẻ `<script>` trong index.html)

- `GUESTS`: link riêng cho từng Thầy Cô. Ví dụ `"co-lan": "PGS.TS Nguyễn Thị Lan"`, rồi gửi link `.../#co-lan`.
- `BTC_ZALO`: số Zalo của Ban tổ chức, để nút "Mở Zalo Ban tổ chức" hiện ra sau khi Thầy Cô xác nhận.
- `EVENT_START`: giờ bắt đầu, dùng cho đồng hồ đếm ngược.
