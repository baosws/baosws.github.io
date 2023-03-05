brew update
brew install ruby
export PATH="/Users/baoduong/.gem/ruby/2.6.0/bin:$PATH" >> .zshrn
export GEM_HOME="$HOME/.gem" >> .zshrc
source .zshrc
gem install rouge -v 3.30.0
gem install bundler jekyll
cd causality_deadlines
bundle install