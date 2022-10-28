# Weather-App
Android Studio Project

In this project, we have build an app that will find the device’s location coordinates(longitude and latitude). Then we will send this data to the API via an API key(which we will see later). The API will send us a JSON from which we will extract the required data that is the temperature and city of the location.


For this app to work we need to ask for three permissions from the system –
Coarse Location – <uses-permission android:name=”android.permission.ACCESS_COARSE_LOCATION”/n>
Fine Location – <uses-permission android:name=”android.permission.ACCESS_FINE_LOCATION”/n>
Internet – <uses-permission android:name=”android.permission.INTERNET”/n>

To get JSON we need to use Volley Library to make an HTTP client request

Volley is an HTTP library that makes networking very easy and fast, for Android apps. It was developed by Google and introduced during Google I/O 2013.

Add ‘implementation com.android.volley:volley:1.1.1’ to the gradle app file.
Create the http for the JSON. For example – “https://api.weatherbit.io/v2.0/current?” + “lat=” + location?.latitude +”&lon=”+ location?.longitude + “&key=”+ api_id1. Here we have already generated API key as well as the location coordinates.
Make a request from this URL and get the data.

➢Layout


![Screenshot (161)](https://user-images.githubusercontent.com/93143666/189376444-9ae93757-7618-410c-a17e-e6dc8ef9c256.png)       


![Screenshot (162)](https://user-images.githubusercontent.com/93143666/189376646-86f5072a-42d5-4cd1-b8cb-9126f69cca03.png)



# Author - 
Xavier Dias


# Contact -
[GITHUB](https://github.com/Xavi007)<br/>
[Instagram](https://www.instagram.com/xavierdias07/)<br/>
[Facebook](https://www.facebook.com/profile.php?id=100017097121241)<br/>


# Support -
If you liked the project, please give it a star ⭐

# Feedback -
If you have any feedback, please reach out to me!!

# Contributing -
Contributions are always welcome!



