# vinheria-microsservicos
Atividade de microsserviços para Vinheria

# Vinheria - Microsserviços

## Descrição do Projeto
Este repositório contém os microsserviços da Vinheria para a atividade de arquitetura de APIs e microsserviços.

## Microsserviços

| Serviço | Descrição |
|---------|-----------|
| servico-pedidos | Gestão de pedidos, fornecedores e estoque |
| servico-producao | Registro de colheitas, fermentação e armazenamento |

## Tecnologias Utilizadas
- Docker para conteinerização
- Jenkins para CI/CD
- Wireshark para análise de segurança

## Como Executar

### Com Docker
```bash
docker run -d --name servico-pedidos nginx
docker run -d --name servico-producao nginx
docker ps
