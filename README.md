Dự án COMM_BOARD - Satellite_COMM_HW_V1.0
Giới thiệu
Dự án COMM_BOARD là một phần của hệ thống phần cứng giao tiếp vệ tinh (Satellite_COMM_HW_V1.0), được thiết kế trên Altium Designer. Bo mạch này được phát triển để hỗ trợ giao tiếp dữ liệu cho các ứng dụng vệ tinh, bao gồm truyền nhận tín hiệu RF và giao tiếp với các thiết bị ngoại vi. Dự án bao gồm sơ đồ mạch (Schematic), bố trí PCB (Layout), và các tệp cần thiết để sản xuất và kiểm tra.

Cấu trúc thư mục
├── 01_DESIGN/
├── 02_Schematic_pdf/
├── 03_BOM/
├── 04_GERBER/
├── 05_SMT/
├── 06_CAD/
├── 07_REF/
├── 08_3D/
└── README.md

Yêu cầu

Phần mềm: Altium Designer phiên bản 21.0 hoặc mới hơn.
Phần cứng: 
Vi điều khiển chính [STM32H745].
Các linh kiện khác theo BOM.

Công cụ khác: 
Phần mềm lập trình firmware (STM32CubeIDE).

Hướng dẫn cài đặt

Tải dự án:
Clone repository về máy:git clone https://github.com/baobuibk/Satellite_COMM_HW_V1.0.git

Mở dự án trong Altium:
Mở Altium Designer.
Chọn File > Open Project và điều hướng đến thư mục 1_COMM_BOARD.
Mở tệp .PrjPcb trong thư mục.
