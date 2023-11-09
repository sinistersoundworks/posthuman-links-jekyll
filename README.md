# posthuman-links-jekyll

### macOS setup


### Install rbenv
```
brew install rbenv ruby-build
```
if this fails, you might need to install ruby first `brew install ruby`

### Install ruby >= 3.1.2
```
rbenv install 3.1.4
rbenv global 3.1.4
```

### Clone repo
```
git clone https://github.com/sinistersoundworks/posthuman-links-jekyll 
cd posthuman-links-jekyll
```

### Install requirements
```
bundle install
```

### Develop
```
bundle exec jekyll serve [-l] [-H host] 
```

### Build
```
JEKYLL_ENV=production bundle exec jekyll build
```
