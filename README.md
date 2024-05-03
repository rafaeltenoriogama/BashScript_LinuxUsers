# Projeto de Configuração de Ambiente no Linux

Este projeto consiste em um script em Bash para configurar um ambiente básico no Linux. Ele cria diretórios, grupos de usuários e configura as permissões de acesso.

## Requisitos

- Sistema operacional Linux

## Instalação e Uso

1. Clone este repositório para o seu sistema local:

```
git clone https://github.com/rafaeltenoriogama/BashScript_LinuxUsers
```

2. Navegue até o diretório do repositório:

```
cd /BashScript_LinuxUsers
```

3. Execute o script bash:

```
chmod +x iac.sh

.iac.sh
```

## Detalhes do Script

O script realiza as seguintes operações:

- Cria diretórios: `/publico`, `/adm`, `/ven`, `/sec`.
- Cria grupos de usuários: `GRP_ADM`, `GRP_VEN`, `GRP_SEC`.
- Cria usuários e associa aos grupos correspondentes.
- Configura permissões nos diretórios criados.

## Notas

- Certifique-se de revisar e ajustar as senhas e permissões conforme necessário antes de executar o script em um ambiente de produção.
- Este script foi desenvolvido como parte do curso de Linux Fundamentals.
