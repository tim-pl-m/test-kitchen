# -*- encoding: utf-8 -*-
source "https://rubygems.org"
gemspec


gem "train", :github => "chef/train", :branch => "winrm-v2"
gem "winrm", :github => "winrb/winrm", :branch => "winrm-v2"
gem "winrm-fs", :github => "winrb/winrm-fs", :branch => "winrm-v2"
gem "winrm-elevated", :github => "winrb/winrm-elevated", :branch => "winrm-v2"

group :guard do
  gem "guard-minitest"
  gem "guard-cucumber", "~> 1.4"
  gem "guard-rubocop"
  gem "guard-yard"
end

group :integration do
  gem "berkshelf", "~> 4.3"
  gem "kitchen-inspec", :github => "mwrock/kitchen-inspec", :branch => "winrm-v2"
end

group :test do
  gem "codeclimate-test-reporter", :require => nil
end
