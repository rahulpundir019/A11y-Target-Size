# Target Size (Minimum) (Level AA) Checker(Web)
To detect [WCAG 2.5.5 Target Size (AA)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html) bugs automatically I have created this [A11y Target Size(AA)](https://cdpn.io/pen/debug/abXggVw?authentication_hash=DqADdepmNLGA) bookmarklet. It will minimize the manual effort of all Accessibility testers out there🙂. 

I have used ChatGPT to generate used code and then did some manual debugging to edit the code based on my requirements and also tested it out on many websites.

### Limitations:
1. It might not work on every type of websites and on iframes.
2. This tool do not check Target Size (Minimum) Exceptions.

### Credits:
1. I have used [Target Size](https://github.com/stevefaulkner/targetsize) created by [Steve Faulkner](https://github.com/stevefaulkner) which is good to test Target size so check it out but because it does not work on some places(like dialogs) and as a tester I found its testing UX not efficient and as I also want to see whole clickable/target area so that I can also identify overlapping cases clearly while going through websites so created mine accordingly.
2. For 24px Cursor, I have modified the code created by [Adrian Roselli](https://adrianroselli.com/2022/05/24x24-pixel-cursor-bookmarklet.html)

