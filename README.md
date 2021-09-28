# Converting PDF file to Image Python Project

# Overview  
This is a GUI application to convert a PDF file into an image PNG file through simple steps.

![pdf2img](https://user-images.githubusercontent.com/87378628/135120383-b7200cf6-6113-4861-b92d-870120a93c15.png)

# Usage and set up
![package](https://user-images.githubusercontent.com/87378628/135120499-f13dedca-080a-443f-9520-d1633b441c96.png)

PDF2IMG GUI App needs the following Python packages to be installed: 
- pdf2image
- tkinter
- PIL 

You can install them using pip install -r requirements.txt. 

# How to use
After running the code, a GUI window will appear. 
![display](https://user-images.githubusercontent.com/87378628/135120639-1e6260f3-c5cf-42d6-b39e-a7f42e97bfa5.png)


If we paste the file location of the PDF file into the entry box and press Convert, the application will automatically convert into an image and save in the folder including the app.
![success](https://user-images.githubusercontent.com/87378628/135120737-e3c55302-e91c-498c-8038-8b0acab7095c.png)


However, if no PDF file matching with your file location is found, there will be a message box to let you know that.
![nopdffound](https://user-images.githubusercontent.com/87378628/135120899-979452ca-bcfb-4cb7-a889-3f60a1a70070.png)
