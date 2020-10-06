<p align="center">
  <img width="600" src="https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Logo/LogoWithText.png"><br>
</p>

<p align="center">
  <img width="50" src="https://raw.githubusercontent.com/aheze/DeveloperAssets/master/Plus.png">
</p>
   
<p align="center">
  <img src="https://hacktoberfest.digitalocean.com/assets/HF-full-logo-b05d5eb32b3f3ecc9b2240526104cf4da3187b8b61963dd9042fdc2536e4a76c.svg" align="center" width="400">
</p>

<h2 align="center">
  <strong>Add progress bars to gifs!</strong>
</h2>

<p align="center">
   <a href="#hacktoberfest"><strong>Hacktoberfest!</strong></a> |
  <a href="https://apps.apple.com/us/app/id1526969349"><strong>App Store Download</strong></a> |
  <a href="#about">About</a> |
  <a href="#features">Features</a> |
  <a href="#usage">Usage</a> |
  <a href="#contributing">Contributing</a> |
  <a href="#license">License</a>
  <br>
</p>

### Hacktoberfest
All contributions are welcome! Here are some issues to get started on:
- [ ] [Make dark mode look better](https://github.com/aheze/ProgressGif/issues/6)
- [ ] [Display Gif size when export finishes](https://github.com/aheze/ProgressGif/issues/5)
- [ ] [Add haptic feedback when export finishes](https://github.com/aheze/ProgressGif/issues/4)

Steps:
1. Fork the repo
2. Make your changes (just stick on the `main` branch)
3. Make a pull request
4. [Add yourself](https://github.com/aheze/ProgressGif/blob/3c1a062aca5a36c5af54f5975e44158daf2048c5/ProgressGif/About/Contributors.swift#L45) to the `Contributors` screen in the app!
```Swift
let aheze = Contributor()
aheze.name = "Zheng"
aheze.additions = "199,405"
aheze.deletions = "29,470"
aheze.profileName = "ahezeProfile" /// the image name inside Contributing.xcassets
aheze.linkImageName = "Medium"
if let profileURL = URL(string: "https://medium.com/@ahzzheng") {
    aheze.link = profileURL
}
contributors.append(aheze)

Don't forget to add your profile pic inside `Contributing.xcassets`!
```
<img src="https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/contributors.jpg" width="300">

If you have any questions, feel free to open an issue, or leave a comment somewhere!




### App Store Download
Download ProgressGif on the [App Store](https://apps.apple.com/us/app/id1526969349). Because it's open-source, it's free!

### About
**For the writers and bloggers out there**

Tutorials with only words are boring, so we add images. And if they need to be more detailed, we add video... but video isn't always the best choice.
- Readers may not want to turn on audio
- If they're on their phone, the video will open in a full-screen modal, which disrupts the reading experience
- Some blogging sites don't allow video embeds

That's why we use GIFs instead! (Yes, GIFs are memory-inefficient, but they're really convenient, and ProgressGif has options for framerate)

ProgressGif is an iOS app made with Swift 5 and UIKit, inspired by this [article](https://www.excelcampus.com/tips-shortcuts/add-progress-bar-to-gif/). SwiftUI would have be fine for building the UI, but because there's a lot of under-the-hood work with video rendering, I thought it would be better to just go with UIKit.

### Features
ProgressGif does one thing only: Add progress bars to GIFs.

| Example 1 | Example 2 | Example 3 | Example 4 | Example 5 | Example 6 |
| :-------------: |:-------------:| :-----:| :-----:| :-----:| :-----:|
| ![Example1] | ![Example2] | ![Example3] | ![Example4] | ![Example5] | ![Example6] |

Yeah, that's it. ProgressGif serves one purpose, and one purpose only... but in a highly customizable way! Customize height, bar color, bar background color, edge inset, corner radius… and shadows are in beta!

### Usage

| Step 1        | Step 2           | Step 3  |
| :-------------: |:-------------:| :-----:|
| Import video      | Add the bar | Export |
| ![Step1] | ![Step2] |![Step3] |

*GIFs generated by ProgressGif*

### Contributing
Once again, all contributions are welcome! Here's some harder issues that I need help on:
- [x] Horizontal layout
- [ ] Allow picking colors with transparency
- [ ] Allow picking opaque color for background (so that shadows show up)
- [ ] Export as MOV instead of just GIF only

*ProgressGif is inspired by this awesome [article](https://www.excelcampus.com/tips-shortcuts/add-progress-bar-to-gif/).*

[example1]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Examples/13A3607F-1BE9-4CB4-9642-3155EB44D1BE.gif
[example2]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Examples/4EFA4E62-E533-4244-A469-27B771878CCF.gif
[example3]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Examples/56CC30DC-21BE-4A28-81C0-EC310D0CF79F.gif
[example4]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Examples/9A57452A-4934-48A9-BEC5-0C1278402FE8.gif
[example5]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Examples/C5EBDFA4-C310-4942-9F11-1AC22F46F283.gif
[example6]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Examples/F327A3EF-D38C-42C9-82C3-7C5A7C0866AE.gif

[step1]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Usage/Step1.gif
[step2]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Usage/Step2.gif
[step3]: https://raw.githubusercontent.com/aheze/ProgressGif/main/Assets/GitHub/Usage/Step3.gif

### License
```
MIT License

Copyright (c) 2020 Zheng

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
