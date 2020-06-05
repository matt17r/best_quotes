# Best Quotes

This is a demo app to exercise my "new" [Ruby on Rulers framework](https://github.com/matt17r/rulers)

## Usage

This is a rack app. Launch with `rackup -p 3001` and access from http://localhost:3001.

Launch using [rerun](https://github.com/alexch/rerun) to automatically re-launch the webserver when files change: `bundle exec rerun -- rackup -p 3001`

### Pre-requisites

This app currently requires [Rulers](https://github.com/matt17r/rulers) to be in the same parent directory. You can change this by updating (or removing) the `path` in the Gemfile.
