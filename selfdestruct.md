## self-destruct writeup
- nhìn vào mô tả của challenge ta có thể thấy tác giả đã nói chúng ta nên backup lại file disk trước khi chạy 

![image](https://github.com/user-attachments/assets/ff1d7c3a-11d5-462e-8b96-9338c92a89c6)

- và đúng thật khi chạy thì máy ảo tự động hủy chính nó, sau đó không mở lại được nữa
- thông thường mình thấy có đĩa ảo mình thường examine nó trước khi mở nó lên nên là mình đã convert nó ra virtual image của linux

![image](https://github.com/user-attachments/assets/bdeef9f0-c421-4b81-ac27-40475533a341)

- sau khi convert mình sẽ xem các phân vùng như nào

![image](https://github.com/user-attachments/assets/d7aa8b92-cc77-4f9c-b182-1955872c849b)
- thì bài này có những phân vùng như này, chắc chắn extended là phân vùng efi rồi, vậy thì phân vùng kích thước lớn nhất là root của máy ảo linux
- mình sẽ mount nó lên, trước tiên là phải tính offset

![image](https://github.com/user-attachments/assets/ff654346-e285-4f6d-b40b-3da5e67fcec0)

- thêm vài lệnh nữa là mount được lên

![image](https://github.com/user-attachments/assets/531f908a-8e6b-4f36-b1a7-c7264510e2fc)

- với 1 lệnh cơ bản là có thể lấy gần hết flag rồi, phần còn lại của flag trong tệp usr/bin/sush

  ![image](https://github.com/user-attachments/assets/c0f3356d-8c05-4d59-86b4-f149db0e142d)

  ![Uploading image.png…]()

