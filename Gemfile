# -*- encoding: utf-8 -*-
source "https://rubygems.org"
gemspec

gem "winrm", github: "winrb/winrm", branch: "winrm-v2"
gem "winrm-fs", github: "winrb/winrm-fs", branch: "winrm-v2"
gem "winrm-elevated", github: "winrb/winrm-elevated", branch: "winrm-v2"

group :guard do
  gem "guard-minitest"
  gem "guard-cucumber", "~> 1.4"
  gem "guard-rubocop"
  gem "guard-yard"
end

group :integration do
  gem "berkshelf", "~> 4.3"
  gem "kitchen-inspec", "~> 0.12.5"
end

group :test do
  gem "codeclimate-test-reporter", :require => nil
end
