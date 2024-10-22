To set the string to ‘REGÍTED’, we need that `jump` not to be executed.

In line `0040385A`, it has a comparison between the value in `7260D0` with `0`.

If equal, the zero flag is set and the `jump` will happen.

![image](https://github.com/user-attachments/assets/72bb6cac-722f-416c-b980-2ca53859b8dd)

We just need to set it from `0` to another number, so the `jump` will not execute.

![image](https://github.com/user-attachments/assets/61987a08-d2be-4b5c-a259-bc33eccfa843)

Done!

![image](https://github.com/user-attachments/assets/5d57ac4d-3ef1-4cde-86fb-1a6440ab805a)
