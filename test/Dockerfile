FROM sheerun/docker-buildpack:cedar14

ADD Gemfile Gemfile.lock main.rb Procfile ./

RUN buildpack install ruby

CMD ["start", "web"]
