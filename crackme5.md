In this program, we need a username and serial number.

![image](https://github.com/user-attachments/assets/f568a2d2-1e60-45e9-bc77-e5768f6836b1)

In lines `00401190` through `004011AA`, it's doing a string comaparison with the string stored in `eax` and `ecx`.

In each loop iteration, the program checks two characters simultaneously, then increments the string indices by 2.

In line `00401190`, the first character of the input is moved to `dl` and it is compared to the first character on `00401192`.

In line `0040119A`, the second character of the input is moved to `dl` and it is compared to the second character on `0040119D`.

In line `0040116A`, we see that there is a string formatting of `%s-%d%d%d`.

![image](https://github.com/user-attachments/assets/1f4fb86f-5b6c-42b2-9070-a8a3653e7498)

