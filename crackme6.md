In this program, we need to remove the nag, as well as make the program say `Clean crack! Good Job!` when clicking on the button `Re-Check`.

![image](https://github.com/user-attachments/assets/4d4d4e22-cc51-4c5d-a9d6-6c0ae1716436)

![image](https://github.com/user-attachments/assets/7a422b87-0f37-459c-aca7-5e26eebf1d74)

To go through the nag and bullshit screen, we need to make the `jmp` command in line `00401094` executed. So the two `jump` before must be disabled.

![image](https://github.com/user-attachments/assets/b9f4906d-c800-400a-9bec-0c1df4e4830e)

We  just need chage from `jz` to `jnz`.

![image](https://github.com/user-attachments/assets/5213ad59-0b6d-404e-ae48-f1916ce7399a)

![image](https://github.com/user-attachments/assets/944648c1-bfe6-4131-9057-f21eb0bf99e4)
