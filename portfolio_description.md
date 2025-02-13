# Implementação NFS com Kubernetes na Digital Ocean

## Visão Geral
Projeto educacional focado na implementação de um servidor NFS (Network File System) utilizando Kubernetes na Digital Ocean. O objetivo principal foi criar uma solução de armazenamento compartilhado para aplicações containerizadas, demonstrando conceitos importantes de infraestrutura cloud e DevOps.

## Desafio
O principal desafio foi criar uma infraestrutura que permitisse o compartilhamento eficiente de dados entre diferentes pods em um cluster Kubernetes, mantendo a persistência e disponibilidade dos dados.

## Solução
Implementei uma arquitetura baseada em:
- Cluster Kubernetes na Digital Ocean
- Servidor NFS para armazenamento persistente
- Sistema de volumes persistentes (PV) e claims (PVC)
- Deployments e Services para gerenciamento de aplicações

## Tecnologias Utilizadas
- Kubernetes para orquestração de containers
- NFS para compartilhamento de arquivos
- Digital Ocean como provedor cloud
- Docker para containerização
- Linux Ubuntu como sistema operacional base

## Resultados
- Implementação bem-sucedida de armazenamento compartilhado
- Sistema escalável e flexível
- Documentação completa do processo
- Código fonte disponível no GitHub

## Aprendizados
- Configuração e gerenciamento de clusters Kubernetes
- Implementação de soluções de armazenamento em cloud
- Boas práticas de DevOps
- Segurança em ambientes cloud

## Observações
Este é um projeto desenvolvido para fins educacionais, demonstrando conceitos importantes de infraestrutura moderna. As configurações de segurança utilizadas são simplificadas e não são recomendadas para ambientes de produção.

## Links
- [Repositório GitHub](https://github.com/BrendoTrindade/deploy-nfs-cloud)
- [Documentação Completa](https://github.com/BrendoTrindade/deploy-nfs-cloud/blob/main/README.md)

## Status do Projeto
✅ Concluído (Projeto Educacional)
