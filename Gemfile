source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", "~> 231", group: :jekyll_plugins
# gem 'liquid', '~> 4.0', '>= 4.0.4'

group :jekyll_plugins do
  gem 'jekyll-archives', '~> 2.2.1'
  gem 'jekyll-feed', '~> 0.17.0'
  gem 'jekyll-paginate', '~> 1.1.0'
  gem 'jekyll-seo-tag', '~> 2.8.0'
  gem 'jekyll-sitemap', '~> 1.4.0'
end


# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.8"

gem "faraday-retry"
