#Gerenciador de Cinema em Java
Uma aplicação desenvolvida em Java para simular a gestão de salas de cinema, mapeamento de assentos, controle de reservas e emissão de relatórios financeiros via terminal.

📌 Funcionalidades
Cadastro de Salas: Criação de salas com dimensões personalizadas de linhas e colunas.

Mapa de Assentos: Matriz bidimensional categorizando assentos automaticamente entre NORMAL e VIP.

Visualização Visual: Exibição do estado da sala no console usando [L] para livre e [X] para ocupado.

Reserva de Ingressos: Conversão de coordenadas (linha em letra e coluna em número) com validação contra ocupação dupla.

Métricas e Financeiro: Cálculo da taxa de ocupação da sala e faturamento total acumulado das vendas.

🛠️ Conceitos & Boas Práticas Aplicados
Encapsulamento (POO): Atributos das classes protegidos e manipulados por métodos com responsabilidades bem definidas.

Matrizes Bidimensionais: Estrutura de dados utilizada para renderizar e gerenciar as coordenadas da sala em tempo real.

Conversão de Dados: Manipulação da tabela ASCII para transformar entradas do tipo char em índices numéricos da matriz.

Separação de Responsabilidades: Classes organizadas para dividir as regras de negócio do cinema, da sala, do assento e do ingresso.

📂 Estrutura do Projeto
Plaintext
src/
└── gerenciador/cinema/
    ├── GerenciadoCinema.java  # Controle geral das salas, vendas e relatórios
    ├── Sala.java              # Gestão da matriz de assentos e mapa visual
    ├── Assento.java           # Estado, posição e tipo do assento
    └── Ingresso.java          # Registro da venda e associação com o cliente
