# BT01 (07/01/2025): CÀI ĐẶT MÔI TRƯỜNG LẬP TRÌNH
## 1. Cài đặt Node js.
### - Truy cập trang https://nodejs.org/en/download/. Chọn Windows Installer (.msi) như hình: ![image](https://github.com/user-attachments/assets/95672c44-b730-42e5-a7d2-bef0b2b72b30)
### - Chạy file đã tải. Kiểm tra phiên bản cài đặt bằng cách chạy lệnh "node -v" trong cmd. Nếu hiện kết quả như hình là cài đặt Node js thành công. 
#### ![image](https://github.com/user-attachments/assets/a80cd637-b37e-4cd4-990b-5bc3c015aaca)
## 2. Cài đặt jdk cho windows.
### - Truy cập trang https://www.oracle.com/java/technologies/downloads/#jdk23-windows. Chọn x64 Installer như hình: ![image](https://github.com/user-attachments/assets/497bfba5-15dc-41a9-9e1e-82de14142ffd)
### - Chạy file đã tải. Kiểm tra phiên bản cài đặt bằng cách chạy lệnh "java --version" trong cmd. Nếu hiện kết quả như hình là cài đặt jdk thành công. 
#### ![image](https://github.com/user-attachments/assets/cf129c74-d7b7-4479-a9ef-864a152d079d)
## 3. Cài đặt Androi Studio.
### - Truy cập trang https://developer.android.com/studio. Tải về và cài đặt.
### - Cấu hình Androi Studio: Tại màn hình như hình dưới, chọn More Actions --> SDK Manager. 
#### ![image](https://github.com/user-attachments/assets/3b12198c-141f-4198-a5b9-4d403cbc53df)
### - Tại tab SDK Platforms, đảm bảo các mục được tích như hình dưới: 
#### ![image](https://github.com/user-attachments/assets/2cf50642-0cda-4184-be97-07ed779e44bf)
### - Tại tab SDK Tools, đảm bảo các mục được tích như hình dưới: 
#### ![image](https://github.com/user-attachments/assets/1fafa86b-daaf-45ee-95d4-77de7c9f7c4e)
#### ![image](https://github.com/user-attachments/assets/3f474364-a859-4abf-af50-83acc8c3990a)
#### ![image](https://github.com/user-attachments/assets/37022399-d44e-4bf1-869c-0140ad8da685)
## 4. Tạo dự án.
### - Mở cmd và điều hướng đến thư mục lưu dự án sẽ tạo.
### - Chạy lệnh "npx create-expo-app@latest bt01". (Lưu ý: bt01 là tên dự án). Ảnh demo sau: 
#### ![image](https://github.com/user-attachments/assets/94f41cb7-705e-46eb-987a-ec795d9e02a2)
## 5. Tạo và khởi chạy máy ảo Androi.
### - Tại màn hình như hình dưới, chọn More Actions --> Virtual Device Manager.
#### ![image](https://github.com/user-attachments/assets/ac16ffb1-93d0-464e-a807-adb56d5f637e)
### - Nếu muốn tạo máy ảo, click vào biểu tượng "Create Virtual Device" để tạo: 
#### ![image](https://github.com/user-attachments/assets/0902d28c-1e7a-413d-a843-f0e5b5773eae)
### - Nếu đã có máy ảo, click vào biểu tượng "Start" ở máy ảo cần để khởi chạy: 
#### ![image](https://github.com/user-attachments/assets/a3f8d817-4968-4731-8dc5-6485ee58785a)
## 6. Code và chạy dự án đầu tiên.
### - Mở dự án đã tạo ở bước 4 bằng Visual Studio Code.
### - Mở terminal mới tại Visual Studio Code.
### - Chạy lên "npm start" để chạy dự án. Ảnh demo bên dưới:
#### ![image](https://github.com/user-attachments/assets/698a8b92-6c6c-49c3-8c77-18ca41823830)
### - Khi terminal trả về kết quả như hình bên dưới, nhập tiếp a để chạy dự án trên máy ảo Androi đã chạy ở bước 5.
#### ![image](https://github.com/user-attachments/assets/c4f0b1c7-b9fb-4ac9-89b1-a4820e3876b1)
### - Dự án sẽ chạy từ file index.tsx, kết quả máy ảo như hình sau là đã chạy thành công dự án. Bây giờ hãy thực hiện yêu cầu được giao để tạo ra dự án cho riêng mình.
#### ![image](https://github.com/user-attachments/assets/6afc46d0-f426-479a-a018-ca481dd5fbb7)
