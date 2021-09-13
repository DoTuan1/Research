Đầu tiên ta cũng đăng nhập vào trong tài khoản lấy cookies và decode

![image](https://user-images.githubusercontent.com/63194321/133049674-4b6bc96f-4d59-4423-8950-57b0172f117c.png)

![image](https://user-images.githubusercontent.com/63194321/133049709-817a7db4-66bd-4c34-ad88-00128e465f02.png)

Tiếp thep ta thay biến user name bằng `administrator` và gửi đi.

![image](https://user-images.githubusercontent.com/63194321/133050133-0375021e-3c7a-4897-98e9-c87d26f7e682.png)

ta gặp phải lỗi `access token` của `administrator` không chính xác. Theo gợi ý của bài thì ta sẽ so sánh `access token` với `0` vì trong PHP khi so sánh `0` với 1 chuỗi sẽ luôn trả về `true`

![image](https://user-images.githubusercontent.com/63194321/133052808-a8e3d252-cdb7-4957-bf51-3c40dbeec0ff.png)

![image](https://user-images.githubusercontent.com/63194321/133052873-04117deb-3cd7-4b21-9db8-eeb0728f22f3.png)

![image](https://user-images.githubusercontent.com/63194321/133053123-7585abea-ad72-4b8e-b63d-a77da3425b56.png)
