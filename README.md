# Custom Test Extension by Diwakar Singh

A chrome extension that works on top of any assessment website, starting when the
user opens a test page. Once the user clicks the &quot;end test&quot; button, the chrome
extension should be disabled and the browser should return to its normal state. The
extension should have basic features such as preventing browser navigation, keeping
the browser window in full mode while the user is taking the test, and disabling the user
from manually closing the browser.

### Added Basic Features

- [ ] Extension should work only in selected URLs(test page) during a certain time/trigger.
- [x] The browser should open in full screen mode.
- [x] Pop up should be shown when someone switches between 2 tabs or Application.
- [x] More than one tab can’t be opened.
- [ ] Users should not be able to close the tab by the normal close button [shortcut keys should not work too]. (User should only be able to close tab by clicking on
“End Test” Button)
- [ ] Should do requirement check initially when extension is activated:
a. Audio
b. Camera
c. Internet Stability
- [ ] Capture the user related information in local storage.(e.g. IP, requirements check)
