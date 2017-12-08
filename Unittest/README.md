# Unittest
Boston University College of Engineering - EC601 HW6 - Unittest of HW2

I created the Testcase sheet that contains the unittests of my resume page and firebase app.

I use monkey test to test automatically. The result screenshots are in this folder. resume page runs well,
but firebase app faild some on-click events. It is because monkeytest can not log-in with google accounts,
which is required by this firebase app.

Furthermore, I tried CrossBrowserTest to test the browser compatibility of my firebaseapp, the results are shown in respective folder. except for safari and ie, the results runs well. It is because the app is based on google.
