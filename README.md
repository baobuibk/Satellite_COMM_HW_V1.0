# Dự án COMM_BOARD - Satellite_COMM_HW_V1.0

## Giới thiệu
Dự án `COMM_BOARD` là một phần của hệ thống phần cứng giao tiếp vệ tinh (`Satellite_COMM_HW_V1.0`), được thiết kế trên **Altium Designer**. Bo mạch này hỗ trợ giao tiếp dữ liệu cho ứng dụng vệ tinh, bao gồm truyền nhận tín hiệu RF và giao tiếp với các thiết bị ngoại vi, sử dụng vi điều khiển STM32H745.

## Cấu trúc thư mục
```
├── 01_DESIGN/                # Tệp thiết kế chính
├── 02_Schematic_pdf/         # Sơ đồ mạch dưới dạng PDF
├── 03_BOM/                   # Danh sách linh kiện (Bill of Materials)
├── 04_GERBER/                # Tệp Gerber cho sản xuất
├── 05_SMT/                   # Hướng dẫn lắp ráp SMT
├── 06_CAD/                   # Tệp CAD bổ sung
├── 07_REF/                   # Tài liệu tham khảo
├── 08_3D/                    # Mô hình 3D
└── README.md                 # File này
```

## Yêu cầu
- **Phần mềm**: Altium Designer phiên bản 21.0 hoặc mới hơn.
- **Phần cứng**: 
  - Vi điều khiển STM32H745.
  - Các linh kiện khác theo BOM trong `03_BOM/`.
- **Công cụ khác**: Phần mềm lập trình firmware (STM32CubeIDE).

## Hướng dẫn cài đặt
1. **Tải dự án**:
   - Clone repository về máy:
     ```
     git clone https://github.com/baobuibk/Satellite_COMM_HW_V1.0.git
     ```
2. **Mở dự án trong Altium**:
   - Mở Altium Designer.
   - Chọn `File > Open Project` và điều hướng đến thư mục `1_COMM_BOARD`.
   - Mở tệp `.PrjPcb` trong thư mục.

## Hướng dẫn sản xuất
- Xuất Gerber từ thư mục `04_GERBER/` và gửi cho nhà sản xuất.
- Tham khảo `05_SMT/` để lắp ráp linh kiện.
- Kiểm tra thiết kế bằng DRC trong Altium trước khi sản xuất.

## Ghi chú
- Đảm bảo kiểm tra kết nối RF và nguồn điện trước khi sử dụng.
- Tài liệu tham khảo bổ sung có trong `07_REF/`.

## Liên hệ
- Tác giả: [baobuibk]
- GitHub: [https://github.com/baobuibk]
