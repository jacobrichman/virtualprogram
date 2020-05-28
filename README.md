# VirtualProgram.org

[![YouTube](http://img.youtube.com/vi/GwQKJ5R8llg/0.jpg)](https://www.youtube.com/watch?v=GwQKJ5R8llg "Play Video")

DEMO: [virtualprogram.org](https://virtualprogram.org/)

## Inspiration
If you’ve ever been to a convention or conference, you know exactly this feeling. You’re sitting in the middle of a 20,000 seat convention center, the intro music ends, a video plays on the 100 foot screens and then the keynote speaker walks on to the stage. These experiences are memorable because it's exhilarating to be with like-minded people discussing something they’re passionate about.

Unfortunately, with COVID-19 these were one of the first venues to close their operations. Since then we’ve all begun transitioning to virtual content through platforms like zoom and facebook live. Yet, in the three months since, no one has truly tried to replicate that full experience and bring the conference to the home.

## What it does
Never again feel like your front row seat at the conference has been downgraded to merely 25 people in gallery view on zoom. Thanks to virtualprogram.org the gap between video conferencing platforms and truly virtual programs will finally be bridged.

With virtualprogram.org, you virtually walk into the convention center along with thousands of others as music plays and slides are displayed on the screen, The VIPs are seated prominently in the front, and the screen gets dark when the speaker begins.

This solution has potential to be used for events ranging from graduations, religious ceremonies, galas, concerts and so much more. Any program that originally required a stage and audience can be fully virtualized using this product.


## How I built it
As a proof of concept, I built a web app which has two components.

First, it uses YouTube to either display a live stream or a video premiere. This way the show itself is given priority over the bandwidth and it also incorporates a slight delay in order to ensure high definition quality of the stream.

The second part uses Jitsi (an open source video conferencing platform) to create a private room for the event. All participants can see each other as well as the youtube stream.

There are also some other tweaks which make it feel like a conference such as branding, animations and dimming of lights by darkening the UI.

## Challenges I ran into
It's clear that it takes quite a long time to fully develop a video conferencing platform that's even remotely comparable to Zoom or Google meet. Therefore, this site uses a lot of CPU in order to have more than 10 people on the call. In production this would not be a viable solution.

It would probably be best to develop a custom solution. Given that everyone in the audience is muted and that resolution or FPS isn't much of a priority, a custom solution would be able to handle hundreds and maybe even thousands of people. I had also hoped to add a VIP section, but this would also require a custom solution

## Accomplishments that I'm proud of
The prototype I built is capable of being used right away and could be a very useful platform for virtual events. This project has potential to be used for so many types of events. I am looking forward to sharing with others to enhance the virtual experience.

## What I learned
Before working on this project I had never worked with video conferencing technology, and I learned a lot about how it works and all the detail required to make all of our calls look so smooth.

## What's next for virtualprogram.org
The next steps for this project would be to conduct more market research to narrow down the target market and to find out more precisely what the needs are of those who would use it. Depending on how well this proof of concept performs, I may also begin working on a custom video conference solution for this product as described above.
