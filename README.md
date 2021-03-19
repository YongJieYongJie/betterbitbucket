# Better BitBucket

_Sheeple! For far too long have our eyes been blinded by the light theme of
Bitbucket---the #FFFFFF that countless bugs were attracted to._

_But fear not! No longer shall we be held dominion under such tyranny. The
choice (of color palette) is upon us---follow the instructions below and let
the darkness begin._

In gist, here's a poorly-made dark theme for BitBucket Server, enjoy! 


## Installation

1. Install the [Stylus][stylus-link] browser extension:
    - [Chrome / Edge][chrome-edge-link]
    - [Firefox][firefox-link]
1. Open the custom dark theme CSS stylesheet over [here][user-style-link].
1. On the Stylus pop-up, click on "Install style"
1. Visit any BitBucket pull request page, and enjoy the dark theme.

[stylus-link]: https://add0n.com/stylus.html
[chrome-edge-link]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne
[firefox-link]: https://addons.mozilla.org/firefox/addon/styl-us/
[user-style-link]: https://github.com/YongJieYongJie/betterbitbucket/raw/main/betterbitbucket.user.css


## Advanced Usage

_Readers beware: thread carefully in the tomes that follow, for once the
craftsman of binary tools have been acquainted with the ancient knowledge, no
others tools will ever prove sufficient is the quest of._

More plainly, I have also written custom stylesheets that allow you to view
the state of the file with and without the changes in the pull request.


### Recommended Steps

1. Assign a keyboard shortcut to the Stylus extension (I recommend
`Ctrl+Shift+S`):
    - [Chrome][chrome-shortcut-link]
    - [Firefox][firefox-shortcut-link]
    - (Or just use Google how to do it yourself)
1. Install the custom stylesheets for showing the file:
    - [without changes from the pull request][before-link]
    - [with changes from the pull request][after-link]
1. When reviewing pull requests:    
    1. Switch to "Side-by-side diff" mode
    1. Press the keyboard shortcut assigned to the Stylus extension
    1. Press the shortcut key to activate / deactivate the appropriate
    stylesheet for showing only the before or after state of the file.
    
[chrome-shortcut-link]: https://obie.ai/blog/how-to-add-and-remove-custom-keyboard-shortcuts-and-hotkeys-for-a-chrome-extension-in-5-seconds-flat/
[firefox-shortcut-link]: https://support.mozilla.org/en-US/kb/manage-extension-shortcuts-firefox
[before-link]: https://github.com/YongJieYongJie/betterbitbucket/raw/main/betterbitbucket-before.user.css
[after-link]: https://github.com/YongJieYongJie/betterbitbucket/raw/main/betterbitbucket-after.user.css
