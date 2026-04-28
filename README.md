# MyApplication_EXP-11

Aim
To develop an Android application using WebView to display a webpage inside the application and handle web navigation.

Algorithm


1.Open Android Studio and create a new Android application project.


2.Design the user interface using LinearLayout in the XML file.


3.Add a WebView component to the layout file.


4.Initialize the WebView in MainActivity using findViewById().


5.Obtain WebSettings from the WebView using getSettings() method.


6.Enable JavaScript support using setJavaScriptEnabled(true).


7.Set a WebViewClient to open webpages inside the application instead of an external browser.


8.Load a webpage URL using loadUrl() method.


9.Override the onBackPressed() method in MainActivity.


10.Check whether the WebView can navigate back using canGoBack().


11.If possible, move to the previous webpage using goBack(); otherwise close the application.


12.Run the application and verify that webpages load and navigate correctly inside the app.

