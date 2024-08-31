Запустил кластер кафки (из дз 1), настроил авторизацию и ACL.
user1 имеет права на запись в test-topic
user2 имеет права на чтение в test-topic
user3 не имеет никаких прав.
Скриншот с результатом kafka-topics.sh - list-topics.png.
Скриншот с результатом kafka-console-producer.sh - produce-messages.png.
Скриншот с результатом kafka-console-consumer.sh - consume-messages.png.
Ansible репозиторий с ролями, тасками, плейбуками и т.д. можно найти в моем гите https://github.com/ivanpriz/ansible-infra/tree/feature/kafka-auth-2