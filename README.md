# An Ambulance Booking Application --Uber Clone for Ambulances--

##### Note - Although this app has been tested on multiple android devices and is working fine, changes are still being made to this app as it is further refined.

### Features:
1. Account creation for Riders and Drivers using Phone Number.
2. OTP verification on login using Firebase UI Phone Auth.
3. Uploading of images of Ambulance Registration Certificate and Driver's License on Cloud, for the authorities to verify the authenticity of Ambulance Service. The App uses Firebase Cloud Store for this purpose.
4. Firebase Realtime Database provides the facility to store and fetch Riders and Drivers information. For the Riders, it provides Real-Time location of all the available ambulances and their details(such as, if it has Life Support System or not).
5. The booking request of a Rider is forwarded to the respective Driver using Firebase Cloud Messaging, a push notification is generated on the Driver's side informing him of the request. A similar push notification is generated on the Rider's side when the Driver accepts or rejects the request.
6. An additional facility is provided to the Riders to call the Drivers, they just made the request to.
7. If the Driver accepts the request of the Rider, he is taken to the Navigation Mode, which shows the Driver on the Map, the shortest path to the Rider, the distance across this path and the expected time to cover this distance.



##### Common to both Riders and Drivers:

1. Signing in using Phone Number:

2. OTP Verification:

3. Driver/Rider profile selection option on first time account creation:



##### Rider:

2. Make a request to some Ambulance:

3. Driver accepting the request notification:

4. Call the Ambulance Driver:

