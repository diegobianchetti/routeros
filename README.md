# routeros
Testing Ansible AWX with Community RouterOS Collection


## adicionando hostnames sem serviço de DNS

Quando incluir o host pelo nome o bloco de texto para variáveis deve ter a declaração do IP 

---
  ansible_host: <IP.IP.IP.IP>
