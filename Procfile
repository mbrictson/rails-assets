web: bin/rails s --port "$PORT"
sidekiq: bin/sidekiq -q update_scheduler -q update_component -q default -q reindex -c 10
