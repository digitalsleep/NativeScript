##Native Script

![](http://freevector.co/wp-content/uploads/2014/06/nativescript.png)

#What is it
[NativeScript ](https://www.nativescript.org/)

NativeScript is a framework for building native iOS and Android apps using JavaScript and CSS.
NativeScript renders UIs with the native platform’s rendering engine—no WebViews—resulting in native-like performance and UX

#A framework for creating truly native apps for IOS and Android
* windows coming soon(maybe)


*No DOM*

*No Plugins*

##How does it work

Runs JavaScript in a VM on the device

*  JavaScriptCore VM on IOS
*  V8 VM on Android
*  JavaScriptCore VM on WinMobile
*   Full access to Native API's (All of IOS & Android)

##so why should i care about {N}?

*   Truly Native UX
*   Access to huge selection 3rd party JavaScript Libraries
*   Sameday acces to native API's
*   XML UI declaration (I know but it's actually pretty cool)
*   Open Source
*    Allows for resuse of skills and assets
*   Use native libraties for each platform
*   Use JS libraries without DOM dependency
*   Shared UI styles through css
*   Full TypeScript Support*   VS code plugin available


##How to get started(OSX)?
[Install guide](http://docs.nativescript.org/start/quick-setup)

Getting Started
##Installing NativeScript
`npm i -g nativescript`

## Now you have access to the tns command

`$ tns`



##OSX Setup

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/NativeScript/nativescript-cli/production/setup/native-script.rb)"`

Verify the setup

`tns doctor`

creating an new app

`tns create my-app-name`


#Adding platforms
#IOS

`tns platform add ios`

#Android

`tns platform add android`

#Running App

`tns run ios --emulator`
`tns run android --emulator`

#livesync

#IOS
`tns livesync ios --emulator --watch`

#Android
`tns livesync android --emulator --watch`



Angular 2 + NativeScript
The result is a software architecture that allows you to build mobile apps using the same framework—and in some cases the same code—that you use to build Angular 2 web apps, with the performance you’d expect from native code. Let’s look at how it all works by building an app.

[NativeScript Angular](http://docs.nativescript.org/angular/start/introduction.html)



