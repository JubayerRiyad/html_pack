# html_pack 
This is HTML Quick-Start Pack For Start A New Project. 


# js-keycodes-demo
👋 Hey there! Get to know all about the key events just with a key stroke.
# 🚀 Live demo
The app is deployed using Vercel and Netlify. You can play around with it from here,
- [https://js-keyevents-demo.vercel.app/](https://js-keyevents-demo.vercel.app/)
- [https://keyevents.netlify.app/](https://keyevents.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/246b2856-19c2-4886-b2e3-81417556e204/deploy-status)](https://app.netlify.com/sites/keyevents/deploys)

Optionally, you can also play around with it from here, [https://stackblitz.com/edit/js-keycodes?file=index.js](https://stackblitz.com/edit/js-keycodes?file=index.js)
# 👍 Want to Motivate? 
Thanks for your time to reading this. Feel free to clone/fork/improve. Who doesn't want motivations? Give the project a star(⭐) if you liked the work.

## Many Thanks to all the `Stargazers` who has supported this project with stars(⭐)

[![Stargazers repo roster for @atapas/js-keyevents-demo](https://reporoster.com/stars/atapas/js-keyevents-demo)](https://github.com/atapas/js-keyevents-demo/stargazers)


# 🖮 A List of Key Codes
[Click Here](./KEYCODE.md) to see the list of key codes.

# 🏃🏿‍♂️ How to run the project locally?
- Clone the project to a local directory.
- Browse to the project folder, `js-keyevents-demo`.
- Use the `npx serve` command to run the server.
- Now you can access the app @ [http://localhost:5000](http://localhost:5000)

> Note: You must have `Node.js` v12.x or higher installed. Optionally, you can also deploy this app to any other web/app servers like `tomcat`, `express`, etc. and run.





# 🖮 Key Code List

- `event.which` is legacy(or outdated)
- The `event.code` value is same for small letters(a) and capital letters(A). Hoever the `event.key` value represents the actual letter.
- The `event.which` value is different in Firefox(FF) and any other browsers for the keys, `equal(=)`, `semicolon(;)`, and `dash/minus(-)`

| Key Name    | event.which | event.key | event.code | Notes 
|-------------|---------------------|-----------|------------|------|
| backspace   | 8                   | Backspace | Backspace |
| tab         | 9                   | Tab       | Tab |
| enter       | 13                  | Enter     | Enter |
| shift(left) | 16                  | Shift     | ShiftLeft | `event.shiftKey` is true |
| shift(right)| 16                  | Shift     | ShiftRight | `event.shiftKey` is true |
| ctrl(left)  | 17                  | Control   | ControlLeft | `event.ctrlKey` is true |
| ctrl(right) | 17                  | Control   | ControlRight | `event.ctrlKey` is true |
| alt(left)   | 18                  | Alt       | AltLeft | `event.altKey` is true |
| alt(right)  | 18                  | Alt       | AltRight | `event.altKey` is true |
| pause/break | 19                  | Pause     | Pause |
| caps lock   | 20                  | CapsLock  | CapsLock |
| escape      | 27                  | Escape    | Escape |
| space       | 32                  |           | Space   | The `event.key` value is a single space.
| page up     | 33                  | PageUp    | PageUp |
| page down   | 34                  | PageDown  | PageDown |
| end         | 35                  | End       | End |
| home        | 36                  | Home      | Home |
| left arrow  | 37                  | ArrowLeft | ArrowLeft |
| up arrow    | 38                  | ArrowUp   | ArrowUp |
| right arrow | 39                  | ArrowRight | ArrowRight |
| down arrow  | 40                  | ArrowDown  | ArrowDown |
| print screen| 44                  | PrintScreen  | PrintScreen |
| insert      | 45                  | Insert    | Insert |
| delete      | 46                  | Delete    | Delete |
| 0 | 48 | 0 | Digit0 | 
| 1 | 49 | 1 | Digit1 |
| 2 | 50 | 2 | Digit2 |
| 3 | 51 | 3 | Digit3 |
| 4 | 52 | 4 | Digit4 |
| 5 | 53 | 5 | Digit5 |
| 6 | 54 | 6 | Digit6 |
| 7 | 55 | 7 | Digit7 |
| 8 | 56 | 8 | Digit8 |
| 9 | 57 | 9 | Digit9 |
| a | 65 | a | KeyA |
| b | 66 | b | KeyB |
| c | 67 | c | KeyC |
| d | 68 | d | KeyD |
| e                | 69  | e | KeyE |
| f                | 70  | f |KeyF |
| g                | 71  | g | KeyG |
| h                | 72  | h | KeyH |
| i                | 73  | i | KeyI |
| j                | 74  | j | KeyJ |
| k                | 75  | k | KeyK |
| l                | 76  | l | KeyL |
| m                | 77  | m | KeyM |
| n                | 78  | n | KeyN |
| o                | 79  | o | KeyO |
| p                | 80  | p | KeyP |
| q                | 81  | q | KeyQ |
| r                | 82  | r | KeyR |
| s                | 83  | s | KeyS |
| t                | 84  | t | KeyT |
| u                | 85  | u | KeyU |
| v                | 86  | v | KeyV |
| w                | 87  | w | KeyW |
| x                | 88  | x | KeyX |
| y                | 89  | y | KeyY |
| z                | 90  | z | KeyZ |
| left window key  | 91  | Meta | MetaLeft | `event.metaKey` is true |
| right window key | 92  | Meta | MetaRight | `event.metaKey` is true |
| select key (Context Menu) | 93 | ContextMenu | ContextMenu |
| numpad 0         | 96  | 0 | Numpad0 |
| numpad 1         | 97  | 1 | Numpad1 |
| numpad 2         | 98  | 2 | Numpad2 |
| numpad 3         | 99  | 3 | Numpad3 |
| numpad 4         | 100 | 4 | Numpad4 |
| numpad 5         | 101 | 5 | Numpad5 |
| numpad 6         | 102 | 6 | Numpad6 |
| numpad 7         | 103 | 7 | Numpad7 |
| numpad 8      | 104 | 8 | Numpad8 |
| numpad 9      | 105 | 9 | Numpad9 |
| multiply      | 106 | * | NumpadMultiply |
| add           | 107 | + | NumpadAdd |
| subtract      | 109 | - | NumpadSubtract |
| decimal point | 110 | . | NumpadDecimal |
| divide        | 111 | / | NumpadDivide |
| f1            | 112 | F1 | F1 |
| f2            | 113 | F2 | F2 |
| f3            | 114 | F3 | F3 |
| f4            | 115 | F4 | F4 |
| f5            | 116 | F5 | F5 |
| f6            | 117 | F6 | F6 |
| f7            | 118 | F7 | F7 |
| f8            | 119 | F8 | F8 |
| f9            | 120 | F9 | F9 |
| f10           | 121 | F10 | F10 |
| f11           | 122 | F11 | F11 |
| f12           | 123 | F12 | F12 |
| num lock      | 144 | NumLock | NumLock |
| scroll lock   | 145 | ScrollLock | ScrollLock |
| audio volume mute   | 173 | AudioVolumeMute |  | ⚠️ The `event.which` value is 181 in Firefox. Also FF provides the code value as, `VolumeMute` |
| audio volume down   | 174 | AudioVolumeDown |  | ⚠️ The `event.which` value is 182 in Firefox. Also FF provides the code value as, `VolumeDown` |
| audio volume up   | 175 | AudioVolumeUp |  | ⚠️ The `event.which` value is 183 in Firefox. Also FF provides the code value as, `VolumeUp` |
| media player   | 181 | LaunchMediaPlayer |  | ⚠️ The ️`event.which` value is 0(no value) in Firefox. Also FF provides the code value as, `MediaSelect` |
| launch application 1 | 182 | LaunchApplication1 |  | ⚠️ The ️`event.which` value is 0(no value) in Firefox. Also FF provides the code value as, `LaunchApp1` |
| launch application 2 | 183 | LaunchApplication2 | | ⚠️ The ️`event.which` value is 0(no value) in Firefox. Also FF provides the code value as, `LaunchApp2` |
| semi-colon    | 186 | ; | Semicolon | ⚠️ The `event.which` value is 59 in Firefox |
| equal sign    | 187 | = | Equal | ⚠️ The `event.which` value is 61 in Firefox |
| comma         | 188 | , | Comma |
| dash          | 189 | - | Minus | ⚠️ The `event.which` value is 173 in Firefox |
| period        | 190 | . | Period |
| forward slash | 191 | / | Slash |
| Backquote/Grave accent  | 192 | ` | Backquote |
| open bracket  | 219 | [ | BracketLeft |
| back slash    | 220 | \ | Backslash |
| close bracket | 221 | ] | BracketRight |
| single quote  | 222 | ' | Quote |







