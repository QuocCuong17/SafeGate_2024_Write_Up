# **💡Lab: Excessive trust in client-side controls**
---
### **Mô tả**
Bài lab này có một **lỗ hổng logic** do **giá trị của sản phẩm** được kiểm soát và xác thực **trên phía client** thay vì phía server. Điều này cho phép kẻ tấn công thay đổi giá trị của sản phẩm khi gửi yêu cầu mua hàng đến server, dẫn đến việc **mua hàng với giá $0**.

### **Mục tiêu**
Mục tiêu của bài lab này là khai thác **lỗ hổng logic** do sự tin tưởng quá mức vào kiểm soát phía client để lấy được hàng hóa với giá $0. 

---
Đăng nhập với wiener/peter
[![image](https://hackmd.io/_uploads/Hy78oI99C.png)](https://hackmd-prod-images.s3-ap-northeast-1.amazonaws.com/uploads/upload_9c06d6eaff185c9687d487affa7f0faf.png?AWSAccessKeyId=AKIA3XSAAW6AWSKNINWO&Expires=1723654141&Signature=X4PGJ%2FF21NQFOTFzwOOejlslN3M%3D)
<br>
Test thử chức năng thêm vào giỏ hàng
![image](https://hackmd.io/_uploads/BkQii859R.png)

Bắt request gửi sang Repeater để phân tích

Sửa giá về 0, 1 respone 302 được trả về nhưng trong giỏ hàng vẫn trống -> khả năng không nhận giá 0
![image](https://hackmd.io/_uploads/r12L2L9qC.png)

Sửa thành giá tiền âm cũng không được
![image](https://hackmd.io/_uploads/Sy2tnI95C.png)

Chỉ chấp nhận giá tiền >0, sửa giá thành 1 thì được
![image](https://hackmd.io/_uploads/SkxA2Ic5A.png)

Bây giờ giá đã nhỏ hơn số dư, có thể mua hàng


Nhấn **Place Order** đơn hàng được đặt thành công, Bài lab được ***hoàn thành***
![image](https://hackmd.io/_uploads/H1IPTUqqC.png)
