We will trace where the “Registered” is. 

We see that if eax = ecx = 5 and `sub eax, ecx` lead to `eax = 0`. And then test `eax` = 0 or not and let zero flag = 1 and `jump` to `loc_401037`, and so on jump to `loc_401042`.
What we need to do is make “test eax, eax != 0”. We just need change the value `eax` and `eca` to be difference.

![image](https://github.com/user-attachments/assets/99df793d-dd49-459c-b406-72ddd9973ce6)


