1. Căn giữa chữ so với khung:
- Tìm flex container thêm thuộc tính "display: flex"
- Vào flex item thêm thuộc tính "margin: auto"
2. Thay đổi thứ tự hiển thị của flex item bằng thuộc tính "order"
3. CSS BEM

# BEM 
là tiêu chuẩn đặt tên class khi viết CSS

# Ý nghĩa
- Viết tắt của Block Element Modifier
- Block: khối
- Element: thành phần trong khối
- Modifier: Bổ sung ý nghĩa cho Block hoặc Element

## Tại sao phải dùng BEM?
- Mỗi người đặt 1 kiểu
- Members đặt class trùng nhau, CSS đè lên nhau

## Cú pháp
- .block
- .block__element

- .block--modifier
- .block__element--modifier

## Tính ứng dụng
- Xây dựng layout website
- Xây dựng thành phần trên website

## Ưu điểm
- Tính rõ ràng
- Tái sử dụng dễ dàng
- Giúp cả team làm việc với nhau dễ dàng
- Tính module, không lo CSS của class này ảnh hưởng lên CSS của class khác

## Khi nào cần dùng BEM là PHÙ HỢP
- Dự án nhiều members
- Dự án lớn, nhiều pages hoặc số lượng thành phần trên website nhiều