# Mockup-example-live-stream-shopping

This is an example of how to Live-Stream Shopping can look like when 
embedded into a Commerce website. Uses flv javascript library to grab video stream from RTMP server.

## Getting Started RTMP Server

You will need the RTMP server first. Download the repository below and follow the README information.

Server : https://github.com/maxknu/live-tream-rtmp-server

## Getting Started RTMP Client

You will need the RTMP client (android or iphone app). Download the repository below and follow the README information.

Server : https://github.com/maxknu/react-native-live-stream-rtmp-example

## Config
html page is just a html mockup of Commerce website, configuration is on line ```line 2997 ```

## Change your url to the RTMP server on line 2997
```bash
Replace "YOURRTMPSERVER" on line 2997 inside index.html with your RTMP URL or locally hosted IP

Example: url: 'wss://168.192.1.30/live/Test2.flv' 
```

## Install package
```bash
yarn install
```
## Running the App
```bash
yarn start
```

## Showing stream video
Start the RTMP server
Start your android or iOS app and start streaming
The stream should pop up on the mockup page