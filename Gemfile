source "https://rubygems.org"

# Add Jekyll and the theme
gem "jekyll", "~> 4.3"
gem "jekyll-agency", github: "raviriley/agency-jekyll-theme"

# This is a common group for GitHub Pages compatibility
group :jekyll_plugins do
  gem "github-pages", "~> 232", group: :jekyll_plugins
end

# Windows-specific gem
gem "wdm", ">= 0.1.0" if Gem.win_platform?
