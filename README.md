The ANT+ Plugins is an Android application which allows applications to use ANT+ wireless technology to communicate with millions of ANT+ enabled devices. The plugins communicate with the ANT radio via the ANT Radio Service, and abstract searching for and connecting to devices and ANT+ encoding/decoding into a simple to use, easy to understand API for applications to use.
<br/>
Note: Changelog at bottom.
<br/>

<u>Attention Developers!</u> Using the ANT+ plugins in your app to communicate with ANT+ devices is quick, easy, and free and uses a simplified API that doesn't require referencing technical documents or learning new protocols. Visit the ANT Android Developer page http://www.thisisant.com/developer/ant/ant-in-android/ for more info and to download the SDK.
<br/>

The current version of the plugins supports the following ANT+ profiles:

* <b>Bike Power</b>: Receive power data from ANT+ cycling power meters. Includes seamless support for all power meter types and the new advanced data sent from meters such as the Garmin Vector
* <b>Audio, Video, and Generic Controls profiles</b>: Send and Receive control data with remote controls (IE: use a remote control watch app to control your MP3 player or camera)
* <b>Heart Rate</b>: Receive live heart rate data from heart rate straps produced by many popular manufacturers
* <b>ANTFS Watch downloader utility</b>: Download saved activities from ANTFS enabled watches
* <b>Bike Speed and Cadence</b>: Receive live bike speed, distance, and/or cadence data
* <b>Blood Pressure</b>: Download saved measurement data from blood pressure devices
* <b>Stride-based Speed and Distance Monitor</b>: Receive live speed and distance data from footpods
* <b>Fitness Equipment</b>: Connect to ANT+ enabled fitness equipment to receive live workout data
* <b>Geocache</b>: Search for and receive/send data with remote devices such as the Garmin Chirp
* <b>Weight Scale</b>: Read and download weight data and advanced body measurements such as BMI from ANT+ enabled weight scales
* <b>Environment</b>: Receive temperature data and records from remote temperature sensors such as the Garmin Tempe
<br/>

ANT+ is an established wireless technology with over 60 million devices in the market. With ANT+ you have the opportunity to link to top devices and applications to collect, transfer and track your very own data. ANT+ is an extremely power efficient solution with advanced functionality, that gives you the most reliable data, simply and easily. New apps and devices are continually being developed, with endless opportunity for personal monitoring. See http://www.thisisant.com/directory for all ANT+ certified products and compatible products from all manufacturers.
<br/>

To learn more about ANT+ visit http://www.thisisant.com.
<br/>

Please send any questions to info@thisisant.com.
<br/>

<i><u>Note</u>: This application is a service that other applications use to communicate with ANT+ devices. In order to communicate with ANT+ devices, you will need to run one of these other applications. To test or to try out the plugins you can get started with the sampler app here: https://play.google.com/store/apps/details?id=com.dsi.ant.antplus.pluginsampler
<br/>

<u>Also note</u>: This service requires the ANT Radio Service to be installed and not all phones support ANT communication, please refer to the ANT Radio Service listing for more info: https://play.google.com/store/apps/details?id=com.dsi.ant.service.socket.</i>

--------------------------------
<u>Changelog:</u>
--------------------------------
<b>v.2.2.0, posted Sept 8 2013:</b>
-Change: requestAccess methods will now return 'ADAPTER_NOT_DETECTED' on platforms where ANT radio is not built-in to hardware and there are no other adapters plugged-in
-Change: requestAccess methods will now return 'BAD_PARAMS' for requests that have invalid parameter values instead of throwing exceptions
-Change: default device name for devices not saved in the plugin database to '-not saved-' instead of 'unknown'
-Fix: null pointer exception in background scan reported by G&ST
-Fix: geocache plugin to work with unprogrammed chirps
-Fix: bike speed and cadence issues with saving info to the built-in device database
-Fix: bike power plugin crashing using asynchronous request access methods

