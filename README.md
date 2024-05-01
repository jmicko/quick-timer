# Quick Timer

## Description

A pwa that will start a timer with a predefined duration. The default should be 4 minutes, and the user should be able to change the duration and have it save to their device. The timer should start when the app is opened, the idea being that if they have a timer that they use constantly, they can just start it quickly by opening the app. This removes the overhead of needing to set the timer every single time. For example, I use a timer every day to make coffee. It's always the same duration, and I am tired of setting it every single day. I want to just open the app and have the timer start running.

When the time is up, it should make a beeping sound and the screen should optionally flash red. This flashing should be a setting that can be turned on, but is off by default for the sake of users with photosensitive conditions.

There should be a stop button to stop the alarm or stop the timer before it runs out. There should also be a reset button to restart the timer at it's original length. The stop button should be on the right of the time display, and the reset button should be on the left of the time display to avoid accidentally hitting the wrong button.

Additionally, the app should support multiple timers. The default timer can be set by the user, and the app will always start the default timer when opened. Timers should be displayed in a list view.

The app should not require a back end infrastructure of any sort. It should rely completely on html, css, and javascript. such that it can be served by any static web host. It should not require a database, as there will be no need for user accounts, and all user data will be stored locally on the device.

## Usage

```bash
npm install # or pnpm install or yarn install
```

### Learn more on the [Solid Website](https://solidjs.com) and come chat with us on our [Discord](https://discord.com/invite/solidjs)

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.\
Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

### `npm run build`

Builds the app for production to the `dist` folder.\
It correctly bundles Solid in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

## Deployment

Learn more about deploying your application with the [documentations](https://vitejs.dev/guide/static-deploy.html)
