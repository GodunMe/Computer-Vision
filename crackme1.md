![image](https://github.com/user-attachments/assets/e6d8695d-e9f9-4686-b0f6-cde6ca6c3bc3)
After few run to test the program I found the code that has function to check the serial key, and I also found the seial key right there
![image](https://github.com/user-attachments/assets/36b26c55-358a-419e-bbb0-e6e4bcde2b4e)
So the real serial key is cr4ckingL3ssons
![image](https://github.com/user-attachments/assets/771ab50d-a8a1-49d7-b140-531a3d16446d)
To make the program always show the congrats at any key I need to fix few thing.
First is the jump, I need to remove it and change the value at the eax register from 1 to 0 because if I just change the value in eax prog will corrupted the instructio will be overwrite to another instruction cause is not enough byte for that instruction here.
![image](https://github.com/user-attachments/assets/67d97edf-4082-404a-9417-855608bf9a87)
![image](https://github.com/user-attachments/assets/583b5689-514a-49ca-b1de-eee63ba5a381)
I delete the jump command to get space for the mov command. The jump take 4 bytes and the mov al, 0 take 3 bytes so that is the reason.
Then patch the file and got the result like this:
![image](https://github.com/user-attachments/assets/83e545f7-aae3-43c6-a1b7-57e13f62e68f)
