## self-destruct writeup
- description show that, we need to backup the disk before running, that's really helpful because the vm will destroy itself when we click run

![image](https://github.com/user-attachments/assets/ff1d7c3a-11d5-462e-8b96-9338c92a89c6)

- it can be opened again
- usually i always examine the disk before run it so i need to mount it 

![image](https://github.com/user-attachments/assets/bdeef9f0-c421-4b81-ac27-40475533a341)

- first, convert this disk to linux virtual image, then show the infomation about the volumes

![image](https://github.com/user-attachments/assets/d7aa8b92-cc77-4f9c-b182-1955872c849b)

- calculate the offset and attach the image to loop dev 

![image](https://github.com/user-attachments/assets/ff654346-e285-4f6d-b40b-3da5e67fcec0)

- mount that loop dev 

![image](https://github.com/user-attachments/assets/531f908a-8e6b-4f36-b1a7-c7264510e2fc)

- just a simple command to break it down

  ![image](https://github.com/user-attachments/assets/c0f3356d-8c05-4d59-86b4-f149db0e142d)

  ![image](https://github.com/user-attachments/assets/0d0bba63-ed98-42b2-ad4d-993094d1f10c)


