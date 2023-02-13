## To run locally

1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.


## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
  * Home: _pages/about.md
  * Contact: _pages/contact.md
  * Members: _pages/members.html
* Collections of pages:
  * Publications: _publications/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png
