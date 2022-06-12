# Amazon-Web-Scraping
It is software in which you want to insert URL of Amazon Product with Url you have to add two more details like your E-mail address & Price of prouct which should be less.
When product prices is fall down then it will compare your Before Entered Price with Current Product price if it less than Before Entered Price Then it will send you an email on given Reciver Email address.
## Changes To be Done In Webscrapping.py
1. Go on line where it said ```pass1="Paste_Generated_password_here"```. 
2. You should enable your Two-step varification for your E-Mail.
3. To Generate Password for your PC Search on Google '[Google app password](https://www.google.com/search?q=google+app+password)' goto app password site.
4. Now to genereate Password Login your G-mail then in ```'Select app'``` choose option ```'Mail'``` and in ```'Select Device'``` select your device whichever you working on like use Windows so i select ```'Windows Computer'```.
5. Hit Generate password i will generate password for your system it will be Highlited Copy it and Paste it on ```"Paste_Generated_password_here"``` in first step.
6. Go to line where it say ```headers={"User-Agent":'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/77.0.3865.120 Safari/537.36'}```.
7. Then Search on Google '[my user agent](https://www.google.com/search?q=my+user+agent)' copy the text inside card Then paste it here after "User-Agent":
8. Go to Send_mail() Change ```"Enter_sender_email@gmail.com"``` to your G-mail address.
## Execute file
1. Open CMD or Terminal Where ```Webscrapping.py``` is Located. 
2. Enter command ```python Webscrapping.py```.
## Instructions & info
1. ADD Button on UI is to add mutilple product at time.
2. SAVE TO EXCEL will store all info in to Excel file (It cannot be updated).
3. Execute Script it will check product price and compare with stored excel file value then it will send an email.
