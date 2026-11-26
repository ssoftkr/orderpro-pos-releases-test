# OrderPro POS releases

Repo này chỉ chứa **file cài đặt** của app OrderPro POS (Windows), không chứa code.

Bản test (ví dụ ký bằng chứng chỉ tự ký): Test server và máy test. Không dùng cho cửa hàng thật.

- Mỗi phiên bản là một Release, tag đúng bằng số phiên bản (ví dụ `1.0.1`, không có `v`): `latest.yml`, file cài đặt `.exe` và `.blockmap`.
- Phát hành bằng `npm run release` trong `clients/pos_app_electronjs` của repo `ssoftkr/orderpro`.
- **Không xóa** Release cũ (rollback cần file bản cũ). **Không sửa hay thay file** trong Release đã đăng: cần sửa thì tăng phiên bản.