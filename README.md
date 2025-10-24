Nguyễn Văn Song

K215480106043

K57KMT

                                                                                                                           Bài Tập 2
                                                                                                                           
1. Cài đặt Apache web server
   <img width="1920" height="1080" alt="Ảnh chụp màn hình 2025-10-19 215409" src="https://github.com/user-attachments/assets/2e386700-1ef4-4f5b-9b0c-afa49176d233" />
2. cài đặt và Vô hiệu hoá IIS
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d5cd3096-8e9e-48b9-8d97-789e375d5ff1" />
   vô hiệu hóa:
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fc969b0c-a93e-48f0-8537-ad613c4ba17f" />
   <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/35ebd6fc-b90a-42dd-8d3e-39c6b3c8c712" />
- Download apache server, giải nén ra ổ D, cấu hình các file:
  + D:\Apache24\conf\httpd.conf
    <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b98dcd49-0d04-4337-a5bc-93904a276926" />
  + D:Apache24\conf\extra\httpd-vhosts.conf
    <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4cd463ff-e7bc-48ea-aee8-9345986c1819" />

2.2. Cài đặt nodejs và nodered => Dùng làm backend:
- Cài đặt nodejs:
<img width="1097" height="606" alt="image" src="https://github.com/user-attachments/assets/1c29da8b-77d7-420d-b20c-80a76d894928" />

 - Cài đặt nodered
   <img width="937" height="979" alt="Ảnh chụp màn hình 2025-10-20 213927" src="https://github.com/user-attachments/assets/888c07af-373c-456a-bf54-c0a88b46b0bb" />

- CÀI NSSM
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/08cef0b7-7f86-4359-b946-587ff309aa68" />
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b105ea51-2636-458a-a47b-47dd4802d7fe" />

2.4. Cài đặt thư viện trên nodered:
<img width="1920" height="1080" alt="Ảnh chụp màn hình 2025-10-21 210753" src="https://github.com/user-attachments/assets/179228cc-cf5b-41b5-8aa1-b1341ffb0da4" />

2.5. tạo api back-end bằng nodered:
logic flow sẽ gồm 4 node 

<img width="1920" height="1080" alt="Ảnh chụp màn hình 2025-10-23 205657" src="https://github.com/user-attachments/assets/99be2387-4f35-4954-b1a1-82de81e560e1" />

test api thông qua trình duyệt

<img width="1920" height="1080" alt="Ảnh chụp màn hình 2025-10-23 213923" src="https://github.com/user-attachments/assets/ef4b968d-fd52-4f67-8b4c-0a8d8c062412" />

2.6. Tạo giao diện front-end:

html
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/87c38aa2-57a0-46d1-9b94-6c428ad689ee" />
css
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a0fbb7b7-e879-458f-a1fb-d140a52d8a16" />
 js
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/490ce2e3-cb95-4ae4-a8c0-868c9415d0c6" />

3 file này đặt trong thư mục
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fe2cb622-1f97-4ace-9bf1-45ffca68fe33" />

giao diện với kết quả truy vấn
<img width="1920" height="1080" alt="Ảnh chụp màn hình 2025-10-23 223258" src="https://github.com/user-attachments/assets/86e0719e-a792-4ae9-8bf6-2a12addc6536" />

2.7. Nhận xét bài làm của mình
Về quá trình cài đặt phần mềm và thư viện:

Em đã hiểu rõ các bước cài đặt từng phần mềm cần thiết như Node.js, Node-RED, và Apache. Biết cách cấu hình môi trường, thiết lập đường dẫn, và xử lý một số lỗi thường gặp trong quá trình cài đặt (ví dụ: lỗi quyền truy cập, lỗi cấu hình DocumentRoot trong Apache).

Về cách sử dụng Node-RED để tạo API back-end:

Em đã nắm được cách tạo luồng (flow) trong Node-RED để xử lý dữ liệu, dùng các node như http in, function, http response để xây dựng API. Biết cách kết nối với cơ sở dữ liệu (nếu có), và kiểm tra API hoạt động thông qua trình duyệt hoặc Postman.

Về cách front-end tương tác với back-end:

Em đã hiểu cách front-end (HTML, JavaScript hoặc framework như React/Vue) gửi yêu cầu đến back-end thông qua API (HTTP request). Biết được quá trình dữ liệu đi từ front-end → Node-RED → xử lý → trả kết quả lại cho người dùng.
