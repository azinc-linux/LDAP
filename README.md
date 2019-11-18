#LDAP (FreeIPA)

client_install.yml - playbook для развертывания freeipa-клиента.

server_install.yml - playbook для развертывания freeipa-сервера.

Для поддержки идемпотентности при развертывании проверяется наличие /etc/ipa/default.conf и, если файл отсутствует, то производится 
конфигурирование.
