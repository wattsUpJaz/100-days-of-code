# 100 Days Of Code - Log

### Day 1: Wednesday - November 9, 2022

**Today's Progress**: Picked this back up again after falling off the bandwagon for a couple weeks because of getting sick and burnout. Discovered the most absurd missing feature in Premiere Pro. You can't select all video or audio transition to delete them. You have to do it by hand, or buy this addon. I am appalled. It's talked about [here](https://adobe-video.uservoice.com/forums/911233-premiere-pro/suggestions/43571349-select-transitions-for-multiple-clips-at-once#:~:text=1.,%2B%20ALT%20%2B%20drag%2C%20etc.) and [here](https://community.adobe.com/t5/premiere-pro-discussions/how-to-remove-all-transitions/td-p/1631643/page/2).

### Day 1 (again): Wednesday - November 30, 2022

**Today's Progress**:

Re-learned how to set up localhost web server using npm's `http-server` command. Learned how to access my computer's localhost on my phone. You just go to `System Preferences > Sharing > Internet Sharing` to find the address of your computer's local network, and then just type that into your phone's browser with the port your hosting at.

Opted out of the simple web server and used simple hot reloading web server with `npx parcel index.html` (parcel is like a simpler webpack). Found the info in [this super useful article on fullstack live reloading](https://blog.logrocket.com/complete-guide-full-stack-live-reload/).

Updated and re-learned `npx create-react-app [appName]` and learned about `react-helmet-async` ([article here](https://designcode.io/react-hooks-handbook-seo-and-metadata)) for adding metadata to react apps. Also remembered how to create a git repo with `git init`

Read a bit of [an article](https://overreacted.io/npm-audit-broken-by-design/) by the creator of `create-react-app` on how `npm audit` is broken and the 6 high sev warning can be ignored.

Learned a little bit about the Apache V2 Licensing [here](https://fossa.com/blog/open-source-licenses-101-apache-license-2-0/). If this POC ends up working I'll need to come back and do this.

Started to manually refactor [this AR example](https://immersive-web.github.io/webxr-samples/immersive-ar-session.html) into React, because it's the only WebXR AR example that worked with XRViewer (ios doesn't support WebXR still, so you need to use a workaround browser). But I realized this was stupid and found some react libraries from [this 2 year old article](https://blog.dubenko.dev/react-xr/) that are promising.

Learned that apparently Godot has WebXR support, but it needs to be in an app form i think.

### Day 2: Thursday - December 1, 2022

**Today's Progress**: Learned how to set up a python devlopment project for Advent of Code.

1. Command Palette (`Shift+Cmd+P`) > Python: Create Environment > Venv
2. Run `pip install copier`
3. Run `$ copier gh:gahjelle/template-aoc-python ./`
4. Command Palette > Python: Configure Tests > PyTest
5. Run `pip install advent-of-code-data`. This is a library for automatically getting your personal input for each puzzle.
6. Follow [this guide](https://github.com/wimglenn/advent-of-code-wim/issues/1) to get your AOC (Advent of Code) session.
7. Save your session as an environment variable `export AOC_SESSION=[your session ID]`

Learned about CoPilot and chatGPT a little. They're AI coding assistants that kinna make solving coding challenges stupid easy, or just solve it all for you.

Found [this site](https://webxr-ios.webxrexperiments.com/splash.html) that might be a good lead for AR stuff (repos [here](https://github.com/MozillaReality/webxr-ios-js/network/members))

Looked into Godot's WebXR support more. Found [this](https://www.youtube.com/watch?v=UMKvSxUpsHA) interesting video. Learned that [Meta has dumped a lot of money into Godot](https://mixed-news.com/en/meta-invests-in-open-source-engine-godot-for-what-reason/), maybe for its XR potential?

[Babylon.js](https://doc.babylonjs.com/journey/theFirstStep) may be a good alternative?

### Day 3: Friday - December 2, 2022

**Today's Progress**: Learned about Chrome tab groups and how to save them ([article here](https://www.theverge.com/23384844/chrome-google-tab-groups-create-save-how-to)).

Enrolled and then unenrolled in a web development Harvard course. Almost enrolled in a couple three.js courses

Found [Nerd Forge](https://www.youtube.com/@Nerdforge) on YT and wasted some time...

Resources found:

- [daisy ui](https://daisyui.com/) - tailwind components
- [prisma](https://www.prisma.io/) - node.js / typescript ORM
- [planetscale](https://planetscale.com/) - serverless MySql db
- [cypress](https://www.cypress.io/) - full js testing framework

Discovered Chrome's [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) dev tool for checking website quality.

Decided to write a book.

Did Advent of Code day 3

**Thoughts**:

Today's been an emotional one. I changed gears a lot. I came up with five different ideas for moving forward, and I was 100% convinced of them all at some point during the day. Jared and I went on a long walk, and he really helped me see things a little more clearly. He is such a lovely, kind, thoughful, insightful human. I am super lucky to be his partner in all this madness.

I finished The Subtle Art again today and it inspired me to try reorienting myself around some good values and goals. I went back over the exercise I did back in September after reading Get Smart and that helped a lot. I think trying my hand at entrepreneurial stuff is really important to me, even if I fail miserably at it. It just resonates super deep with me and I feel like if I could get past some of these barriers I'm hitting, I could maybe even like it. I'm in my own way so bad though. I'm like a dog with squirrels. I get distracted so easily. And I feel burned out on code.

After talking with Jared and explaining all the ideas I had, he said to roll with the book idea 100%. I cried. He's awesome. End of story. So I think this is gonna turn into a 100 days of log stuff type of thing, because I'm not sure how much coding I'll be doing. I do want to keep up on the Advent of Code, so I guess that'll count. I want to keep updates going here though, because it really helps me. A lot. My brain capacity is that of a goldfish, and trying to hold onto things or process all I did is exhausting and usually unsuccessful.

Also, how the heck do you turn on spell check for markdown.
