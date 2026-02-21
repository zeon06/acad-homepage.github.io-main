source "https://rubygems.org"

# 使用 GitHub Pages 核心插件，它已经包含了 Jekyll 本身
gem "github-pages", group: :jekyll_plugins

# Windows 环境必备
gem "eventmachine", ">= 1.2.7", platforms: [:ruby, :mswin, :mingw, :x64_mingw]
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
gem "wdm", "~> 0.1.1" if Gem.win_platform?

# Ruby 3.0+ 及部分 2.7 环境需要手动添加这个来启动服务器
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  # 已移除 hawkins，因为它在 Windows 上会导致 EventMachine LoadError
end