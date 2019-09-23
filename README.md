# installation-of-es-redis-jdk-memcached


 # Memcached:
  sudo apt-get install memcached
  sudo apt install libmemcached-tools
  sudo systemctl restart memcached
 # Redis:
  https://www.hugeserver.com/kb/install-redis-4-debian-9-stretch/
 # Elasticsearch:
  sudo apt install openjdk-11-jre-headless
  1. wget -qO - https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add -
  2. echo "deb https://artifacts.elastic.co/packages/6.x/apt stable main" | sudo tee -a /etc/apt/sources.list.d/elastic-6.x.list
  3. sudo apt update
  4. sudo apt install elasticsearch
  5. Open port and localhost in /etc/elasticsearch/elasticsearch.yml
  6. sudo systemctl start elasticsearch
  7. sudo systemctl enable elasticsearch
  8. curl -X GET "localhost:9200"
 # Postgress:
  1.sudo apt-get install postgresql postgresql-contrib libpq-dev
  2.Additional commands:
  3.sudo apt-get install imagemagick
  4.gem install pg -v '1.1.4' --source 'https://rubygems.org'
  5.sudo apt-get install libpq-dev
  6.HugeServer KnowledgebaseHugeServer Knowledgebase
  7.How to install Redis 4 on Debian 9 (Stretch)
  Introduction Redis is a flexible open-source, key-value data store, used as a database, cache and message broker. Redis allows the user to store vast amounts of data without the limits of a relational database. In order to achieve its outstanding performance, Redis works with an in-memory dataset. Depending on your use-case, you can persist it … Continue reading How to install Redis 4 on Debian 9 (Stretch) →
