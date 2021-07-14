# Recording

![Recording](./image.png)

### Live example

**[See it in action here ➡️](https://dailyjs-recording.vercel.app)**

---

## What does this demo do?

- Use [startRecording](https://docs.daily.co/reference#%EF%B8%8F-startrecording) to create a video and audio recording of your call. You can read more about Daily call recording (and the different modes and types) [here](https://docs.daily.co/reference#recordings)
- Supports both `cloud` and `local` recording modes (specified when creating the room or managed using the Daily dashboard)
- Coming soon: supports different recording layouts and composites
- Coming soon: use the Daily REST API to retrieve a list of cloud recordings for the current active room

**To turn on recording, you need to be on the Scale plan. There is also a per minute recording fee for cloud recording.**

Please note: this demo is not currently mobile optimised

### Getting started

```
# set both DAILY_API_KEY and DAILY_DOMAIN
mv env.example .env.local

yarn
yarn workspace @dailyjs/recording dev
```

## Deploy your own on Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/daily-co/clone-flow?repository-url=https%3A%2F%2Fgithub.com%2Fdaily-demos%2Fexamples.git&env=DAILY_DOMAIN%2CDAILY_API_KEY&envDescription=Your%20Daily%20domain%20and%20API%20key%20can%20be%20found%20on%20your%20account%20dashboard&envLink=https%3A%2F%2Fdashboard.daily.co&project-name=daily-examples&repo-name=daily-examples)