
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve --livereload
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

source "https://rubygems.org"

gem "jekyll"

#jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'wdm', '~> 0.1.1', :install_if => Gem.win_platform?

 gem 'eventmachine', '1.2.7',  platform: :ruby
