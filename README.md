RegExp Tester
=============

Test your regular expressions without online tools. [DevUtils.app](https://devutils.app) allows you to quickly test regular expressions with a sample text without any internet connection. It supports ICU regex engine and flags: case sensitive, white space, comments, line separator options...

<p align="center">
  <img src="https://devutils.app/assets/demo-regexp-tester-dark.png" alt="DevUtils.app: RegExp Tester macOS app"/>
  <br/>
  <a href="https://devutils.app/">🚀  Download</a> | <a href="https://devutils.app/demo">🎬  Demo & Screenshots</a> | <a href="https://github.com/DevUtilsApp/DevUtils-app">📝  View source</a>
</p>

Quickly test a regular expression
---------------------------------

You can test a regular expression from anywhere in your macOS (terminal, in email, web browser,...). Activate the app by:

* Copy text ► Press ⌃⌥⌘Space `(Or your own customized hotkey, up to you)`
* Copy text ► Click to icon <img src="https://devutils.app/menu-icon-dark.png" alt="DevUtils.app status bar icon" width="28px" /> in the status bar
* Select text ► Right-click ► "Inspect in DevUtils.app" `(This menu appears after you install the app)`


Input
-----

Enter your regular expression in the input textbox and the sample text in the second textbox. The matches will be highlighted as you type.

You can also load the sample text from a file from your computer using the "Load file..." button.

Output
------

The tool will render the matches with green background. You can also inspect each matches using the text view at the bottom. The text view lists all the matches separated by a new line.

You can navigate to each matches by clicking the "back" and "forward" button. The label in between displays the number of matches for the current regex.

Options
-------

Currently, the supported regex engines are:

*   ICU Engine

Supported flags:

*   Case insensitive
*   Allow use of white space and #comments within patterns
*   "." matches line separators
*   "^" and "$" matches at the start and end of each line within the input text
*   "\\b" matches words based on boundaries defined in Unicode UAX 29, Text Boundaries

You can click to the gear icon to set the flags.

![DevUtils.app: RegExp Tester Settings macOS app](https://devutils.app/assets/settings/setting-regexp-tester.png)
