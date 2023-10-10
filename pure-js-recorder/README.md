# how the audio recorder develop and collect in refresh platform

1. adopt the webrtc and reference to https://github.com/yuelinghunyu/blog-demo/tree/master/audio

2. modify to use base64 instead blob to play audio, since we cannot use blob due to the restriction of content security policy

3. modify the code to get it work in safari

4. combine the main.js and record.js

5. add function to hide and display div

6. add function to add timer reference https://stackoverflow.com/questions/31405996/find-elapsed-time-in-javascript

7. send the base64 string to google sheet using google app script reference: https://github.com/levinunnink/html-form-to-google-sheet

8. modify the google app script to allow character more than 50000

9. disable to open window when submit form in html reference https://stackoverflow.com/questions/8756584/stop-a-html5-form-posting-refreshing-or-opening-a-new-window-onsubmit

10. if the form have multiple input field, all the value in the input field will combine into one json like format

the index.html cannot run, just use for record