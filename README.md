# PixPic

## PixPic, a Photo Editing App Built by Our iOS Interns 

<img src="Screenshots/5.5%20Device%200.jpg" width="250" />
<img src="Screenshots/5.5%20Device%201.jpg" width="250" />
<img src="Screenshots/5.5%20Device%202.jpg" width="250" />
<img src="Screenshots/5.5%20Device%203.jpg" width="250" />
<img src="Screenshots/5.5%20Device%204.jpg" width="250" />
<img src="Screenshots/5.5%20Device%205.jpg" width="250" />

What's the best way to teach interns how to write an iOS app? Just let them do it! This app is the result of our interns’ collaboration.
This app was created for educational purposes and we used all our common practices just like we do when creating commercial apps. Read more about AGILE on [our blog](https://yalantis.com/blog/we-just-launched-pixpic-a-photo-editing-app-built-by-our-ios-interns/).

We followed gitflow approach and merge requests in order to check the code. This approach let our senior developers share their valuable expertise with interns. 
Delivering builds for testing was automated through Continuous Integration Server. One of our mentors pretended to be a customer who came to us with an idea for an app. While we were working on the app, he regularly received new builds - in time and after each sprint. Guys went the whole way from an idea and basic design concept  to generating provisioning profiles and certificates and deploying the final build to iTunes Connect.
Here’s where you can check out [the app itself](https://itunes.apple.com/us/app/pixpic-pixel-stickers-kit/id1132190990?mt=8).

We improved the MVC architecture offered by Apple by providing special Router class for every View Controller to decrease coupling and separate different parts of the logic inside of the app. All dependency injections and data transferring go through Routers.
