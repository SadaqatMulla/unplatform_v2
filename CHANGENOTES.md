## [1.3.5] - 2017-03-28
### Added
- Add acknowledgements in README.

1.3.4:
  - Fix windows build script; copy qbank executable.

1.3.3:
  - Include OEA and content player configs in this repo.
  - Update build scripts to use OEA and content player configs.

1.3.2:
  - Minor fixes to tools view/removes multiple scrollbars.
  - Fix the z-index of header to appear above tools.

1.3.1:
  - Minor fixes to OS X build script.

1.3.0:
  - Add session timeout warning modal. Requires `content_player` v1.1.0.

1.2.10:
  - Fix the multiple scrollbars.
  - Fix the z-index of the unplatform header to appear above content.
  - Begins reworking Homeview component for keyboard accessibility.

1.2.9:
  - Fix the template copy.

1.2.8:
  - Copy template directories on windows build.

1.2.7:
  - Remove background image on indidivual tool page.
  - Attempt to make tool iframes wider.

1.2.6:
  - Add `npm install` command for `client` directory
    for OEA.

1.2.5:
  - Return modules list in natural sorted order.

1.2.4:
  - Change how sessions are managed and expire.
  - Set default session expiration to 15 minutes of inactivity.
  - Update UI components to not store in localstorage.
  - Update UI components to redirect to home, if the
    session expires.
  - Remove redundant / permanent "configure school here"
    link.

1.2.3:
  - Refactor how to pull version for web route.

1.2.2:
  - Refactor Windows build script to use compile:ui:only
    command.

1.2.1:
  - Fix OS X launcher script to use found qbank executable.
  - Account for trailing slash on /oea route.

1.2.0
  - merge in TravisCI configuration for automated testing.

1.1.0
  - Updated the data extraction script for unplatform to
    copy the JSON files instead of the .sqlite3 file.

1.0.0
  - Initial release with working Windows build script

[1.3.5]: https://github.com/CLIxIndia-Dev/unplatform_v2/compare/v1.3.4...v1.3.5
