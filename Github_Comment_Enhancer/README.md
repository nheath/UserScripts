# [Github Comment Enhancer](https://github.com/jerone/UserScripts/tree/master/Github_Comment_Enhancer) <sup>(deprecated)</sup>

[![Install](https://raw.github.com/jerone/UserScripts/master/_resources/Install-button.png)](https://github.com/jerone/UserScripts/raw/master/Github_Comment_Enhancer/Github_Comment_Enhancer.user.js)
[![Source](https://raw.github.com/jerone/UserScripts/master/_resources/Source-button.png)](https://github.com/jerone/UserScripts/blob/master/Github_Comment_Enhancer/Github_Comment_Enhancer.user.js)
[![Donate](https://raw.github.com/jerone/UserScripts/master/_resources/Donate-button.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VCYMHWQ7ZMBKW)
[![Support](https://raw.github.com/jerone/UserScripts/master/_resources/Support-button.png)](https://github.com/jerone/UserScripts/issues)


## Notice

THIS USERSCRIPT IS SADLY DEPRECATED.

## Description

Add features to enhance comments & wiki & contact page on [Github](https://github.com) and comments on [Github Gist](https://gist.github.com).

You can reply to issues, pull requests and inline comments by pressing the reply button on every comment.

Every comment field also got a toolbar, consisting of the following buttons:
* Bold (<kbd>ctrl+b</kbd>)
* Italic (<kbd>ctrl+i</kbd>)
* Underline (<kbd>ctrl+u</kbd>)
* Strikethrough (<kbd>ctrl+s</kbd>)
* Headers
    * Header 1 (<kbd>ctrl+1</kbd>)
    * Header 2 (<kbd>ctrl+2</kbd>)
    * Header 3 (<kbd>ctrl+3</kbd>)
    * Header 4 (<kbd>ctrl+4</kbd>)
    * Header 5 (<kbd>ctrl+5</kbd>)
    * Header 6 (<kbd>ctrl+6</kbd>)
* Link (<kbd>ctrl+l</kbd>)
* Image (<kbd>ctrl+g</kbd>)
* Unordered List (<kbd>alt+ctrl+u</kbd>)
* Ordered List (<kbd>alt+ctrl+o</kbd>)
* Task List (<kbd>alt+ctrl+t</kbd>)
* Code (<kbd>ctrl+k</kbd>)
    * Syntax highlighting
* Quote (<kbd>ctrl+q</kbd>)
* Horizontal Rule (<kbd>ctrl+r</kbd>)
* Table (<kbd>alt+shift+t</kbd>)
* Snippets
    * Tab character
    * UserAgent
    * Contributing message
* Emoji
* Clear content (<kbd>alt+ctrl+x</kbd>)


## Screenshot

![Github Comment Enhancer Screenshot](https://github.com/jerone/UserScripts/raw/master/Github_Comment_Enhancer/screenshot.jpg)


## Compatible

* [![](https://raw.github.com/jerone/UserScripts/master/_resources/Greasemonkey.png) Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/) on [![](https://raw.github.com/jerone/UserScripts/master/_resources/Firefox.png) Mozilla Firefox](http://www.mozilla.org/en-US/firefox/fx/#desktop) desktop.


## Version History

* **2.9.0**
    * Fixed GitHub changes (fixes https://github.com/jerone/UserScripts/issues/98);
* **2.8.3**
    * Fixed erroring on non-editor pages (fixes https://github.com/jerone/UserScripts/issues/95);
* **2.8.2**
    * Fix working on contact page (fixes https://github.com/jerone/UserScripts/issues/91);
* **2.8.1**
    * Emoji menu overlaps text (fixes https://github.com/jerone/UserScripts/issues/92);
* **2.8.0**
    * Reverted commit 9bf8974 to fix the toolbar on the wiki.
    * Included fix for enabling and disabling buttons per language on wiki.
    * Also fixes non-working italic button (fixes #83).
    * Added clear button back to wiki.
    * Moved help button to the right.
    * Only execute action when button is not disabled.
    * :sparkles: Added dialog when inserting link or image.
    * Homepage is now link to userscript readme.
* **2.7.0**
    * Fixed Github's name completion (fixes https://github.com/jerone/UserScripts/issues/81);
    * Restored using enter key on dropdown menus.
    * Fixed emoji text.
* **2.6.0**
    * Fixes wrong button styles in gists (fixes https://github.com/jerone/UserScripts/issues/78);
    * Fixed modals showing below other elements;
    * Added extra button with complete list of all code syntax (closes https://github.com/jerone/UserScripts/issues/18);
* **2.5.1**
    * Fixed showing list of all emoji (fixes https://github.com/jerone/UserScripts/issues/75);
* **2.5.0**
    * Fixed not running everywhere (fixes https://github.com/jerone/UserScripts/issues/66);
    * Better clear button icon;
    * Fixed comment form header on inline comments;
* **2.4.1**
    * Fixed a small bug with cached suggestions for emoji when returning to an issue/PR;
* **2.4.0**
    * Keyboard shortcuts (fixes https://github.com/jerone/UserScripts/issues/19);
* **2.3.0**
    * Added emoji's (fixes https://github.com/jerone/UserScripts/issues/37);
    * Added underline button;
    * Added option to choose the character that precedes the list;
    * Added option to choose the characters that makes up a horizontal line;
    * Fixed running on GitHub Gists and inline comments on commits (fixes https://github.com/jerone/UserScripts/issues/43);
    * Fixed linking @users on GitHub Gists (fixes https://github.com/jerone/UserScripts/issues/13);
    * Reply in correct inline commit comment textarea (fixes https://github.com/jerone/UserScripts/issues/14);
    * Searching snippets improved;
    * Improve table code;
    * Added missing tooltips;
    * Corrected dependency message;
* **2.2.0**
    * Fixed issues after recent layout updates (fixes https://github.com/jerone/UserScripts/issues/43);
    * Added support for GFM task lists in replies (fixes https://github.com/jerone/UserScripts/issues/35);
* **2.1.0**
    * Added tab character as a snippet (thnx to [r-a-y](https://github.com/r-a-y), fixes https://github.com/jerone/UserScripts/issues/41);
    * Updated toMarkdown for replies;
* **2.0.3**
    * Fixed reply button style issue after recent layout update;
    * Fix ordered list with multi-line (fixes https://github.com/jerone/UserScripts/issues/20);
    * Small style fix with bold button in Chrome;
* **2.0.2**
    * Fix multiple reply buttons when navigating back;
    * Added native & TamperMonkey for Google Chrome compatibility (fixes https://github.com/jerone/UserScripts/issues/11);
* **2.0.1**
    * Small bug fix with reply after another layout update from Github;
* **2.0**
    * Fixed issues after recent layout updates (https://github.com/blog/1866-the-new-github-issues);
    * Fixed pjax for new issues & PR listing pages;
    * Added reply buttons (using [to-markdown](https://github.com/domchristie/to-markdown) to convert to Markdown);
* **1.6**
    * Removed floating arrow (fixes https://github.com/jerone/UserScripts/issues/7);
    * Fixed history back;
    * Fixed buttons on Github Gist;
    * Fixed inline comments;
* **1.5**
    * Added pinned contributing message;
    * Added tooltips for all buttons;
* **1.4**
    * Included on [Github Gist](https://gist.github.com);
    * Fixed issue with missing trailing space when selected;
    * Added snippets (only useragent atm);
    * Added clear button;
* **1.3**
    * Navigation logic implemented;
    * Inline comment logic implemented;
    * Included on Wiki pages;
    * Fixed warnings by JSHint;
* **1.2**
    * Added simple table logic;
    * Added headers 4 'til 6;
    * Combined headers in one button;
    * Reordered buttons;
    * Added Task Lists https://help.github.com/articles/writing-on-github#task-lists
    * Added fenced code blocks;
    * Clean up;
* **1.1.1**
    * Fixed space being not part of selection again;
* **1.1**
    * Fixed space being not part of selection;
    * Added new line when needed;
* **1.0**
    * Initial version;


## Test cases

* https://github.com/jerone/UserScripts/issues/new (new issue)
* https://github.com/jerone/UserScripts/issues/1 (new comment & edit comment)
* https://github.com/jerone/UserScripts/commit/master (comments below & inline comments)
* https://github.com/jerone/UserScripts/wiki/_new (new wiki)
* https://github.com/jerone/bootstrap-material-design/pull/new/feature/sass (new PR)
* https://gist.github.com/jerone/9526258 (new comment & edit comment)
* https://github.com/contact (new message without suggester)


## Dependencies

* Part of [domchristie](https://github.com/domchristie)'s library [**to-markdown**](https://github.com/domchristie/to-markdown) is used.


## Contributors

* [tophf](https://github.com/tophf)
* [r-a-y](https://github.com/r-a-y)


## External links

* [Greasy Fork](https://greasyfork.org/scripts/493-github-comment-enhancer)
* [OpenUserJS](https://openuserjs.org/scripts/jerone/Github_Comment_Enhancer)
