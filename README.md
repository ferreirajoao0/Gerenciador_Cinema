# Gerenciador_Cinema
Gerenciador de Cinema em Java
Projeto desenvolvido para simular o gerenciamento completo de salas de cinema, contemplando o cadastro de salas, mapeamento visual de assentos, controle de reservas e emissão de ingressos com relatórios financeiros.

O objetivo principal deste projeto foi aplicar na prática conceitos fundamentais de Programação Orientada a Objetos (POO), estruturas de dados com matrizes bidimensionais e princípios de código limpo (Clean Code).

Funcionalidades
Gerenciamento de Salas: Cadastro de salas com dimensões customizáveis de linhas e colunas.

Mapeamento de Assentos: Criação automática de matrizes bidimensionais de assentos, categorizando fileiras entre NORMAL e VIP.

Mapa Visual no Terminal: Exibição do layout da sala no console, indicando assentos livres ([L]) e ocupados ([X]).

Busca e Conversão de Coordenadas: Identificação de assentos através da conversão de caracteres da tabela ASCII (ex: linha 'A', coluna 1).

Controle de Vendas: Validação de assentos e reserva em tempo real sem sobreposição de ingressos.

Métricas e Financeiro: Cálculo da porcentagem de ocupação das salas e emissão de relatório financeiro com o faturamento total das vendas.

Tecnologias e Conceitos Utilizados
Linguagem: Java (JDK 17+)

Paradigmas: Programação Orientada a Objetos (Encapsulamento, Abstração e Composição)

Estrutura de Dados: Arrays unidimensionais e Matrizes bidimensionais (Assento[][])

Boas Práticas: Separação de responsabilidades, nomes descritivos de métodos e legibilidade do código

Estrutura do Projeto
GerenciadoCinema.java: Classe principal responsável pelo controle geral das salas, vendas de ingressos e relatórios.

Sala.java: Responsável por gerenciar a matriz de assentos, exibição do mapa visual e cálculo de ocupação.

Assento.java: Representa a unidade do assento, armazenando posição, tipo (VIP/NORMAL) e status de ocupação.

Ingresso.java: Representa a venda realizada, associando o cliente ao assento reservado.
