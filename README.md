# angular-paystack
Simple AngularJS(1.x) wrapper for interfacing the excellent Paystack javascript lib.This essentially gives you an "Angular way" to expose the client API in your
Angular applications. 

>## Bonus Feature
It exposes a callback for functionality that should be called only when the 
Paystack library and UI Iframe have fully loaded. This was created out of necessity
as some calls that were being made would return **undefined** sometimes
and work properly other times, depending on internet connection speed.

> Server endpoints required by this library would be mocked by the Apiary.io service, to enable users test the library without having to setup a server.

##TODO
Stop procrastinating and actually upload the code :(
Include tests.
