# btl

PHẦN A – MIT APP INVENTOR

- Tạo Project mới có tên PTBac2_App

- Tạo Screen1 (About) và đổi các thuộc tính

<img width="1883" height="870" alt="image" src="https://github.com/user-attachments/assets/1cbb4eb9-9a55-4514-826f-042e1a08c60e" />

<img width="918" height="625" alt="image" src="https://github.com/user-attachments/assets/687946ee-8d96-4103-be52-af85aa921f8c" />

- Tạo Screen2

<img width="1883" height="863" alt="image" src="https://github.com/user-attachments/assets/a438ef6a-bf38-45f4-8ef5-e36249d864d2" />

. Giải PT bậc 2

<img width="1887" height="837" alt="image" src="https://github.com/user-attachments/assets/9a3b1e3b-144b-4ea3-bc2d-0edbba403568" />

- Tạo Screen3 có thuọc tính HomeUrl : https://k58kmt.tdh.io.vn

<img width="1836" height="886" alt="image" src="https://github.com/user-attachments/assets/b50787ad-1d47-4894-bd17-7569bf9d8061" />

<img width="913" height="642" alt="image" src="https://github.com/user-attachments/assets/a86bd465-00bc-467d-b823-53159be53636" />

- app chạy trên điện thoại

<img width="400" height="698" alt="image" src="https://github.com/user-attachments/assets/3ab828b7-094c-4793-b84e-039f44617ae9" />

<img width="401" height="643" alt="image" src="https://github.com/user-attachments/assets/3a1c27ca-77d4-4bef-a082-814433fae6ba" />

- MÔ TẢ

 1. Giới thiệu ứng dụng

. Ứng dụng được xây dựng bằng MIT App Inventor gồm 3 màn hình (Screen):

. Screen1: About

+ Hiển thị thông tin cá nhân:

Họ tên

MSSV

+ Có 2 nút:

Mở màn hình Giải toán

Mở màn hình WebView

. Screen2: Giải bài toán đơn giản

+ Giải phương trình bậc 2:

ax² + bx + c = 0

+ Người dùng nhập:

a

b

c

+ Nhấn nút "Giải"
  
+ Hiển thị kết quả nghiệm.
  
. Screen3: WebView

+ Hiển thị một trang web có sẵn.

+ Sử dụng thành phần WebViewer.

+ Tự động hiển thị phù hợp với giao diện điện thoại.

2. Giao diện MIT App Inventor

- MIT App Inventor gồm 2 chế độ chính:

. Designer : Dùng để thiết kế giao diện.

Cho phép:

+ Kéo thả Button
  
+ Kéo thả Label
  
+Kéo thả TextBox

+ Kéo thả WebViewer
  
+ Kéo thả Layout

+ Không cần viết code.

. Blocks : Dùng để lập trình.

Lập trình bằng cách:

+ Kéo block
  
+ Ghép block

Thay cho việc viết mã nguồn.

3. Thanh công cụ trong Designer
   
. Palette : Nằm bên trái.

Chứa các nhóm thành phần:

+ User Interface
 Button
 Label
 TextBox
 Image
+ Layout
 HorizontalArrangement
 VerticalArrangement
+ Media
 Sound
 Player
+ Sensors
 Accelerometer
 LocationSensor
+ Viewer
Mô phỏng màn hình điện thoại.
Dùng để kéo thả giao diện.

+ Components

Hiển thị danh sách đối tượng đã thêm.

Ví dụ:

Screen1
 ├─ Label1
 ├─ Button1
 ├─ Button2
 
+ Properties
Hiển thị thuộc tính của đối tượng.

Ví dụ Button:

Text
Width
Height
BackgroundColor
FontSize
Visible

4. Kéo thả và thay đổi thuộc tính

Ví dụ tạo nút bấm.

Bước 1

Kéo:

  User Interface
  ↓
  Button

vào màn hình.

Bước 2

Đổi thuộc tính:

  Text = Giải phương trình
  
Mục đích

Thuộc tính giúp thay đổi:

  .Nội dung hiển thị
  .Màu sắc
  .Kích thước
  .Vị trí

mà không cần viết code.

5. VerticalArrangement là gì?

