source "https://rubygems.org"
 
gem 'awesome_print', :git => 'git@github.com:awesome-print/awesome_print.git'
gem "hashie" 
gem "sinatra", '2.0.2'
gem "octokit", '~> 2.0'
 
gem "pry", :group => :development

group :test do
  gem "rspec"
end



# Including gem followed by the name of the gem will make sure that gem is installed for the project. Listing a gem without a version will cause Bundler to download the newest version of that gem.

# Including a specific version, like gem 'sinatra', '1.4.5' will lock the version so your app only uses that version.

# Including ~> before the version number will limit your app to using either the version you list or a version with only minor updates (or patches, depending on your syntax).
# For some reason lost to history, Rubyists have decided to call this ~> "Twiddle-Wakka."