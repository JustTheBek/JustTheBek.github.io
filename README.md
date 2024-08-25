# This (private) development repo contains the source code (incl. resources such as posts and images) of my personal blog.

-> For the development I use Jekyll and the template basically-basic.

-> The hosting is done from a different repo: https://github.com/JustTheBek/JustTheBek.github.io

-> Handling of Ruby gems and all the dependencies is done by bundler. Before executing on a new machine / after changing dependencies the command >> bundle install should be executed.

-> The main config is stored in _config.yml, theme specific stuff is located in theme.yml

-> Currently the deployment happens completely manually by copying the content of the _site folder (after execution of >> bundle exec jekyll build) to the hosting repo. This should be automated in the future.

-> Testing on localhost can be done by executing the command: >> bundle exec jekyll serve  (attention: the embedded videos will probably not work and the links neither. The links should be fixed.)

->TODOs: fix search bar, fix post references (one step jump instead of step inbetween, upload more content, add references)
