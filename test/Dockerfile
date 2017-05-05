FROM sheerun/docker-buildpack:cedar14

ADD Gemfile Gemfile.lock main.rb Procfile ./

RUN buildpack install https://github.com/heroku/heroku-buildpack-ruby

CMD ["start", "web"]
