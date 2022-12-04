# HORISEON landing page: code refactor
![img](screenshot.JPG)

## Motivation
Refactoring existing code without actually changing what it does is a large part of what web development teams do. New technology, refining drafts of code, or fulfilling newly implemented standards are a few reasons why it is such a common problem. There is always work to be done on good applications. This is the reason why there are constant updates for apps and the reason why it's best to keep apps on auto-update. Hinging on this fact is the challenge, HORISEON landing page: code refactor.

## Challenges faced
There were a few bumps along the way in completing this challenge. figuring out what semantic elements were appropriate in place of non-semantic elements. Keeping an organized consistent framework with comments to aid in the future maintenance of the code. Maintaining the function of the HTML framework, following the changes to the elements, and the consolidation of the CSS selectors and declarations.

## lessons learned
Commenting out lines of code and having a live preview of the changes allowed me to get a grasp of what is and isn't allowed. I found that the most appropriate semantic elements worked in replacement, but I kept to some of the standard code when it was found that the consolidation under broader selectors broke the layout of the page. This was mostly encountered in the header element. There was little commonality between the header declarations. I did my best and reduced redundancy but in the end, I left it to the comment structure to help guide the coder. The most evident and successful cases that I encountered under consolidation were different selectors with shared declarations under a shared parent element. Consolidating those was a matter of grouping the class and removing the repetitive declarations.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2022 kcavner

---
