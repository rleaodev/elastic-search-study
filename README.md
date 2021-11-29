## Elastic Search

Projeto feito com o uso de Ansible e Vagrant para estudo das tecnologias da stack ELK.

Para instalar os programas basta ter instalado na máquina host o Python, Ansible, Vagrant e Virtualbox.

```
ansible-playbook -i ansible/hosts ansible/provisioning.yaml
```

Os arquivos que foram importados para o ElasticSearch estão dentro de um Zip na pasta files.


O Conteúdo de ELK efetuado na infra descrita neste repo foi adquirida neste curso: [Elasticsearch 7 e Elastic Stack: o Curso Completo!
](https://www.udemy.com/course/elasticsearch-elastic-stack/)

Recomendo, é uma ótima introdução a tecnologia :)