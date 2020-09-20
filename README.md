[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]


<br />
<p align="center">
  <a href="https://github.com/eunai/commits-widget-darkmode">
<img src="./images/darkMode.svg" alt="dark mode icon">
  </a>
  </p>

  <h3 align="center">Dark Mode for TylerLH's Latest Commits Widget</h3>

  <h4 align="center">Fork of TylerLH's Latest Commits Widget</h4>

  <p align="center">Modified CSS file to change the colors to a material design dark mode and disable scrollbar (and keep functionality).</p>

## About

[![Product Name Screen Shot][product-screenshot]](https://eunai.github.io/commits-widget-darkmode/)

Show the latest commit activity on your repo, keeping the community updated and giving users more incentive to contribute to your project with this widget.

Check out a demo of the widget in action @ [Sample](https://eunai.github.io/commits-widget-darkmode/sample?username=eunai&repo=commits-widget-darkmode&limit=30)

Forked from [TylerLH's master branch](https://github.com/tylerlh/github-latest-commits-widget/)

<!-- TO DO LIST -->
Tasks
-----
- [x] ~~Material Design Dark Mode~~
- [ ] Adaptable Width and/or Height
- [ ] Add a toggle for light and dark mode?

<!-- USAGE -->
Usage
-----

This widget is hosted via GitHub Pages, meaning all you need to do is include an iframe in your html and you're good to go. There are 4 params at the moment: `USERNAME`, `REPO`, `BRANCH`, and `LIMIT`.

``` html
<iframe src="https://eunai.github.io/commits-widget-darkmode/?username=USERNAME&repo=REPO&limit=LIMIT"
  allowtransparency="true" frameborder="0" scrolling="no" width="502px" height="252px"></iframe>
```


<!-- PARAMETERS -->
## Parameters
`USERNAME`<br>
GitHub username that owns the repo (required)<br>

`REPO`<br>
GitHub repository to check for activity (required)

`BRANCH`<br>
Branch to pull commits from (default: master)

`LIMIT`<br>
The maximum number of results to list (default: 10)

<!-- NOTICE -->
Things to Note
-----------

+ Width and height are hardcoded. Be sure to specify the default values (500x250) in your iframe and overload those values in the css if you want to change them.

+ The widget currently depends on jquery and jquery.timeago at the moment.

<!-- LICENSE -->
## Copyright & License

Distributed under the Apache License, Version 2.0. See `LICENSE.txt` for more information.


Copyright 2012-2015 Tyler Hughes.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.



<!-- CONTACT -->
## Contact

Francis - [@retiredbarista](https://twitter.com/retiredbarista) - [GitHub](http://github.com/eunai)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* **Tyler Hughes** (Author) [@iampbt](https://twitter.com/iabpt) - [GitHub](http://github.com/tylerlh)
* [MaterialDesign.io (Dark Mode)](https://material.io/design/color/dark-theme)
* [W3Schools](https://www.w3schools.com/)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/eunai/commits-widget-darkmode.svg?style=flat-square
[contributors-url]: https://github.com/eunai/commits-widget-darkmode/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/eunai/commits-widget-darkmode.svg?style=flat-square
[forks-url]: https://github.com/eunai/commits-widget-darkmode/network/members
[stars-shield]: https://img.shields.io/github/stars/eunai/commits-widget-darkmode.svg?style=flat-square
[stars-url]: https://github.com/eunai/commits-widget-darkmode/stargazers
[issues-shield]: https://img.shields.io/github/issues/eunai/commits-widget-darkmode.svg?style=flat-square
[issues-url]: https://github.com/eunai/commits-widget-darkmode/issues
[license-shield]: https://img.shields.io/github/license/eunai/commits-widget-darkmode.svg?style=flat-square
[license-url]: https://github.com/eunai/commits-widget-darkmode/blob/master/LICENSE.txt
[product-screenshot]: https://puu.sh/GusJ9.png
