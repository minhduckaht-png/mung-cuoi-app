# App Danh sách mừng cưới cho iPhone (bản trống, không kèm dữ liệu cá nhân)

## Tính năng
- Bắt đầu với danh sách trống; không chứa tên khách hoặc khoản mừng từ file Excel gốc.
- Tìm kiếm không dấu trong tên, ghi chú và tiền.
- Sắp xếp theo tên gọi A–Z, họ tên A–Z hoặc thứ tự nhập.
- Thêm, sửa, xóa từng người.
- Thống kê số người có tên, tổng tiền mặt và tổng vàng riêng biệt.
- Nhập CSV/JSON; xuất CSV và sao lưu JSON.
- Lưu dữ liệu trên trình duyệt của iPhone.

## Nhập dữ liệu Excel
App không đọc trực tiếp tệp `.xlsx`. Mở file Excel, chọn **Save As / Export** và xuất thành **CSV UTF-8**, sau đó dùng nút **Nhập CSV/JSON** trong app. Cấu trúc CSV gồm 3 cột: `Tên`, `Note`, `Tiền`.

Quy ước tiền: `tr` = triệu đồng; `k` = nghìn đồng; `p` = phân vàng; `chỉ` = chỉ vàng. Tổng tiền mặt và tổng vàng được thống kê riêng; 10 phân = 1 chỉ.

## Cài trên iPhone 11 Pro
1. Tạo một repository GitHub mới.
2. Tải toàn bộ các file trong thư mục này lên repository.
3. Vào **Settings → Pages**, chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, rồi Save.
4. Khi GitHub Pages cấp địa chỉ HTTPS, mở địa chỉ đó bằng Safari trên iPhone.
5. Chọn **Chia sẻ → Thêm vào Màn hình chính**.

## Lưu ý riêng tư và sao lưu
- Đây là bản mã nguồn trống, không có danh sách khách ban đầu. Tuy nhiên, nếu anh nhập dữ liệu vào app, dữ liệu được lưu trong bộ nhớ trình duyệt trên thiết bị đó.
- Không tải file Excel có thông tin khách lên repository GitHub.
- Dữ liệu không tự đồng bộ giữa các thiết bị. Dùng **Sao lưu JSON** định kỳ và giữ file sao lưu ở nơi riêng tư.
- GitHub Pages là website công khai; ai có đường dẫn cũng có thể mở trang app. Vì vậy chỉ đưa mã nguồn trống lên GitHub, không đưa danh sách khách hoặc bản sao lưu lên đó.
