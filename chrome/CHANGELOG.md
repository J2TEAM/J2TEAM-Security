# Change Log
All notable changes to [J2TeaM Security](https://j2team.github.io/J2TeaM-Security/index.html) will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).

## Unreleased
...

## 0.1.2 - 2016-12-10
### Added
- Show a notification when the user cannot login to Premium area.
- Noel-mode option (snowfall on all websites).

### Changed
- Use new method to disable Chrome Inline-install API.

## 0.1.1 - 2016-12-08
### Changed
- Fix a minor bug in background page.

## 0.1.0 - 2016-12-08
### Added
- Now users can change hotkey via context menu (Help > Change hotkey).

### Changed
- Try to use a blank tab when create a new tab.
- Users cannot report my websites via context menus:
  + junookyo.blogspot.com
  + *.junookyo.xyz

## 0.0.55 - 2016-11-21
### Added
- Block malicious files sent via Messenger/Chat on Facebook. [Click here to read more!](https://junookyo.blogspot.com/2016/11/ma-doc-facebook-qua-tin-nhan.html?utm_source=j2team_security_changelog)

## 0.0.54 - 2016-11-17
### Added
- Dashboard for [Premium users](http://code.junookyo.xyz/j2team-security/premium-upgrade/).

## 0.0.53 - 2016-11-15
### Added
- [Block auto check-in on Facebook](https://www.youtube.com/watch?v=ZktcOM4MIk0) (privacy options).
- Facebook Pages Manager (Premium feature).
- Facebook Video Downloader (Premium feature).

### Changed
- Auto changes the read status of the previous messages when users send a new message. This will make Facebook stops showing too many notifications of new messages on mobile.

## 0.0.52 - 2016-11-14
### Added
- Now the users can change the language via the context menu (Help > Change language).
- Option to toggle notifications when updated to new version.
- Facebook Friends Manager (Premium feature).

## 0.0.51 - 2016-11-13
### Changed
- Facebook Clock: handle DOM error if cannot find the blue bar.
- Minor changes in the content script.

## 0.0.50 - 2016-11-12
### Changed
- Facebook Kount: Improve the algorithm.

## 0.0.49 - 2016-11-12
### Added
- [Facebook Kount Premium](https://www.youtube.com/watch?v=-7916PWaHWk).

### Changed
- Facebook Kount: Improve the algorithm.

## 0.0.48 - 2016-11-11
### Changed
- Change the UI of the Free tools to fit with the Premium tools.

## 0.0.47 - 2016-11-10
### Changed
- Facebook Kount: Improve the algorithm.
- Facebook Group Manager (Premium feature): fix the leave group function.

## 0.0.46 - 2016-11-10
### Changed
- Check API definition on the Premium page to prevent error (reported by [Đức Đỗ](https://www.facebook.com/ducdo.hct)).
- Facebook Kount: Improve the algorithm.

## 0.0.45 - 2016-11-10
### Changed
- Facebook Security Tester, Facebook Object Ranking and Facebook Kount: Check Facebook login status before execute the main function.
- Disable context menus on invalid URLs ("chrome:" or "file:" protocol).

## 0.0.44 - 2016-11-10
### Added
- Link to changelog on context menus.

### Changed
- Update link to JavaScript file on the Facebook Kount page.

## 0.0.43 - 2016-11-10
### Added
- [Facebook Kount](https://www.youtube.com/watch?v=_XvF-H4LHNM) - Message statistics.

### Changed
- The "Block Facebook Timeline" feature now works on mobile domains.

## 0.0.42 - 2016-11-08
### Changed
- Hide GitHub corner for Premium users.

## 0.0.41 - 2016-11-08
### Added
- [Facebook Group Manager](http://code.junookyo.xyz/j2team-security/facebook-group-manager/) (Premium features).

## 0.0.40 - 2016-11-06
### Added
- Open the home page when users uninstall the extension.
- Now users can upgrade to a Premium account to [get more features](http://code.junookyo.xyz/j2team-security/premium-upgrade/).

### Changed
- Skip blocking [Self-XSS](https://www.facebook.com/selfxss) on m.facebook.com (reported by [Hoàng Vũ](https://www.facebook.com/HoangVu.0711))
- Facebook Clock (appear next to the Home button) will auto-sync every 30 seconds instead of 1 second for better performance.

## 0.0.39 - 2016-11-02
### Added
- Show notify when extension update to new version. The user can click on the notify to see the changes in new version.

### Changed
- Update links in context menus.
- Use a new way to block malware/ads scripts (because blocking malicious script embedded in the page by updating the tab will make the user can not access the site's content).

## 0.0.38 - 2016-10-31
### Added
- Facebook [Picture-in-Picture](https://en.wikipedia.org/wiki/Picture-in-picture) Mode: https://www.youtube.com/watch?v=o7qQEYPJ-SQ
- Unlock time limitation on www.studyphim.vn
