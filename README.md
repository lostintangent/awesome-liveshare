# <img src="https://ms-vsliveshare.gallerycdn.vsassets.io/extensions/ms-vsliveshare/vsliveshare-pack/0.2.12/1554959297207/Microsoft.VisualStudio.Services.Icons.Default" width="25px" /> Awesome Live Share
<img src="https://awesome.re/badge.svg" alt="Awesome">

A curated list of awesome [Visual Studio Live Share](https://aka.ms/vsls) articles, editor extensions and more. Inspired by other [awesome lists](https://github.com/sindresorhus/awesome-nodejs) and meant to provide visibility to resources that can help make your real-time collaborative development experience even better! If you notice something missing below, that would benefit the community, please feel free to submit a PR or reach out to [@lostintangent](http://twitter.com/lostintangent) on Twitter 👋

<a href="https://aka.ms/vsls-zelda"><img src="https://aka.ms/vsls-zelda" width="500px" /></a>

# Contents

- [Editor Extensions](#extensions)
    - [Visual Studio Code](#visual-studio-code)
        - [Chat / Communication](#chat--communication)
        - [Miscellaneous](#miscellaneous)
        - [Testing](#testing)
        - [Time Tracking / Management](#time-tracking--management)
        - [Version Control](#version-control)
        - [Web Development](#web-development)
    - [Visual Studio](#visual-studio)
        - [Integrated Chat](#integrated-chat)
        - [Diagnostics](#diagnostics)
- [Resources](#resources)
    - [Articles](#articles)
    - [Documentation](#documentation) 
    - [Extensibility SDKS](#exensibility-sdks)

## Editor Extensions

While Visual Studio Live Share provides a rich collaborative experience out-of-the-box (e.g. editing, debugging, terminals, localhost servers), it's also fully [extensible](#exensibility-sdks), which enables 3<sup>rd</sup> party extensions to augment it in new and interesting ways. Check out the following extensions in order to up-level your Live Share collaboration sessions:

### Visual Studio Code

#### Chat / Communication

- [CodeStream](https://marketplace.visualstudio.com/items?itemName=CodeStream.codestream) - Provides an integrated chat and rich commenting system, that includes the ability to easily spin up Live Share sessions from a chat thread.
- [Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) - Allows other Discord users to easily spectate and/or join your active Live Share sessions ([example](https://twitter.com/LostInTangent/status/1070566201078640640)).
- [Live Share Audio](https://aka.ms/vsls-audio) - Provides integrated audio calling for Live Share sessions, without needing to use a seperate service ([example](https://twitter.com/lostintangent/status/1075155769870307329)).
- [Team Chat](https://marketplace.visualstudio.com/items?itemName=karigari.chat) - Provides integrated text chat for Live Share sessions, without needing to use a seperate service ([example](https://twitter.com/lostintangent/status/1075155769870307329)).

#### Miscellaneous

- [Live Share Whiteboard](https://aka.ms/vsls-whiteboard) - Provides a real-time, collaborative whiteboard to Live Share sessions ([example](https://twitter.com/lostintangent/status/1079846355290415104)).
- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode) - A live JavaScript scratchpad, that can be collaboratively edited by everyone in a Live Share session ([example](https://twitter.com/wallabyjs/status/1050188666889428992)).

#### Testing

- [Test Explorer](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer-liveshare) - Provides a shared test runner, where the results of test runs are viewable in real-time.

#### Time Tracking / Management

- [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode) - Automatically track how you spend your time coding, including the time spent in Live Share sessions ([example](https://twitter.com/brettmstevens/status/1103809321702313984)).
- [Live Share Pomodoro](https://marketplace.visualstudio.com/items?itemName=lostintangent.vsls-pomodoro) - Provides a shared Pomodoro timer for everyone in the Live Share session, which can help add some structure to your pairing workflow ([example](https://twitter.com/lostintangent/status/1115847842453762049)).
- [Waka Time](https://wakatime.com/vs-code) - The open source plugin for productivity metrics, goals, leaderboards, and automatic time tracking.

#### Version Control

- [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) - Allows you to review a PR in real-time with other developers ([example](https://twitter.com/lostintangent/status/1093950344239837184)).
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Enables guests within a Live Share session to view inline Git blame info as well as rich commit history. This is one of the most valuable VS Code extensions in the marketplace, and it's also fully collaborative! ([example](https://twitter.com/LostInTangent/status/1085919402954874883)).

#### Web Development

- [Browser Preview](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview) - Allows participants within a Live Share session to browse the same pages together, which can be particularly using for debugging a web app, or viewing documentation ([example](https://twitter.com/auchenberg/status/1116362646784102400)).
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - Allows you to easily spin up a local web server for static HTML files. When in a Live Share session, the local servers are automatically shared with guests, so that everyone can work on it together, without needing to manually share the underlying port ([example](https://twitter.com/LostInTangent/status/1063445225140568065)).

### Visual Studio

#### Integrated Chat

- [CodeStream](https://marketplace.visualstudio.com/items?itemName=CodeStream.codestream-vs) - Provides an integrated chat and rich commenting system, that includes the ability to spin up Live Share sessions.

#### Diagnostics

- [OzCode](https://marketplace.visualstudio.com/items?itemName=CodeValueLtd.OzCode) - Provides awesome debugging enhancements, including a fully collaborative time-travel debugger.

## Resources

Check out the following resources in order to learn how to get the most out of Visual Studio Live Share, understand how others are using it, and (hopefully!) answer any questions you may have:

### Articles

- [In Pursuit of Enjoyable Developer Collaboration](https://aka.ms/vsls-why) - Describes why Live Share was built, and the key reasons that make it a unique product for developer collaboration.
- [Collaboration Doesn't Come in "One Size Fits All"](https://dev.to/lostintangent/collaboration-doesn-t-come-in-one-size-fits-all-33ai) - Describes the multi-modality experience that Live Share enables for collaboration (e.g. focusing on the same thing, working independently).
- [Localhost Isn't Local Anymore](https://dev.to/lostintangent/localhost-isnt-local-anymore-2ib6) - Goes into detail about the ability to share localhost servers as part of a Live Share session.
- [Collaborative Development Requires a Shared Browser](https://dev.to/lostintangent/collaborative-browsing-within-visual-studio-code-4h92) - Illustrates how to collaboratively browse web pages via the Browser Preview extension.
- [Visual Studio Live Share Can Do That?](https://www.smashingmagazine.com/2018/09/visual-studio-live/) - Highlights some of the more compelling features of Live Share along with some pro-tips.

### Documentation

- [Visual Studio "How to"](https://docs.microsoft.com/en-us/visualstudio/liveshare/use/vs) - Provides a quick start for using Live Share in Visual Studio.
- [Visual Studio Code "How to"](https://docs.microsoft.com/en-us/visualstudio/liveshare/use/vscode) - Provides a quick start for using Live Share in Visual Studio Code.
- [Security Considerations](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/security) - Discusses the various mechanisms that Live Share provides in order to collaborate securely.
- [Connectivity Requirements](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/connectivity) - Explains the requirements for deploying Live Share within your organization's network.
- [Common Use Cases](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/use-cases) - Outlines the diverse set of ways that developers are using Live Share today (e.g. pair programming, mentoring, interactive brown bags).

### Extensibility SDKS

- [Visual Studio](https://www.nuget.org/packages/Microsoft.VisualStudio.LiveShare/) - NuGet package for adding Live Share integration to your Visual Studio extension.
- [Visual Studio Code](https://npmjs.com/vsls) - NPM package for adding Live Share integration to your Visual Studio Code extension.
