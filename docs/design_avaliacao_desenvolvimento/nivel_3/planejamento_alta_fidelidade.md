# Planejamento da Avaliação do Protótipo de Alta Fidelidade

## Introdução

O presente artefato apresenta o planejamento da avaliação do protótipo de alta fidelidade elaborado para a aplicação web lichess. O planejamento baseia-se nas atividades propostas pelo _framework_ DECIDE, a saber:

- D: Determinar os objetivos da avaliação;
- E: Explorar perguntas a serem respondidas com a avaliação
- C: Escolher os métodos de avaliação a serem utilizados
- I: Identificar e administrar as questões práticas da avaliação
- D: Decidir como lidar com as questões éticas
- E: Avaliar, interpretar e apresentar os dados

## Objetivos

A avaliação do protótipo de alta fidelidade tem como principal objetivo identificar problemas na interação e interface. As perguntas[1] que devem ser respondidas com a avaliação são:

- O usuário consegue realizar as tarefas no sistema?
- O usuário consegue atingir o objetivo das tarefas? Com qual eficiência? Em quanto tempo? Após cometer quantos erros?
- Qual parte da interface e da interação o deixa insatisfeito?
- O usuário entende o que significa e para que serve cada elemento de interface?
- O usuário entende o que deve fazer nas etapas das tarefas?
- Quais problemas de IHC dificultam ou impedem o usuário de alcançar seus objetivos? Onde eles se manifestam? Com qual frequência ocorrem? Qual a gravidade deles?
- Quais barreiras o usuário encontra para atingir seus objetivos?

## Metodologia

A avaliação será feita em laboratório, em um ambiente controlado, pois esse tipo de avaliação fornece um maior controle sobre as interferências do ambiente na interação usuário-sistema e facilita o registro dos dados [1]. A avaliação será um **teste de usabilidade**, que utiliza o método de observação para fazer a avaliação.

## Questões práticas

A preparação para a avaliação consiste em:

- Definir tarefas para os participantes executarem
- Definir o perfil dos participantes e recrutá-los
- Preparar material para observar e registrar o teste
- Executar um teste piloto

As seguintes subseções apresentam o planejamento prático das atividades.

Antes de iniciar a coleta de dados, o avaliador deve preparar o material de apoio, que consiste nos seguintes documentos:

- Termo de consentimento (duas vias, uma para o avaliador e uma para o participante)
- Especificação das tarefas e orientações para o usuário (apenas uma via)

### Recrutamento dos participantes

De acordo com Krug, um teste feito com 3 ou 4 participantes é suficiente para detectar a maioria dos problemas [3], e essa quantidade possibilita fazer a análise no mesmo dia. Em decorrência do curto período de tempo disponível para fazer a avaliação, foi definido que a avaliação será feita com 3 participantes. Por meio do [perfil de usuário](../../analise_requisitos/perfil_usuario.md) foi possível traçar um desenho sobre os grupos que compõem a maior parte de usuários da plataforma, e tendo em vista esse perfil, escolheu-se recrutar três estudantes universitários, na faixa etária de 20 a 25 anos e jogadores de xadrez competitivo. A busca por usuários foi feita em grupos de xadrez com estudantes da Universidade de Brasília.

### Cronograma da avaliação

A Tabela 1 detalha as atividades da avaliação.

| Data e horário | Atividade | Autor(es) | Revisor(es) |
| :-: | - | - | - |
| 18/01/2023 até as 23:00 | Entrega do protótipo de alta fidelidade | Lucas Macedo | Maurício |
| 19/01/2023 às 12:00 | Aplicação do teste piloto | Davi e Nicolas | Maurício |
| 19/01/2023 até às 23:00 | Ajustes necessários antes da avaliação do protótipo | Nicolas | Lucas Macedo |
| 20/01/2023 às 10:00 | Aplicação da avaliação do protótipo de alta fidelidade | Nicolas | Lucas Gabriel |
| 22/01/2023 até 23:00 | Entrega do relato de resultados da avaliação do protótipo de alta fidelidade | Nicolas | Lucas Gabriel |

<div style="text-align: center">
<p>
Tabela 1: Cronograma da Avaliação. (Fonte: autor, 2023)
</p>
</div>

### Papéis dos Avaliadores

Durante a entrevista, um membro do grupo exercerá o papel de avaliador. Ele ficará responsável por observar os comportamentos, comunicação não verbal e respostas do entrevistado, enquanto conduz a entrevista.

### Ferramentas

A entrevista será realizada na plataforma Microsoft Teams, para que seja possível gravar o encontro. Os avaliadores e entrevistado podem também utilizar papel e caneta para fazer registros durante a entrevista.

### Teste piloto

Antes da execução da entrevista, será realizado um teste piloto. O teste piloto consistirá na execução da avaliação com um integrante do grupo, para avaliar o tempo gasto, o funcionamento correto dos equipamentos e do protótipo e a qualidade da gravação.

