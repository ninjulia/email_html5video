# Email with Embedded Video

Starter file for responsive email featuring an embedded video via HTML5 player. While the majority of email clients still do not support playing video directly from your inbox, both Apple Mail and the native Samsung email client do - and both represent a large segment of the email client market. To cover all email clients, however, fall-back code is added providing alternative content. Here, an animated gif fall-back indicated a user should click through to see the video using their browser. To get started, I followed the Email on Acid guide [How to Embed HTML5 Video in Emails | And Your Other Options](https://www.emailonacid.com/blog/article/email-development/a_how_to_guide_to_embedding_html5_video_in_email/).

I created the design for this email as part of a larger eLearning series for IT Software-as-a-Service company. You can read more about the project on [my design portfolio site](https://www.becausejulia.com/design/elearning/) Here, I've replaced the copy and edited the video to remove any proprietary information / logos.

The email showcased here was coded from scratch utilizing my email boilerplate framework (developed from Email on Acid and Litmus.com samples as a starting point). Email on Acid Tests passing in 44 popular mobile, web, and desktop email clients/devices as of August, 2021. All copyrights and trademarks remain property of their respective owners.

## Expected Results

Users should be able to:

_On Email Clients that Support HTML5 Video (iOS, Apple Mail, Samsung Mail, and Thunderbird)_

- View a **HERO IMAGE** video with HTML5 video standard controls within the email client

_On Email Clients that **DO NOT** Support HTML5 Video, but **DO** support animated GIF (Majority of email clients)_

- View a linked animated **HERO IMAGE** based on a video still featuring a false "play" button
- **HERO IMAGE** is linked to the hosted video

_On Email Clients that **DO NOT** Support HTML5 Video nor animated GIFs (Outlook 2007-2017)_

- View a linked **HERO IMAGE** with **CTA** for to hosted video

_ALL CLIENTS_

- View a responsive layout depending on their device screen size & email client

## Email On Acid Test List

### Mobile

- Gmail App Pixel 2 (Android 9)
- Gmail App Pixel 3 (Android 10)
- Gmail App Pixel 4 (Android 11)

- iPhone11 (iOS 13)
- iPhone12 (iOS 13)
- iPhone13 (iOS 14)

### Desktop

- Apple Mail
- Outlook

### Web Clients

- Gmail (Chrome, Edge, FireFox)
- Office365 (Chrome, Edge, FireFox)
- Outlook.com (Chrome, Edge, FireFox)
- Yahoo (Chrome, Edge, FireFox)

## Screenshot

![screenshot](screenshot.png?raw=true)

## Links

- View Email: [https://ninjulia.github.io/email_html5video/](https://ninjulia.github.io/email_html5video/)

## Attributions:

Email designed and coded by Julia Czarnecki with a lot of help from [Litmus](https://www.litmus.com/blog/video-in-email/) and Email on Acid. Any and all copyrighted material is property of the copyright owners. Placeholder logo image provided by [placeholder.com](https://placeholder.com/logos/) used under [Creative Commons Licensing](https://creativecommons.org/).
