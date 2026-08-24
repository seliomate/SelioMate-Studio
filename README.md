# SelioMate Studio — kho phát hành

Kênh phát hành chính thức của **Seliomate Studio** và các module mở rộng.

- **Releases**: bản cài Studio theo từng phiên bản, và các gói module `.smod` kèm chữ ký
  minisign (`.smod.sig`).
- **`registry.json`**: danh mục máy đọc — Studio đối chiếu `minAppVersion` để chọn bản
  tương thích, kiểm sha256 rồi kiểm chữ ký trước khi cài.

Mã nguồn nằm ở các repo riêng. Gói tải công khai; việc kích hoạt module theo giấy phép
diễn ra trong ứng dụng.
