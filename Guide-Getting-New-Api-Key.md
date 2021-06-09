# How to get a New API Key : A Guide

1. Goto [https://selfregistration.cowin.gov.in/](https://selfregistration.cowin.gov.in/) on the browser of your choice

2. Open the Developer Console.

<p align="center">
    <img src="images/developer-tools-network-tab.PNG"/>
</p>
3.From the Network Options, select Offline
<p align="center">
    <img src="images/dev-tools-network-options.png"/>
</p>
4. Enter your mobile number and click on Get OTP
5. In the network tab you will see an XHR request to **generateMobileOTP**. Click on that and scroll down to Request Payload Section
<p align="center">
    <img src="images/gen-otp-request.PNG"/>
</p>

6. Click on View Sources
<p align="center">
    <img src="images/gen-otp-source.PNG"/>
</p>

7. The Long String you see after "secret":, and inside the quotations is your new API Key.