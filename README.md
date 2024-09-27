## About this app

CarePulse is a mock medical site that allows patients to sign-up, enter medical and ID information and book appointments with their doctor/s. It also contains an admin panel protected by a passkey that allows admin users to visit a dashboard to schedule, cancel or edit requested appointments.

It was built using NextJs, TypeScript, TailwindCSS, Appwrite, ShadCN, and Sentry.

Sentry was installed to monitor for errors and bugs and will immediately send a report to the site administrator with full details of any occuring error including a video (see screenshot) - the great thing about this is that all details are blocked out to comply with security and in this case hippocratic regulations.

Appwrite was used for the database and storage of documents.


### Functionality & Key Features

The site is fully adjustable for screen sizes ranging from mobile to desktop.

I followed a tutorial created by JavaScriptMastery to become more proficient with TypeScript and NextJs, learn more key principles and best practices in order to expand my portfolio.

CarePulse has been deployed on Vercel and can be viewed here:

https://care-pulse-inky.vercel.app/admin

## Tech Stack

- NextJs
- TypeScript
- TailwindCSS
- ShadCN
- Appwrite
- HTML
- CSS
- Sentry

## Screenshots

### Screenshot of homepage
!["Screenshot of homepage"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/carepulse-homepage.png?raw=true)

### Screenshot of patient details page
!["Screenshot of patient details page"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/carepulse-details-page.png?raw=true)

### Screenshot of patient appointment booking request
!["Screenshot of patient appointment booking request"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/new-apt-request.png?raw=true)

### Screenshot of successful request submission
!["Screenshot of successful request submission"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/request-submission.png?raw=true)

### Screenshot of admin panel access password modal
!["Screenshot of admin panel access password modal"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/admin-panel-access-token.png?raw=true)

### Screenshot of admin panel page
!["Screenshot of admin panel page"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/admin-panel-home.png?raw=true)

### Screenshot of appointment manager modal
!["Screenshot of appointment manager modal"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/appointment-manager.png?raw=true)

### Screenshot of Sentry example for error logging
!["Screenshot of Sentry example for error logging"](https://github.com/will-frankland/care-pulse/blob/main/public/screenshots/sentry-example-video.png?raw=true)


# Getting Started

## Available Scripts

In the project directory, you can run:

### `npm  i`
### `npm  run dev`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\