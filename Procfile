web: bundle exec rails server -p $PORT
worker: bundle exec sidekiq -e production -c 2 -q default -C config/sidekiq.yml
