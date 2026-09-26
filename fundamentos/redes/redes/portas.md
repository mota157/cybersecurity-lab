# 🔌 Portas e Serviços

Uma porta é um ponto lógico de comunicação usado por serviços de rede.

## Exemplos comuns

| Porta | Protocolo/Serviço | Uso |
|---|---|---|
| 22/tcp | SSH | Acesso remoto seguro |
| 80/tcp | HTTP | Comunicação web |
| 443/tcp | HTTPS | Comunicação web segura |
| 53/udp | DNS | Resolução de nomes |

## TCP e UDP

A mesma numeração pode existir separadamente em TCP e UDP.

Por exemplo:

- `53/tcp`
- `53/udp`

São endpoints diferentes.

## Estado de uma porta

No Nmap, podemos encontrar estados como:

- **open** → existe um serviço aceitando conexões.
- **closed** → o dispositivo está acessível, mas não há serviço escutando naquela porta.
- **filtered** → algum filtro ou firewall impede determinar claramente o estado.

## Segurança

Uma porta aberta não significa automaticamente que existe uma vulnerabilidade.

É necessário analisar:

- O serviço
- A versão
- A configuração
- A autenticação
- A exposição do serviço

## Nmap

Exemplo de verificação:

`nmap 192.168.56.101`

Para tentar identificar versões dos serviços:

`nmap -sV 192.168.56.101`

> Os testes devem ser realizados somente em sistemas próprios ou ambientes autorizados.
