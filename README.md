# Media tab capture chrome extension
A chrome browser extension that records the current tab and let's you download or play it later.

### API Explanation

1. First step is to initialize the constructor `new RecordRTC_Extension()`.
2. Second step is, pass two parameters on `startRecording`. First paramter is named as `recording-formats` and last parameter is named as `recording-start-callback`.
3. Manually stop the recording using `stopRecording` method. Callback contains two arguments. First argument is `Blob` object and second argument is `error` string.

### Credit where credit is due:
Based on: [https://github.com/muaz-khan/Chrome-Extensions/tree/master/screen-recording](https://github.com/muaz-khan/Chrome-Extensions/tree/master/screen-recording)

### License
[MIT license](https://github.com/muaz-khan/Chrome-Extensions/blob/master/LICENSE)
