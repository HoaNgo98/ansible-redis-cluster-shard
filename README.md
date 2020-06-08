# ansible-redis-cluster-shard
MÔ HÌNH REDIS CLUSTER 6 NODE: 3 Master, 3 Slave. Mỗi Master sẽ có 1 Slave
# deploy
+ ansible-playbook -i redis.hosts redis.yml --tags setup
+ ansible-playbook -i redis.hosts redis.yml --tags config
