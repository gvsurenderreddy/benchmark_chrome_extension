benchmark_chrome_extension
==========================

This a modified version for Chrome Benchmark extension, including the timing measurement features for page load time, TLS tunnel setup time on client end, TCP setup time and client response time. The timing measurements are done using the navigation API --> http://www.html5rocks.com/en/tutorials/webperformance/basics/ . The reference to original chrome benchmark extension can be found here http://www.chromium.org/developers/design-documents/extensions/how-the-extension-system-works/chrome-benchmarking-extension

Instructions for adding benchmark_extension to chrome
1) Open Chrome, type chrome://extensions in the address bar and press enter.

2) Check the developer mode checkbox.

3) Press Load Unpacked Extension and browse to benchmark-extension\benchmark-extension.

And this would install the extension to your chrome browser.

Note:- In order to use the extension (after installation), one needs to start chrome with --enable-benchmarking option. For this please browse to chrome.exe on your system and issue the following command through command line-

chrome.exe --enable-benchmarking