## Questões Éticas

No caso de avaliações que envolvem participantes, é necessário colher o consentimento dos participantes, a partir do termo de consentimento livre e esclarecido, de acordo com os [aspectos éticos](../../analise_requisitos/aspectos_eticos.md) definidos para o projeto.

## Relato de Resultados

A avaliação, interpretação e apresentação dos dados será feita por meio do relato de resultados, de acordo com o [planejamento](../nivel_1/planejamento_do_relato_de_resultados.md) realizado.

O relato deve conter:

- Os objetivos e escopo da avaliação;
- Uma breve descrição do método de teste de usabilidade;
- O número e o perfil dos avaliadores e dos participantes;
- As tarefas executadas pelos participantes;
- Tabelas e gráficos que sumarizam as medições realizadas;
- Uma lista de problemas encontrados, indicando para cada problema:
  - local onde ocorreu;
  - descrição e justificativa;
  - discussão, indicando os fatores de usabilidade prejudicados;
  - sugestões de solução.

## Material de Apoio

### Termo de Consentimento livre e esclarecido

Antes de iniciar a avaliação, o avaliador deve apresentar o termo de consentimento ao entrevistado e verificar se ele consente em participar da pesquisa e com a gravação da entrevista.

<div style="text-align: center">
<h3>
Termo de Consentimento Livre e Esclarecido
</h3>
</div>
------
Somos uma equipe da disciplina de Interação Humano Computador, que está realizando uma avaliação do sistema Lichess, um sítio da internet que tem como foco a prática de xadrez online, os resultados desse projeto podem ser observados através deste [link](https://interacao-humano-computador.github.io/2022.2-Lichess/). Nessa etapa do projeto, queremos realizar testes com protótipos de alta fidelidade para conhecer o que algumas das pessoas que usariam o sistema pensam a respeito de suas características e funcionamento. Estamos realizando uma série de pesquisas, e solicitamos seu consentimento para a realização de um teste de usabilidade com duração aproximada de 30 minutos. Para decidir sobre o seu consentimento, é importante que você conheça as seguintes informações sobre a pesquisa:

- Os dados coletados durante o questionário destinam-se estritamente a atividades de análise e elaboração de melhorias para o sistema Lichess.
- Nossa equipe tem o compromisso de divulgar os resultados de nossas pesquisas para o cliente.
- O consentimento para a participação do teste de usabilidade é uma escolha livre, feita mediante a prestação de todos os esclarecimentos necessários sobre a pesquisa.
- O teste de usabilidade pode ser interrompido a qualquer momento, segundo a sua disponibilidade e vontade.
- Será necessário gravar a sessão de teste, e as gravações efetuadas serão divulgadas nos resultados do projeto.

Diante das explicações você acha que está suficientemente informado(a) a respeito da pesquisa que será realizada e concorda de livre e espontânea vontade em participar, como colaborador?
Caso o participante seja menor de idade é necessária a permissão do responsável legal.

\(  \) Sim

\(  \) Não

-----

### Protótipo de Alta Fidelidade

Antes de iniciar a avaliação, o avaliador deve deixar claro para o usuário o que é o protótipo, podendo utilizar o texto abaixo como contextualização.

Um protótipo de alta fidelidade apresenta elementos e materiais que serão encontrados na versão final de um produto, assemelhando-se bastante ao produto final. A utilização de protótipos facilita a comunicação entre os membros da equipe e os _stakeholders_, além de auxiliar a equipe de desenvolvimento a tomar decisões de design.

A utilização de protótipos de alta fidelidade apresenta vantagens e desvantagens, dentre as vantagens ressaltam-se a interatividade completa do usuário com o protótipo, o uso conduzido pelo usuário e as mesmas aparências e interações do produto final. Em contrapartida, a elaboração de protótipos de alta fidelidade tem um custo maior, demanda mais tempo e não serve para coletas de requisitos. Ou seja, a prototipação de alta fidelidade deve ser aplicada nas etapas mais avançadas do design, pois não serve para coleta de requisitos.

### Roteiro de Tarefas

O usuário deverá executar as seguintes tarefas no protótipo de alta fidelidade:

- Iniciar uma partida de xadrez;
- Acessar um tutorial de xadrez;

O avaliador deverá apresentar para o usuário o caminho que ele deverá executar dentro do sistema para realizar as tarefas e os dados que deverão ser inseridos nos campos, caso necessário fazer alguma inserção.

## Bibliografia

[1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

[2] PREECE, J. Design de Interação: Além da interação homem-computador. Editora Bookman, 2013.

[3] Avaliação E Projeto No Design De Interfaces Capa comum – 1 janeiro 2010. Edição Português por José Guilherme Santa Rosa (Autor).

## Histórico de Versão

| Versão | Data  | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ----- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 10/01/2023  | Criação da versão inicial do artefato.|  Nicolas Souza | Davi Silva |
