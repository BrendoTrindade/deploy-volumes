# Projeto de Estudos: PostgreSQL em Kubernetes

Este é um projeto educacional que demonstra a implementação básica de um banco de dados PostgreSQL em um ambiente Kubernetes.

⚠️ **AVISO**: Este é um projeto de estudos e NÃO deve ser usado em produção.

## 🚀 Tecnologias

- Kubernetes
- PostgreSQL
- Docker
- Persistent Volumes
- NodePort Service

## 📋 Pré-requisitos

- Kubernetes cluster (local ou remoto)
- kubectl configurado
- Docker instalado

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/k8s-postgres-study
```

2. Aplique os manifestos Kubernetes:
```bash
kubectl apply -f deployment.yaml
```

## 📦 Estrutura do Projeto

```
.
├── README.md
├── deployment.yaml    # Manifesto principal do Kubernetes
└── docs/             # Documentação adicional
```

## 🛠️ Configurações

### Deployment
- Imagem: PostgreSQL
- Porta: 5432
- NodePort: 30000

### Variáveis de Ambiente
- POSTGRES_DB: kubenews
- POSTGRES_USER: kubenews
- PGDATA: /var/lib/postgresql/data/pgdata

### Volume
- Tipo: HostPath
- Caminho: /k3d/images

## ⚠️ Limitações e Avisos de Segurança

Este projeto é apenas para fins educacionais e possui várias limitações de segurança:

- Senhas em texto plano
- Sem SSL/TLS
- Sem backup configurado
- Sem políticas de segurança
- Sem alta disponibilidade

## 📚 Aprendizados

- Conceitos básicos de Kubernetes
- Deployments e Pods
- Persistência de dados
- Exposição de serviços
- Configuração de ambiente

## 🤝 Contribuindo

Este é um projeto de estudos e contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature
3. Commitar suas mudanças
4. Fazer push para a branch
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✨ Agradecimentos

- Comunidade Kubernetes
- Documentação oficial do PostgreSQL
- Contribuidores do projeto

---
⚠️ Lembre-se: Este é um projeto educacional e não deve ser usado em ambiente de produção.
