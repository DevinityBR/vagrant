# Introdução ao Vagrant

## História e Contexto

- O **Vagrant** é uma ferramenta opensource de automação escrita em Ruby e mantida pela **HashiCorp**.
- Ela simplifica a criação e gerenciamento de ambientes de desenvolvimento virtuais.
- Permite que você defina e configure máquinas virtuais de forma **totalmente automatizada**.

## Fundamentos da Vagrant

- **Vagrantbox**: Uma imagem base pronta com pacotes necessários para o funcionamento da máquina virtual.
- **Vagrantfile**: Um script escrito em Ruby que descreve todos os aspectos de uma máquina virtual:
    - **Hostname**, **IP**, **CPU**, **memória**, **disco**, **sistema operacional**.
    - Quantidade de máquinas que serão criadas.
    - Scripts para o provisionamento e configuração.

# Exercicio
1. Adicione um Script para atualizar o Sistema Operacional
2. Envie um Arquivo para a Máquina durante a criação, uma chave SSH por exemplo;
3. Crie uma segunda máquina;\
3.1. Não esqueça de Nomeá-las;

> NOTA: Os passos 1 e 2 devem se repetir nas duas máquinas criadas.

# Referências

https://www.vagrantup.com

https://developer.hashicorp.com/vagrant/install
