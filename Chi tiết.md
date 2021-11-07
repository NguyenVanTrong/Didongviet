                                                                     Ngày:07/11/2021                                                                             
                                                                     Reporter:Ngô Đức Văn                                                                          
                                                                     Tên lỗi:Business Logic                                                                           
                                                                     Website: https://mia.vn/                                                                                                                       


Đầu tiên thử ấn vào mua một món hàng xem như thế nào,thấy ở mục số lượng không cho điều chỉnh xuống được nữa                                                                                                                       
![254548654_1055133151911479_1349733565979628889_n](https://user-images.githubusercontent.com/88313289/140636405-01e0a9e2-33aa-43f9-802f-fb243315d361.png)
Tiếp theo thử dùng Burp Suite để bắt request và nhận lại được như sau:                                                                                                                       
<img width="960" alt="2" src="https://user-images.githubusercontent.com/88313289/140636514-7d7a8a41-2ae0-4e32-8975-17ea2d82c35b.png">

Ở mục quantity thử chỉnh lại cho nó bằng -1 xem response sẽ như thế nào và kết quả là

![254348795_1511345482559639_2926598337918481179_n](https://user-images.githubusercontent.com/88313289/140636607-0eedec4c-319d-4ba6-af77-6f7d2330cca5.png)

Ta thấy được bây giờ số tiền ở mục thanh toán đang là số âm nên thử chọn thêm vài món nữa cho số tiền âm đó lớn hơn và chọn cho nó thành số dương thì thôi

![254345002_415120206724074_5658862723494189288_n](https://user-images.githubusercontent.com/88313289/140636711-d8e60515-6116-4c82-ac2c-211e07f8d945.png)

Thấy được hiện tại đang có 5 vali ở mục một đang là số âm nên không cần tính và tổng số tiền của 8 món hàng còn lại là 9.000 vnđ


https://user-images.githubusercontent.com/88313289/140636975-be8da582-29f6-4d61-bcb8-2effb23f50d3.mp4


