# Change Log

All notable changes to the "sublime-text-4-theme" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## v1.3.0

- Fixed token colors for property declarations e.g.
  ```js
    class Foo {
      constructor() {
        ...
      }

      // here get is now italic and Bar should be colored like every other function
      get Bar() {
        ...
      }
    }
  ```
- Variable colors are now slightly dimmer than before, they are set to #ddddd7 instead of #d8dee9.
- I also removed the original theme as this was shipped together accidentally.

## Initial release
- Initial release
