# Change Log
This project is currently at an alpha stage. It will continue on the `0.*.*` branch until the first stable release.  

## [0.3.0] - 2016-06-08
### Changed
- Fixed various bugs with the MailContext
- Changed email step from '...email to <email> should match "<message>"' to '...email to <email> should contain "<message>"'
- `InboxFactory` now refreshes the inbox each time its requested
- Rename extension to **WordPressBehatExtension** and updated namespace accordingly
- Correct CHANGELOG link

## [0.2.0] - 2016-06-07
### Changed
- `.gitignore` to hide IDE files
- Rename namespace **Johnbillion\ WordPressExtension** as **StephenHarris\WordPressBehat**
- Remove autoload of PHPUnit functions, use `PHPUnit_Framework_Assert` in contexts instead
- Applied PSR-2 coding standard
- Update Readme with history & aims

### Added
- This changelog
- Add Email, Inbox and InboxFactory classes to improve handling of checking e-mails sent by `wp_mail()`. 
- Adds unit test

## 0.1.0 - 2016-06-03
### Added
- Additional contexts 


[0.3.0]: https://github.com/stephenharris/WordPressBehatExtension/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/stephenharris/WordPressBehatExtension/compare/0.1.0...0.2.0

