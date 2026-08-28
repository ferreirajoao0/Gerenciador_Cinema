# Gerenciador de Cinema em Java
Sistema desenvolvido para gerenciar salas de cinema, mapear assentos em tempo real, controlar vendas de ingressos e gerar relatórios financeiros.

Funcionalidades
Gerenciamento de Salas: Cadastro de salas com dimensões personalizadas.

Mapa de Assentos: Matriz bidimensional com divisão entre assentos NORMAL e VIP.

Visualização no Terminal: Exibição do estado da sala usando [L] para livre e [X] para ocupado.

Reserva de Ingressos: Conversão de coordenadas (ex: linha 'A', coluna 1) e validação de assentos ocupados.

Relatório Financeiro: Cálculo da taxa de ocupação da sala e faturamento total das vendas.

Tecnologias e Conceitos
Linguagem: Java (JDK 17+)

POO: Encapsulamento, Abstração e Composição

Estrutura de Dados: Arrays e Matrizes bidimensionais

Boas Práticas: Clean Code e separação de responsabilidades

Estrutura do Projeto
GerenciadoCinema.java: Controle geral das salas, vendas e relatórios.

Sala.java: Gestão da matriz de assentos, mapa visual e métricas.

Assento.java: Estado, posição e tipo do assento.

Ingresso.java: Registro da venda e associação com o cliente.
