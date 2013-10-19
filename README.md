# myokoym.net

## development

### prepare

  1. clone the repository

        git clone git@github.com:myokoym/myokoym.net.git

  2. bundle install

        cd myokoym.net
        bundle install

### modify

  1. launch the local server

        bundle exec middleman server

  2. open the page in the browser

    [http://localhost:4567](http://localhost:4567)

  3. modify files in source/ or data/

  4. reload browser

  5. commit and push

        git add .
        git commit
        ...write a concrete reason...
        git push origin master

### deploy

  1. build from sources in source/ to HTMLs in build/

        bundle exec middleman build

  2. deploy to GitHub Pages

        bundle exec middleman deploy
