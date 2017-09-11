# README

This repository implements an instgram-like app in Ruby on Rails, made in conjunction with Begginner Programers' youtube tutorial "Make an instagram like site in under 30 minutes! (Ruby on Rails)", found at: https://www.youtube.com/watch?v=MpFO4Zr0EPE. It can be run by any user of Ruby on Rails who has downloaded ImageMagick in the proper folder by running "rails s" on the command line and connecting to "localhost:3000". Once there, you can register an account, log in and out, post pictures, and view the posted pictures.

It's functionality includes:  
-Registering accounts:
![Register(1)](https://github.com/hmc-cs-fsouth/Instagram-App/blob/master/Instagram%20Screenshots/Register(1).PNG)
![Register(2)](https://github.com/hmc-cs-fsouth/Instagram-App/blob/master/Instagram%20Screenshots/Register(2).PNG)

-Logging in:
![Login(1)](https://github.com/hmc-cs-fsouth/Instagram-App/blob/master/Instagram%20Screenshots/Login.PNG)
![Login(2)](https://github.com/hmc-cs-fsouth/Instagram-App/blob/master/Instagram%20Screenshots/Login(2).PNG)

-Adding new posts:
![NewPost](https://github.com/hmc-cs-fsouth/Instagram-App/blob/master/Instagram%20Screenshots/NewPost.PNG)

-Veiwing all posts:
![Feed](https://github.com/hmc-cs-fsouth/Instagram-App/blob/master/Instagram%20Screenshots/Feed.PNG)


Dependency:  
Ruby on Rails (If you need to install, I recommend http://installrails.com).

Imagemagick (version 6.9.9 reccomended, can be found at https://www.imagemagick.org/download/binaries/ ).  
  -Make sure ImageMagick is in the directory quoted in the line:  
        Paperclip.options[:command_path] = "C:/Program Files/ImageMagick-6.9.9-Q8"  
   or change the line so it matches
 
I could not test this on Mac, so it is only garenteed to work on windows machines.

Current Bugs:  
On the bottom of the root page, a string of text with information about all uploaded posts appears.
