source "https://rubygems.org"
ruby "2.4.3"

# This will help ensure the proper Jekyll version is running.
gem "jekyll", "3.6.2"
gem "html-proofer", ">= 3.7.6", :groups => [:development, :test]
gem "git-set-mtime", github: "jayvdb/git-set-mtime", branch: "file-exists"

group :jekyll_plugins do
  gem "github-pages", ">= 177"
  gem "jekyll-netlify", github: 'jayvdb/jekyll-netlify', ref: 'e7efada3'
  gem "disqus-for-jekyll", ">= 1.0.1"
  gem 'jekyll-last-modified-at', github: 'riouwa/jekyll-last-modified-at', branch: 'no-git'
  gem 'jekyll-include-cache', '>= 0.1.0'
  gem 'jekyll-analytics', github: 'hendrikschneider/jekyll-analytics'
  gem 'jekyll_pages_api', '>= 0.1.6'
  gem 'jekyll_pages_api_search', github: 'jayvdb/jekyll_pages_api_search', branch: 'v0.4.4-safe'
  gem 'jekyll_social_icons', github: 'jayvdb/jekyll_social_icons', branch: 'disable-style'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
