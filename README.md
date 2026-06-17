# Kubernetes Labs

Repositório criado para consolidar conhecimentos em Kubernetes através de laboratórios práticos executados em ambiente local.

# Objetivo

Estudar os principais recursos do Kubernetes por meio de exemplos simples e exercícios práticos, compreendendo como os componentes se relacionam em um ambiente real.

Os laboratórios foram desenvolvidos para reforçar conceitos fundamentais utilizados em ambientes corporativos e em processos seletivos para posições de Infraestrutura, Cloud e DevOps.

## Conteúdo

- Pods
- Services
- Deployments
- ConfigMaps
- Secrets
- Volumes
- Liveness Probe


## Ambiente

- Windows 11
- Docker Desktop
- Kubernetes Local
- kubectl

## Comandos úteis

kubectl get pods
kubectl get svc
kubectl get deployments
kubectl describe pod <nome>
kubectl logs <nome>
kubectl rollout status deployment/nginx-deployment

# Laboratórios

- Services

Conceitos estudados:

Labels
Selectors
ClusterIP
Endpoints

Principais comandos:

kubectl get svc
kubectl get endpoints
kubectl describe service <service>

- Deployments

Conceitos estudados:

ReplicaSets
Escalabilidade
Rolling Update
Self Healing

Principais comandos:

kubectl get deployments
kubectl get rs
kubectl rollout status deployment/<deployment>

- ConfigMaps

Conceitos estudados:

Configurações desacopladas da aplicação
Variáveis de ambiente
Montagem de arquivos de configuração

- Secrets

Conceitos estudados:

Armazenamento de informações sensíveis
Consumo de Secrets por variáveis de ambiente
Integração com Deployments

- Volumes

Conceitos estudados:

Persistência de dados
Volumes temporários
Introdução a Persistent Volumes

- Probes

Conceitos estudados:

Liveness Probe
Readiness Probe
Saúde da aplicação
Troubleshooting