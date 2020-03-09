# techtonica-ci-pipeline-demo

# The Docs

## serving the docs locally

Make sure you have jekyll:
```bash
brew upgrade ruby
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.bash_profile
ruby -v
echo 'export PATH="$HOME/.gem/ruby/2.7.0/bin:$PATH"' >> ~/.bash_profile
source ~/.bash_profile
```

`cd` into the `./docs` directory and run:
```bash
cd ./docs
gem install --user-install bundler jekyll
bundle update
bundle exec jekyll serve
```

In your favorite browser, open `localhost:4000`.