ls1

- khi bắt đầu dự án chọn kiến trúc là bước quan trọng vì :
  - Nó sẽ định hình cách hệ thống hoạt động
  - Rất khó để điều chỉnh khi có nhu cầu khác
- Các loại kiến trúc phần mềm :
  - Kiến trúc nguyên khối (Monolithic Architecture)
  - Client - Server Architecture
  - Microservices Architecture

ls2:

| Loại kiến trúc | Microservices                                  | Monolith                                                                               |
| -------------- | ---------------------------------------------- | -------------------------------------------------------------------------------------- |
| Ưu điểm        | dễ nâng cấp bảo trì                            | dễ làm và dễ quản lý                                                                   |
| Nhược điểm     | khó quản lý vì phân tán <br> cần làm nhiều hơn | khó nâng cấp ,bảo trì <br> khó khăn với những người mới vào dự án vì số lượng code lớn |

ls3:

- Ưu Điểm của DDD :
  - làm mọi thứ rõ ràng minh bạch
  - dễ quản lý hơn
  - dễ dàng cho người mới khi vào dự án
- Nhược điểm :
  - cần phải thảo luận kỹ hơn để thống nhất

ls4:

- Order Management : quản lý các đơn hàng
- Payment : quản lý thanh toán
- Shipping : quản lý vận chuyển
- inventory : quản lý lưu kho
- Auth : quản lý xác thực
- search : quản lý tìm kiếm

ls5:

- Core Domain :
  - search
  - payment
  - order
  - Auth
  - inventory
- Supporting Domain:
  - shipping
- Generic Domain:
  - event

ls6:

- nhận định theo cách Sub-domain vì nó sẽ liên tục cải tiến theo phần mềm còn nếu theo Business Capability thì sẽ khó thêm những dịch vụ mới liên tục được
