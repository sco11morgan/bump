worker: bundle exec sidekiq -q bump-repos_to_fetch_files_for -q bump-dependencies_to_update -r ./app/init_sidekiq.rb -c 1
web: bundle exec rackup ./sidekiq_web.ru -p $PORT
