Disable-SSLv3-in-Google-Browser-for-OSX
=======================================
this is modifying Google Chrome for OSX and Chromium for OSX by adding startup parameter --ssl-version-min=tls1 retaining normal browser handling

quit browser, run "bash set-tls-google-browser" in a terminal window on OSX, start browser and test at e.g. https://poodletest.com

test in a terminal window, quit browser and type "open -a Chromium.app https://poodletest.com"
