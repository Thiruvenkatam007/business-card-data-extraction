# Business Cards Data Extraction
Hello guys this is the app i created to extract data from visiting and business cards.This app can also be used to extract data from any image files.
Enjoy the app and HAPPY CODING😉


![bz_front_page](https://user-images.githubusercontent.com/113424127/223333252-bbf37322-4011-4dc5-8d63-23269335a8ca.png)

## This is the frontend view of Database side

### My streamlit app link
>[My app link](https://thiruvenkatam007-business-card-data-extraction-app-sjr4wh.streamlit.app/)

Lets see the codes step by step 

### To extract datas from image i used EASYOCR in this project.To use easyocr you need to install pytorch also.(please see the requirements.txt file)
**Please install requirements.txt.**
#### step:1 
I created a function.py file to create all required function in that file. And imported all required packages
![import](https://user-images.githubusercontent.com/113424127/223334400-80b05245-e376-4b6f-9d48-c97a36e058f0.png)
#### step:2
I created a function to extract datas from image and to separate all the extracted data using regular expression.(for detailed code see funtion.py file)
![upload database](https://user-images.githubusercontent.com/113424127/223335096-d0641374-4ea5-48f5-ad03-4dbd6f699726.png)
#### step:3
To view extracted data in image format i used opencv package to view the Image view of data in app 
![extract image data](https://user-images.githubusercontent.com/113424127/223335415-7c19f981-e0dd-4020-85e4-12cb29e7cbb4.png)


After creating all the functions i created the streamlit app using the function and its very simple app only.(you can see the app code in app.py file)

### I think this project will be useful to you foster your knowledge in Image data extraction using easyocr AND Happy coding😁
