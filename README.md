# <img src="https://ms-vsliveshare.gallerycdn.vsassets.io/extensions/ms-vsliveshare/vsliveshare-pack/0.2.12/1554959297207/Microsoft.VisualStudio.Services.Icons.Default" width="25px" /> Awesome Live Share
<img src="https://awesome.re/badge.svg" alt="Awesome">

A curated list of awesome [Visual Studio Live Share](https://aka.ms/vsls) articles, editor extensions and more. Inspired by other awesome lists, and meant to provide visibility to resources that can help make your collaborative development experience even better! If you notice something missing below, that would benefit the community, please feel free to submit a PR 👍

<a href="https://aka.ms/vsls-zelda"><img src="https://aka.ms/vsls-zelda" width="300px" /></a>

## Contents

- [Extensions](#extensions)
    - [Visual Studio Code](#visual-studio-code)
        - [Chat / Communication](#chat---communication)
        - [Miscellaneous](#miscellaneous)
        - [Testing](#testing)
        - [Time Tracking / Management](#time-tracking---management)
        - [Version Control](#version-control)
        - [Web Development](#web-development)
    - [Visual Studio](#visual-studio)
        - [Integrated Chat](#integrated-chat)
        - [Diagnostics](#diagnostics)
- [Resources](#resources)
    - [Documentation](#documentation)
    - [Articles](#articles)
    - [Extensibility SDKS](#exensibility-sdks)

### Extensions

While Visual Studio Live Share provides a rich collaborative experience out-of-the-box (e.g. editing, debugging, terminals, localhost servers), it's also fully [extensible](#exensibility-sdks), which enables 3<sup>rd</sup> party extensions to augment it in new and interesting ways. Check out the following extensions in order to uplevel your Live Share collaborion sessions:

#### Visual Studio Code

##### Chat / Communication

- [CodeStream](https://marketplace.visualstudio.com/items?itemName=CodeStream.codestream) - Provides an integrated chat and rich commenting system, that includes the ability to spin up Live Share sessions.

- [Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) - Allows other Discord users to easily spectate and/or join your active Live Share sessions

- [Live Share Audio](https://aka.ms/vsls-audio) - Provides integrated audio calling for Live Share sessions, without needing to use a seperate service.

- [Team Chat](https://marketplace.visualstudio.com/items?itemName=karigari.chat) - Provides integrated text chat for Live Share sessions, without needing to use a seperate service. 

##### Miscellaneous

- [Live Share Whiteboard](https://aka.ms/vsls-whiteboard) - Provides a real-time, collaborative whiteboard to Live Share sessions

- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode) - A live JavaScript scratchpad, that can be collaboratively edited by everyone in a Live Share session.

##### Testing

- [Test Explorer](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer-liveshare) - Provides a shared test runner, where the results of test runs are viewable in real-time

##### Time Tracking / Management

- [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode) - Automatically track how you spend your time coding, including the time spent in Live Share sessions.

- [Live Share Pomodoro](https://aka.ms/vsls-pomodoro) - Provides a shared Pomodor timer for everyone in the Live Share session

##### Version Control

- [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) - Allows you to review a PR in real-time with other developers

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Enables guests within a Live Share session to view 

##### Web Development

- [Browser Preview](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview) - Allows you to open/debug/browse web pages within Visual Studio Code. When in a Live Share session, all participants can browse the same pages together, which can be particularly using for debugging a web app, or viewing documentation.

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - Allows you to easily spin up a local web server for static HTML files. When in a Live Share session, the local servers are automatically shared with guests, so that everyone can work on it together, without needing to manually share the underlying port.

#### Visual Studio

##### Integrated Chat

- [CodeStream](https://marketplace.visualstudio.com/items?itemName=CodeStream.codestream-vs) - Provides an integrated chat and rich commenting system, that includes the ability to spin up Live Share sessions.

##### Diagnostics

- [OzCode](https://marketplace.visualstudio.com/items?itemName=CodeValueLtd.OzCode) - Provides awesome debugging enhancements, including a fully collaborative time-travel debugger.

### Resources

#### Documentation

- [Visual Studio "How to"](https://docs.microsoft.com/en-us/visualstudio/liveshare/use/vs)
- [Visual Studio Code "How to"](https://docs.microsoft.com/en-us/visualstudio/liveshare/use/vscode)
- [Security Considerations](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/security)
- [Connectivity Requirements](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/connectivity)
- [Common Use Cases](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/use-cases)

#### Articles

- [In Pursuit of Enjoyable Developer Collaboration](https://aka.ms/vsls-why)
- [Collaboration Doesn't Come in "One Size Fits All"](https://dev.to/lostintangent/collaboration-doesn-t-come-in-one-size-fits-all-33ai)
- [Localhost Isn't Local Anymore](https://dev.to/lostintangent/localhost-isnt-local-anymore-2ib6)
- [Collaborative Development Requires a Shared Browser](https://dev.to/lostintangent/collaborative-browsing-within-visual-studio-code-4h92)

#### Extensibility SDKS

- [Visual Studio](https://www.nuget.org/packages/Microsoft.VisualStudio.LiveShare/)
- [Visual Studio Code](https://npmjs.com/vsls)