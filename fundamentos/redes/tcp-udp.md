# 🌐 TCP e UDP

TCP e UDP são protocolos utilizados para comunicação em redes.

## 🔵 TCP

TCP significa Transmission Control Protocol.

Ele é orientado à conexão e busca garantir que os dados sejam entregues de forma confiável e na ordem correta.

### Características

- Orientado à conexão
- Confirmação e controle de entrega
- Mantém a ordem dos dados
- Possui maior overhead que UDP

### Exemplos

- HTTP/HTTPS
- SSH
- FTP

---

## 🟢 UDP

UDP significa User Datagram Protocol.

Ele não estabelece uma conexão da mesma forma que o TCP e possui menos overhead, sendo útil quando baixa latência é importante.

### Características

- Sem conexão
- Menor overhead
- Não garante a entrega dos pacotes
- Pode ser usado em aplicações que priorizam velocidade

### Exemplos

- DNS
- Streaming
- Jogos online
- Comunicação em tempo real

---

## ⚔️ TCP vs UDP

| Característica | TCP | UDP |
|---|---|---|
| Conexão | Orientado à conexão | Sem conexão |
| Confiabilidade | Maior | Menor |
| Ordem dos dados | Mantida | Não garantida |
| Overhead | Maior | Menor |
| Exemplo | HTTPS, SSH | DNS, aplicações em tempo real |

## 🔐 Segurança

TCP e UDP são fundamentais para entender como os dispositivos se comunicam em uma rede.

A existência de uma porta TCP ou UDP aberta não significa, por si só, que existe uma vulnerabilidade. É necessário analisar o serviço, sua configuração e outros fatores.

Testes de segurança devem ser realizados somente em sistemas próprios ou com autorização.
