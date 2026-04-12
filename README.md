# DevOps na Mão na Massa 🤖
![HTML](https://img.shields.io/badge/Linguagem-HTML-blue)

## Sobre o Projeto 💡
Neste repositório, você encontrará um conjunto de ambientes de treinamento para aprender sobre DevOps utilizando ferramentas como Ansible, Docker, Jenkins, K3s, Prometheus, Sonarqube e Swarm.

## Funcionalidades Principais 🛠️
- Ambientes de treinamento para Ansible, Docker, Jenkins, K3s, Prometheus, Sonarqube e Swarm
- Configuração para automação de processos com Ansible
- Utilização de Docker para criação de containers
- Integração de Jenkins para automação de integração contínua e entrega contínua
- Configuração de clusters de containers com K3s
- Monitoramento de métricas com Prometheus
- Análise de código com Sonarqube
- Utilização de Swarm para deploy de aplicativos

## Pré-requisitos 📝
- Conhecimento básico de ferramentas de DevOps (opcional)
- Instalação de Ambiente de Desenvolvimento (IDE)
- Controle de Versão (Git)
- Conhecimento básico de Linux/Unix

## Instruções de Instalação 🔧
### Passo 1: Configuração do Ambiente
1. Clone o repositório com o comando `git clone https://github.com/usuario/devops-mao-na-massa.git`
2. Navegue até a raiz do projeto com o comando `cd devops-mao-na-massa`
3. Instale as dependências necessárias com o comando `npm install`

### Passo 2: Configuração do Ansible
1. Crie um arquivo de configuração para o Ansible com o comando `ansible-config init`
2. Adicione as variáveis de ambiente necessárias ao arquivo de configuração

### Passo 3: Execução dos Cenários
1. Execute o cenário de Ansible com o comando `ansible-playbook -i inventario.yml playbook.yml`
2. Verifique o resultado da execução do cenário com o comando `ansible-playbook -i inventario.yml playbook.yml -t results`

## Exemplos de Uso 📚
- Execute o cenário de Ansible para criar um ambiente de exemplo com o comando `ansible-playbook -i inventario.yml playbook.yml --tags example`
- Utilize o Prometheus para monitorar as métricas do ambiente criado com o comando `prometheus -config.file=prometheus.yml`

## Estrutura Simplificada do Projeto 🗂️
- `ansible-lab`: Ambiente de treinamento para Ansible
- `docker-lab`: Ambiente de treinamento para Docker
- `jenkins-lab`: Ambiente de treinamento para Jenkins
- `k3s-lab`: Ambiente de treinamento para K3s
- `prometheus-lab`: Ambiente de treinamento para Prometheus
- `sonarqube-lab`: Ambiente de treinamento para Sonarqube
- `swarm-lab`: Ambiente de treinamento para Swarm

## Licença 📜
Este projeto é licenciado sob a Licença MIT. Para mais informações, consulte o arquivo LICENSE.

---

Espero que tenha gostado! Se tiver alguma dúvida, sinta-se à vontade para perguntar 😊.