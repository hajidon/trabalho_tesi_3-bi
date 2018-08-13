# Documentação de Funcionalidades
Quem?

* Pessoas que gostem de novas aplicações e tenham curiosidade na area de eletrônica 

#### O que?

* Este é um aplicativo que tem por função ligar um led atravez de um aplicativo mobile

Por que?

# Funcionalidades
### Enviar comandos para o Arduino:
    SENDO o botão de ligar apertado
    POSSO enviar comandos para o Arduino
    PARA acender o led
 
 #### Cenário 1: atuar com sucesso (led acendeu/desligou)
    Dado que a activity do painel esteja aberta
    Quando aperto o botão o led liga/desliga
    Então o sistema transmite comandos ao Arduino
    E o equipamento recebe as informações dos comandos
    E o led desliga/liga
    
 
### Enviar comandos para o Firebase:
    SENDO o botão de ligar/desligar apertado
    POSSO enviar comandos para o Firebase
    PARA armazenar o histórico

#### Cenário 1: atuar com sucesso (armazenou o histórico)
    Dado que a activity do painel esteja aberta
    Quando aperto o botão o led liga/desliga
    Então o sistema transmite as informações ao firebase
    E firebase armazena na base de dados
    
#### Cenário 2: falha na atuação (não armazenou o histórico)
 