VerticalArrangement là một Layout dùng để sắp xếp các thành phần theo chiều dọc.

Ví dụ:

Label

TextBox

TextBox

Button

sẽ hiển thị:

Label

TextBox

TextBox

Button

từ trên xuống dưới.

6. HorizontalArrangement là gì?

Dùng để sắp xếp các thành phần theo chiều ngang.

Ví dụ:

  Label | TextBox
  
7. Block là gì?

Block là hình thức lập trình trực quan.

Mỗi block đại diện cho:

  Biến
  Hàm
  Điều kiện
  Sự kiện

Ví dụ:

  when Button.Click

nghĩa là:

"Khi người dùng nhấn nút."

Ví dụ:

  if delta < 0

nghĩa là:

"Nếu delta nhỏ hơn 0."

8. Bản chất của việc kéo thả Block

Khi ghép block:

  when Button.Click
      set Label.Text to "Hello"

MIT App Inventor sẽ tự động sinh mã chương trình phía sau.

Người dùng không cần viết:

  button.setOnClickListener(...)

như Android Studio.

9. Ưu điểm của Block

Dễ học : Không cần nhớ cú pháp.

Trực quan : Nhìn block là hiểu luồng xử lý.

Ít lỗi cú pháp

Không bị:
;
{}
()

Phát triển nhanh : Tạo ứng dụng đơn giản rất nhanh.

10. Nhược điểm của Block

. Khó làm dự án lớn

Khi nhiều block: hàng trăm block sẽ rất khó quản lý.

. Ít linh hoạt

Không mạnh bằng Java hoặc Kotlin.

. Hiệu năng thấp hơn

Không tối ưu bằng ứng dụng lập trình truyền thống.

11. Backpack là gì?

Backpack là công cụ sao chép block.

Biểu tượng:

🎒 Backpack

ở góc giao diện Blocks.

12. Copy/Paste Block bằng Backpack
    
. Bước 1

Chuột phải block.

Chọn:

  Add to Backpack
  
. Bước 2

Mở Backpack.

. Bước 3

Kéo block từ Backpack ra màn hình.

Mục đích

Dùng lại block:

  Screen1
  Screen2
  Screen3

mà không cần tạo lại.


2. android app

   cài android

   <img width="1903" height="1008" alt="image" src="https://github.com/user-attachments/assets/491b740c-1be9-4c8f-adeb-643cb1400b16" />

# APP1 - DỮ LIỆU TRONG ASSETS

Ý tưởng:

Cẩm nang Android Offline

Chức năng:

Đọc dữ liệu từ guide.json
Hiển thị nội dung lên màn hình
Không cần Internet

- TẠO PROJECT, CẤU TRÚC PROJECT

 . app
 . java
 . res
 . AndroidManifest.xml

 - TẠO THƯ MỤC ASSETS

   app
    └─ src
       └─ main
          └─ assets

   - FILE guide.json

   <img width="1122" height="666" alt="image" src="https://github.com/user-attachments/assets/ebe2683d-820e-4ec4-bba0-4e4156653171" />

-  Thiết kế giao diện bằng XML

  <img width="1277" height="925" alt="image" src="https://github.com/user-attachments/assets/962becd9-7717-4ea9-a03f-9a55e0075820" />

- MainActivity.java
  
<img width="1227" height="862" alt="image" src="https://github.com/user-attachments/assets/46c2d6da-910d-44e7-bc86-4cb036d6864c" />

-Đặc thù dữ liệu

.Dữ liệu dạng JSON.
.Có cấu trúc gồm title và content.

-Thuật toán

   Đọc file JSON
   ↓
   Phân tích JSON
   ↓
   Lấy dữ liệu
   ↓
   Hiển thị lên TextView
   
- Đối tượng hiển thị : TextView

# APP2 (android studio)

- TẠO 2 ACTIVITY MỚI

  <img width="423" height="182" alt="image" src="https://github.com/user-attachments/assets/9e1e0b74-1e56-4634-af63-e7ba55c12cdd" />

- THIẾT KẾ MAINACTIVITY

  <img width="1297" height="991" alt="image" src="https://github.com/user-attachments/assets/bcb78ac2-6ed8-49fd-9bee-ba0caaa9077b" />
