# Aula-2---Sistem.Distri

Este repositório tem como objetivo documentar as atividades práticas e reflexões propostas na disciplina de Sistemas Distribuídos, servindo como registro de aprendizado e evidência das práticas realizadas em laboratório. Sinta-se à vontade para explorar os arquivos e acompanhar a evolução dos conceitos ao longo do semestre.

# O que foi proposto em aula
A segunda aula teve como foco apresentar as Arquiteturas e Organização dos Sistemas Distribuídos, mostrando como os componentes de um sistema podem ser organizados e como eles interagem. A arquitetura ajuda a responder questões como:

Quem solicita o serviço?
Quem processa a solicitação?
Onde os dados estão armazenados?
Como os componentes se comunicam?
O processamento está concentrado ou distribuído?

Foram estudadas principalmente três arquiteturas:
Cliente-Servidor
Peer-to-Peer (P2P)
Arquiteturas em múltiplas camadas

# Atividade Prática — Construindo uma Comunicação Cliente-Servidor
Na aula anterior utilizamos um navegador como cliente. Hoje vamos criar os dois lados da comunicação usando Sockets em Python.

O que é um Socket? É um mecanismo utilizado para permitir a comunicação entre processos através da rede. Nesta atividade utilizaremos TCP/IP + Python.

Para realizar as atividades praticas é necessário ter o Python Instalado na maquina como também uma IDE (Ex.: VSCode, PyCharm)

Na v1.0 (Client e Servidor) temos o que foi prosto em aula... Para executar basta copiar e colocar na IDE (Claro que há outras formas de fazer como pelo bloco de notas, no entanto não recomendo) e iniciar o arquivo, 1º Inicie o Servidor e Depois o Client
Nessa primeira versão também foi prosto um erro forçado (v1.0 Erro forçado) para vermos quais seriam os possiveis erros de não executar da forma correta, e o erro foi que se não iniciarmos o servidor primeiro o client não pode fazer uma conexão

Na v1.1 foi proposto alterar a mensagem pré-carregado por uma que o client enviaria a forma de executar e a mesma, no entanto agora no terminal vai aparecer para o client escrever uma mensagem que chegara para o lado do Server
Obs: Troquei Servidor por Server para padronizar a nomenclatura.
