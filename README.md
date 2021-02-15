# ServeIndia app

Team project (size 3)
Developed a cross-platform app in flutter where users can make requests to different departments like BMC, Firebrigade, etc. 
The user needs to signin/register and just need to select image form gallery and that's it. That image will will sent as an input to our flask api where our deep learning will run on that image and will send a response back. If the image is recognised as a fire image then notification(in the Fire Department module as well as via a mail) will be sent to the Fire Department along with user details, image latitue, longitute and address. If the image is recognised as a pothole image then notification(in the Pothole Department module as well as via a mail) will be sent to the Fire Department along with user details, image latitue, longitute and address. If the image is recognised as non-fire and non-pothole, then the user will need to select other image.
The flask api is hosted on Heroku.
Admins(Persons handling fire and pothole department module) will get the notification via email as well as in the app and he can further work on the requests.



