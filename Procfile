#web:         bundle exec passenger start -p $PORT --max-pool-size $PASSENGER_MAX_POOL_SIZE
web:         bundle exec passenger start
worker:      QUEUES=default,paperclip,mailers bundle exec rake jobs:work
