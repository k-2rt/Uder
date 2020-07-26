# UberApp
This is transportation network app.

# Requirement
- iOS 13.5
- Swift5
- CocoaPods 1.9.1
- Firebase/Core
- Firebase/Database
- Firebase/Auth
- Firebase/Storage
- GeoFire >= 1.1

# Functions
- CRUD function
- Authenticate
- Search locations
- Generate a Polyline
- Set a pin
- Create a Circular progress bar
- Slide a menu

# Description

This tool is based on Uber App. <br/>
Storybord does't use.

## General Flow

First, sign in from login view. You can choose user type which is rider or driver when you sign up. 
<br/>

![](https://user-images.githubusercontent.com/44741473/88480486-1b183400-cf91-11ea-81e3-d5389185dc02.gif "LoginView")


Left one(iPhoneX) is Driver side. Right one(iPhone11) is Passenger side.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88479396-d937bf80-cf89-11ea-824a-698bbd1db6d8.png "UserAndDriverViews")

Passenger search a destination and generate polyline for one.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88480987-20c34900-cf94-11ea-9b8a-3f59b758c5d8.gif "Searching")

Start animation of circular progress bar when passenger pressed a confirm button.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88480289-2c147580-cf90-11ea-922f-a424dd7e2a30.gif "Pulsing")

A button of driver side changes to Pickup when driver moved near passenger.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88479575-194b7200-cf8b-11ea-8b45-03e765e6a372.png "DriverArrived")

Passenger pressed cancel button then clear trip status. 
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88481569-371ed400-cf97-11ea-8e90-31bf6bf1a499.png "PressedCancel")

Driver pressed a pick up button, generate a polyline to destination.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88479604-4ef05b00-cf8b-11ea-9695-f078b2959caa.png "GoDestinationWithPassenger")

Driver drop off passenger.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88481572-3ab25b00-cf97-11ea-8e13-8708eeedbe92.png "ArrivedDestination")

Alert finish passenger side.
<br/>
<br/>
![](https://user-images.githubusercontent.com/44741473/88479636-8ced7f00-cf8b-11ea-9ada-77755b4231ce.png "FinitTrip")


# Building
UberApp uses CocoaPods for managing the installation of third-party libraries. <br/>
If you don't already have it installed, here's how you can do so:
Using RubyGems
```
$ sudo gem install cocoapod
```
Using Homebrew
```
$ brew install cocoapods
```
Run **`$ pod init`** and **`$ pod install`** in project's root directory.
