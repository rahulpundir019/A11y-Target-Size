# Target Size (Minimum) (Level AA) Checker(Web)
To detect [WCAG 2.5.5 Target Size (AA)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html) bugs automatically I have created this [A11y Target Size(AA)](https://cdpn.io/pen/debug/abXggVw?authentication_hash=DqADdepmNLGA) bookmarklet. It will minimize the manual effort of all Accessibility testers out there🙂. 

### Limitations:
1. V1 and V2 might not work on certain type of UI like dialogs and iframes etc so use 24px Cursor in those cases.
2. This tool do not check Target Size (Minimum) last 4 Exceptions so you need to manually test those.

### Credits:
1. I have modified code of [Target Size](https://github.com/stevefaulkner/targetsize) created by [Steve Faulkner](https://github.com/stevefaulkner) which is good to test Target size so check it out but because it does not work on some places(like dialogs) and as a tester I found its testing UX not efficient and as I also want to see whole clickable/target area so that I can also identify overlapping cases clearly while going through websites so created mine accordingly.
2. For 24px Cursor, I have modified the code created by [Adrian Roselli](https://adrianroselli.com/2022/05/24x24-pixel-cursor-bookmarklet.html)
3. ChatGPT

