---
title: Một số định nghĩa
weight: 5
---

Một số khái niệm liên quan đến contact cần chú ý khi sử dụng hệ thống Fobiz.

1. **Contact** là khách hàng lấy được thông qua các kênh quảng cáo khác nhau và được nhập vào hệ thống Fobiz. Các thông tin liên quan đến khách hàng bao gồm: tên, Số điện thoại, link đến tài khoản facebook,....

2. **Trạng thái contact** là tình trạng của mỗi contact sau mỗi lần tương tác với khách hàng thông qua các cuộc gọi thực hiện bởi người dùng
    - L1 - Contact mới đc thêm vào hệ thống. Các trạng thái bao gồm
    - L1.3 - Contact sai (số điện thoại không liên lạc được, số không tồn tại)
    - L2.1 - Rung chuông nhưng không nhấc máy
    - L2.3 - Nghe máy nhưng đang bận, hẹn gọi lại sau
    - L3.1 - Khách quan tâm tới sản phẩm, có thể tư vấn thêm
    - L6.1 - Khách đồng ý mua hàng nhưng hẹn ngày giao xa, cần gọi lại xác nhận trước khi giao
    - L7.1 - Khách đồng ý mua hàng
    - L7.3 - Khách từ chối mua hàng
    - L7.10 - Khách có đơn hàng đã xuất khỏi kho
    - L8.1 - Khách có đơn hàng giao thành công
    - L8.3 - Khách có đơn hàng giao không thành công

3. **Đơn hàng** là thông tin được tạo ra khi khách hàng đồng ý mua hàng, sau khi telesale tương tác với khách hàng. Thông tin đơn hàng bao gồm: tên khách hàng, địa chỉ nhận hàng, ghi chú khi gửi hàng, và các thông tin liên quan đến sản phẩm (số lượng, biến thể, giá tiền), thông tin vận chuyển của đơn hàng

4. **Nguồn contact** là nguồn nhận được contact, cần phải xác định để tính được các thông số liên quan đến hiệu quả marketing. Nguồn contact chính trên hệ thống đang là các quảng cáo từ các campaign
