# platform Viet Nam map.

## Sinh viên thực hiện
| Họ và tên | Mã Sinh Viên| 
|--------------|-------|
| Trương Thị Huyền Trâm | 21020413| 
| Đỗ Minh Sáng | 21020717|
| Nguyễn Thịnh Thuận | 21020410|
| Hoàng Thanh Tùng | 21021661|
| Đặng Văn Khởi | 21020770|
## Giới thiệu
Bản đồ cung cấp vị trí địa lý chi tiết trên lãnh thổ Việt Nam.
Lấy dữ liệu từ Open street map, tuy nhiên năm 2019, open street map đã xóa bỏ vị trí 2 quần đảo Việt Nam do tranh chấp chính trị.
## Mô tả chức năng
### Chức năng tìm kiếm
- Người dùng có thể tìm kiếm vị trí mình mong muốn trên bản đồ, bằng cách nhập vị trí vào ô tìm kiếm.

### Chức năng lọc
- Bao gồm lọc 1 số vị trí (do data hạn chế) của bệnh viện, cây atm, nhà hàng và cửa hàng trên lãnh thổ Việt Nam

### Chức năng tìm đường đi
- Người dùng nhập vị trí bắt đầu và vị trí kết thúc, hệ thống sẽ cung cấp tuyến đường cụ thể.
- Thời gian đường đi tính bằng xe ô tô.
- Chỉ có 1 tuyến đường được hiển thị.

## Các công nghệ sử dụng
- LeafJS
- jQuery
- GeoJSON
- OSRM 
- OpenStreetMap (OSM)
## Hướng dẫn sử dụng
- clone github
- chạy trên vscode
- cài đặt live server extension trên vscode
- kích chuột trái vào file index.html, chọn open with live server
