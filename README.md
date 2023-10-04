# Digital-Clock-Python
the digital clock displays not only the time but also the current date, which makes it more informative. The modern "Arial" font is used for a more contemporary look, and the clock is placed in a frame with padding to give it a well-defined, clean appearance. The window is resizable.

1️⃣ 𝐈𝐦𝐩𝐨𝐫𝐭𝐢𝐧𝐠 𝐌𝐨𝐝𝐮𝐥𝐞𝐬:

![codeimage-snippet_4 (1)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/6d9e1fed-84b4-4f1c-be3a-f5fb160021d4)

- The code imports the 𝒕𝒌𝒊𝒏𝒕𝒆𝒓 module for creating GUI applications and the 𝒕𝒊𝒎𝒆 module for handling time-related operations.


2️⃣ 𝐂𝐫𝐞𝐚𝐭𝐢𝐧𝐠 𝐭𝐡𝐞 𝐌𝐚𝐢𝐧 𝐖𝐢𝐧𝐝𝐨𝐰:

![codeimage-snippet_4 (2)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/bcfa0957-5ea3-4887-b33e-d375d8a6d018)

- This code creates the main application window using 𝑻𝒌().
- It sets the window's title to "𝑲𝒂𝒏𝒊𝒛'𝒔 𝑫𝒊𝒈𝒊𝒕𝒂𝒍 𝑪𝒍𝒐𝒄𝒌."


3️⃣ 𝐖𝐢𝐧𝐝𝐨𝐰 𝐑𝐞𝐬𝐢𝐳𝐚𝐛𝐢𝐥𝐢𝐭𝐲 𝐚𝐧𝐝 𝐌𝐢𝐧𝐢𝐦𝐮𝐦 𝐒𝐢𝐳𝐞:

![codeimage-snippet_4 (3)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/3ed9d20d-7fad-4c82-baa6-4e8b6f45dfff)

- This code allows the window to be resized both horizontally and vertically (the first True argument) and sets a minimum window size of 300 pixels in width and 100 pixels in height.

4️⃣ 𝐓𝐢𝐦𝐞_𝐮𝐩𝐝𝐚𝐭𝐞() 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧:

![codeimage-snippet_4 (4)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/445ee9de-0d0a-4ead-bf59-781e17c0a0f9)

- 𝒕𝒊𝒎𝒆_𝒖𝒑𝒅𝒂𝒕𝒆 is a function defined to update the time and date displayed in the GUI.
- It gets the current time and date using 𝒍𝒐𝒄𝒂𝒍𝒕𝒊𝒎𝒆() and formats them into strings using 𝒔𝒕𝒓𝒇𝒕𝒊𝒎𝒆().
- The formatted time and date strings are then updated in labels (𝒕𝒊𝒎𝒆_𝒍𝒂𝒃𝒆𝒍 𝒂𝒏𝒅 𝒅𝒂𝒕𝒆_𝒍𝒂𝒃𝒆𝒍).
- Finally, the function schedules itself to run again after 1000 milliseconds (1 second) using 𝒓𝒐𝒐𝒕.𝒂𝒇𝒕𝒆𝒓(1000, 𝒕𝒊𝒎𝒆_𝒖𝒑𝒅𝒂𝒕𝒆), ensuring that the time is continuously updated.

5️⃣ 𝐂𝐫𝐞𝐚𝐭𝐢𝐧𝐠 𝐚 𝐅𝐫𝐚𝐦𝐞:

![codeimage-snippet_4 (5)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/43792507-7243-4634-916d-17a0618d1488)

- A frame is created to contain the labels (𝒕𝒊𝒎𝒆_𝒍𝒂𝒃𝒆𝒍 𝒂𝒏𝒅 𝒅𝒂𝒕𝒆_𝒍𝒂𝒃𝒆𝒍).
- The frame has a black background with padding (𝒑𝒂𝒅𝒙 and 𝒑𝒂𝒅𝒚) to provide some spacing around the labels.

6️⃣ 𝐂𝐫𝐞𝐚𝐭𝐢𝐧𝐠 𝐋𝐚𝐛𝐞𝐥𝐬 𝐟𝐨𝐫 𝐓𝐢𝐦𝐞 𝐚𝐧𝐝 𝐃𝐚𝐭𝐞:

![codeimage-snippet_4 (6)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/318ec0bb-dafd-4f17-b279-83fd7415a069)

- Two labels are created: 𝒕𝒊𝒎𝒆_𝒍𝒂𝒃𝒆𝒍 for displaying the time and 𝒅𝒂𝒕𝒆_𝒍𝒂𝒃𝒆l for displaying the date.
- These labels are given specific fonts, background colors, and foreground (text) colors.
- They are added to the frame using 𝒑𝒂𝒄𝒌().

7️⃣ 𝐈𝐧𝐢𝐭𝐢𝐚𝐥𝐢𝐳𝐢𝐧𝐠 𝐭𝐡𝐞 𝐓𝐢𝐦𝐞 𝐔𝐩𝐝𝐚𝐭𝐞:

![codeimage-snippet_4 (7)](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/56c2efd0-e37a-42ad-990c-27608d2f3966)

- The 𝒕𝒊𝒎𝒆_𝒖𝒑𝒅𝒂𝒕𝒆 function is called initially to start updating the time and date.
- Finally, the main loop of the Tkinter application is started using 𝒓𝒐𝒐𝒕.𝒎𝒂𝒊𝒏𝒍𝒐𝒐𝒑(). This loop keeps the GUI application running and responsive to user interactions.

🐍 𝐏𝐲𝐭𝐡𝐨𝐧 𝐂𝐨𝐝𝐞:
![codeimage-snippet_4](https://github.com/kaniz-codes/Digital-Clock-Python/assets/138873297/e020a8ea-e6d8-42f7-ab3d-ecb1f84a430d)
