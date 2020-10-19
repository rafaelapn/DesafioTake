# DesafioTake

Primeiramente, obrigado pela oportunidade, foi muito divertido relembrar conceitos e voltar a desenvolver.

## Chat Desktop - Versão 1.0
> Sistema desenvolvido para o processo de seleção para vaga na empresa Take Blip

O Sistema de Chat foi desenvolvido em Java, utilizando Sockets para a comunicação entre o Servidor e Clientes.

## Instalação

O programa ficou desenvolvido para rodar diretamente em uma IDE. Este foi desenvolvido no Eclipse:
Version: 2020-09 (4.17.0)
Build id: 20200910-1200

```shell
DesafioTake.zip
```
Baixe o .zip e abra o source no Eclipe, como New Java Project.

## Pacotes e Classes do programa

O sistema foi desenvolvido em 2 Pacotes:

```shell
package Cliente;
class Cliente.java
class TrataMsgCliente.java
class TesteDoCliente.java /JUnit

package Servidor;
class Servidor.java
class RecebeMsgServidor.java
class TesteDoServidor.java /JUnit
```

### Descrição das Classes

package Cliente;
  class Cliente.java
    Classe que é responsável pela iniciação do cliente e conexão com o servidor de chat.
    Se executar várias vezes, será possível conectar múltiplos clientes ao mesmo servidor.
  class TrataMsgCliente.java
    Classe de Tratamento de Mensagens do cliente.
    Classe de tratamento de mensagens provenientes dos clientes/usuários do chat.
  class TesteDoCliente.java /JUnit
    Classe de teste unitário da classe @Cliente

package Servidor;
  class Servidor.java
    Inicia o servidor via conexão Socket nativo.
    Setando uma porta padrão 12345 para o servidor, somente como didática.
    Limite de tempo do servidor aberto = long de 1536259 == 25:36:259.
  class RecebeMsgServidor.java
    Classe de recebimento de mensagens do server
    Classe de tratamento de mensagens provenientes do servidor.
  class TesteDoServidor.java /JUnit
    Classe de validação unitária da Classe @Servidor

## Repositório

O repositório utilizado para o projeto foi o Git.
E criado acesso e uma release no GitHub rafaelapn/DesafioTake.

## Referências para o trabalho

Como trabalho pessoal, para fins específicos, foram utilizadas referências e exemplos de alguns sites importantes de coding, conforme abaixo.

- https://www.caelum.com.br/apostila-java-orientacao-objetos/
- https://stackoverflow.com/questions/
- https://www.devmedia.com.br/forum/
- https://www.guj.com.br/

## Licença

GNU. Trabalho feito para fins específicos e de avaliação específica para a empresa Take Blip, para processo seletivo.
De não comercialização.
