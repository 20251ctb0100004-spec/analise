# Esteira da Análise — BiblioTech

**Estudante:** ARTUR LACERDA DA SILVA

## Funcionalidade 0 (molde):
-- **0.1 Fala do cliente:** "Quando o aluno traz o livro de volta, eu preciso dar baixa na hora, senão fica parecendo que ele ainda está com o livro."
-- **0.2 História de usuário:** "Como leitor, quero devolver um livro emprestado para não ficar com pendências e poder pegar outros."
-- **0.3 Item da lista:** RF04 — O sistema deve permitir o registro da devolução de um livro emprestado.
-- **0.4 Caso de uso:** Ator Bibliotecário → caso de uso "Devolver livro".


## Funcionalidade 1: Reserva de Livro

- **1.1 Fala do cliente:** "Às vezes o livro que o aluno quer já está emprestado, então preciso deixar uma fila de espera gravada para quando o livro retornar."
- **1.2 História de usuário:** Como leitor, quero reservar um livro que está indisponível, para garantir minha vez de retirá-lo assim que for devolvido.
- **1.3 Requisito:** RF01 — O sistema deve permitir a reserva de um livro que esteja atualmente emprestado.
- **1.4 Caso de uso (RF01):** Ator Leitor → "Reservar livro" (verbo + objeto)

## Funcionalidade 2: Emprestimo do Livro

- **2.1 Fala do cliente:** Preciso registrar quando entrego um livro para um aluno, definindo a data de devolução para poder controlar quem está com cada obra.
- **2.2 História de usuário:** Como leitor, quero retirar um livro emprestado, para realizar minhas consultas e leituras de estudo.
- **2.3 Requisito:** RF02 — O sistema deve permitir o registro do empréstimo de um livro para um leitor cadastrado
- **2.4 Caso de uso (RF02):** Ator Leitor → "Emprestar livro" (verbo + objeto)

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala |
|---|---|---|
| emprestar Livro | RF02 | "Preciso registrar quando entrego um livro para um aluno, definindo a data de devolução para poder controlar quem está com cada obra." |
| Reservar Livro | RF01 | "Às vezes o livro que o aluno quer já está emprestado, então preciso deixar uma fila de espera gravada para quando o livro retornar." |

<!-- Nível A: conte o caminho completo de cada funcionalidade,
     da fala do cliente até o que está desenhado no diagrama. -->

## Relacionamento entre casos de uso (nível A)

- Tipo: «include» 
- Entre: "Emprestar livro" e "Buscar livro"
- Por que é esse e não o outro: Foi utilizado o relacionamento «include» porque o processo de busca do acervo é uma etapa obrigatória e indispensável para a execução do empréstimo. Não é possível realizar um empréstimo sem antes consultar e identificar a disponibilidade do livro no sistema.

## Autoavaliação

**Conceito pretendido:** A (A / B / C)

- Conversei sobre esta atividade com: bruno e theo
- Esteira da análise: Completa nas 4 estações para as duas funcionalidades selecionadas (Empréstimo e Reserva).  
- Diagrama e notação: Construído no draw.io contendo fronteira do sistema "BiblioTech", atores externos, casos de uso na forma Verbo + Objeto e relacionamento de inclusão («include»).  
- Rastreabilidade: Mapeada integralmente da fala do cliente até a elipse representada no diagrama.  
- Organização da entrega: Todos os arquivos nomeados corretamente em minúsculas e estruturados na pasta Atividade-17/ dentro da raiz do repositório.