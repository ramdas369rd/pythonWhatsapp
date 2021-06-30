<h1 align = 'center'>Python to Whatsapp </h1>
<p align = 'center'>Automatically send messages to Whatsapp number using Python</p>
<table align='center'>
<tr>
    <td><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen"></td>
    <td><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">

</tr>
</table>

Sign in your web whatsapp.\
Open PyCharm > Select Terminal (bottom of the page).\
Copy, paste and run this line "pip install pywhatkit"\ 
Its better to update to the latest version, to do that run the following lines one by one\
  python -m pip install - upgrade pip\
  python -m pip install - upgrade pillow\
Type the python code in Pycharm IDE and save your file (eg: Whatsautomation.py)\
   
   import pywhatkit as pw\
      pw.sendwhatmsg('+91xxxxxxxxxx', 'Hello, this is amazing. isn't it?', 13, 06)\
      
  #enter the content in the order "'whatsapp number with country code', 'message', time" \
  #separate the hour and minute with a comma\
  #time should enter in 24Hrs format, for example if its 1.15pm write 13,15\
  
Run the code, it will automatically open the web whatsapp with in the set time and will send the message shortly\
Keep the time 2 or 3 mins ahead if you are a first time user and check the process, and wait for it, it will automatically open the browser and then the text will appear on the char box and will send when the time becomes exactly what you given (here it is 13:06)\
Allow the permission to access the browser by Pycharm from your system settings and run it again with different time\


