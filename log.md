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
