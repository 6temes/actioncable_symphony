release: rails db:migrate
web: puma -p ${PORT:-3000} -e production --early_hints
worker: rails jobs:work
