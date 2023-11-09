# posthuman-links-jekyll

### macOS setup

### Install ruby
```
brew install ruby #this step is probably not be needed
```

### Install rbenv
```
brew install rbenv ruby-build
```

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
