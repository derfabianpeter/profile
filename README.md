[![pipeline status](https://git.peter.saarland/fabian/peter-www/badges/master/pipeline.svg)](https://git.peter.saarland/fabian/peter-www/commits/master)

# www.peter.saarland
This is the Source Code for my personal Website - https://www.peter.saarland. It's also an experiment in social distribution.

# Install (MacOS)
```
brew install hugo || brew upgrade hugo
hugo new site www.peter.saarland
git init
git submodule add https://github.com/luizdepra/hugo-coder.git themes/coder
echo 'theme = "coder"' >> config.toml
hugo new about.md
hugo new kontakt.md
```

# Deploy
TBD