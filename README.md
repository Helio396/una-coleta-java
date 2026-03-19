Olá meu nome é Hélio dos Santos Mendonça

Estou começando a todo vapor na programação e tentando aprender com meus erros e me adaptar
aos cenários que vou enfrentar. Abaixo você encontra a documentação dos meus projetos deste 
repositório:


# una-coleta-java

#Descrição

Criei um programa que faz perguntas pro usuário como nome, idade terrestre, altura para saber se
o usuário está apito para a missão

#Fluxograma

flowchart TD

A[Início] --> B[Instanciar Scanner]
B --> C[Exibir mensagem de boas-vindas]

C --> D[Solicitar nome]
D --> E[Ler nome]

E --> F[Solicitar idade]
F --> G[Ler idade]

G --> H[Solicitar altura]
H --> I[Ler altura]

I --> J[Solicitar experiência com drones]
J --> K[Ler experiência]

K --> L[Exibir relatório com dados]

L --> M{Idade >= 18 e <= 45?}

M -->|Sim| N[Status: Apto para testes físicos]
M -->|Não| O[Status: Idade fora dos parâmetros]

N --> P[Fechar Scanner]
O --> P

P --> Q[Fim]
