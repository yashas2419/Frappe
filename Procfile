
redis_cache: redis-server config/redis_cache.conf
redis_queue: redis-server config/redis_queue.conf
web: bench serve --port 8001
socketio: node apps/frappe/socketio.js
watch: bench watch
worker: bench worker 1>> logs/worker.log 2>> logs/worker.error.log
schedule: bench worker --queue short
