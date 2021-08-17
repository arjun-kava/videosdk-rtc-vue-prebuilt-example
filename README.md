# Video SDK No Code Prebuilt App for Vue.

## What is it?

This code sample demonstrates a one-to-one and group video call application built with [Video SDK RTC Prebuilt SDK](https://docs.videosdk.live/docs/realtime-communication/sdk-reference/prebuilt-sdk-js/setup) and [Video SDK RTC JS SDK](https://docs.videosdk.live/docs/realtime-communication/sdk-reference/javascript-sdk/setup)

- Built for serverless video calling experience.
- Scale it upto 5,000 participants with low code.
- 10,000 minutes free on monthly basis.
- Inbuilt video and audio quality optimization.
- Inbuilt chat poll, whiteboard, Q and A support.

![Video API example](./public/prebuilt.jpg)

## Features

- [x] Completely Low code and serverless.
- [x] Video API with real-time audio, video and data streams
- [x] 5,000+ participants support
- [x] Chat support with rich media.
- [x] Screen sharing with HD and Full HD.
- [x] Play realtime video in meeting
- [x] Connect it with social media such as Facebook, Youtube etc (RTMP out support).
- [x] Intelligent speaker switch
- [x] Record your meetings on cloud
- [x] Inbuilt support of whiteboard, poll and Q & A.
- [x] Customize UI as per your needs.

## Browser Support

Visit our official guide for [Browser Support](https://docs.videosdk.live/docs/realtime-communication/see-also/device-browser-support)

## Prerequisites

- Basics of Vue

## Getting started

## SERVER

1. Clone the repo

   ```sh
   $ git clone https://github.com/videosdk-live/videosdk-rtc-nodejs-sdk-example
   ```

2. Copy the `.env.example` file to `.env` file.

   ```sh
   $ cp .env.example .env
   ```

3. Update the api key and secret values in the `.env` file with the ones generated from the developer console.

   ```
   VIDEOSDK_API_KEY=''
   VIDEOSDK_SECRET_KEY=''
   VIDEOSDK_API_ENDPOINT=https://api.zujonow.com
   ```

4. Install NPM packages

   ```sh
   $ npm install
   ```

5. Run the server

   ```sh
   $ npm run start
   ```

## CLIENT

1. Clone current repo

2. Copy the `.env.example` file to `.env` file.

   ```sh
   $ cp .env.example .env
   ```

3. Install NPM packages

   ```sh
   $ npm install
   ```

4. Run the client

   ```sh
   $ npm run serve
   ```

## Resources

Visit, [https://www.videosdk.live/](https://www.videosdk.live/) to generate API key and secret.
