# ProjetoBloco-TP3-Edemir_Ferreira_Junior
### (Principais pontos do CMMI, nível de maturidade - 1 a 5)
##### Representações do Modelo CMMI

O CMMI possui duas representações: a estagiada e a contínua. A representação
estagiada permite que as organizações melhorem um conjunto de processos
interrelacionados e, de forma incremental, tratem sucessivos conjuntos de PAs. A
representação contínua, por sua vez, permite que as organizações melhorem de forma
incremental os processos correspondentes a uma ou mais PAs. A empresa seleciona
em que áreas de processo ela será avaliada. 

##### Representação por Estágios

Esta representação preocupa-se com os processos da organização como um
todo, oferecendo uma abordagem estruturada e sistemática para a melhoria de um
estágio por vez. Atingir um estágio significa que uma estrutura de processo adequada
foi estabelecida como base para o próximo estágio [SEI 2006].
 As áreas de processo (PAs) são organizadas por níveis de maturidade – do
nível “inicial” (nível 1) ao nível “em otimização” (nível 5) – que sugerem uma ordem
para a implementação das áreas de processo. Cada nível possui várias PAs, e por sua
vez, cada PA possui objetivos, práticas genéricas e específicas, assegurando assim uma
base de melhoria adequada para o próximo nível de maturidade.

Na representação por estágios, quando uma organização atinge as práticas necessárias para estar em um nível, significa que atinge todos os requisitos necessários dos níveis imediatamente anteriores conforme ilustrado na Figura abaixo:

![CMMI](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/CMMI.png)

##### A) Nível 1 - Inicial.

É o nível de maturidade CMMI mais baixo. Em geral, as organizações desse nível têm processos imprevisíveis que são pobremente controlados e reativos. Nestes nível de maturidade não há PAs, os processos são normalmente imprevisíveis e caóticos, e a organização geralmente não fornece um ambiente estável.


##### B) Nível 2 - Gerenciado.

Neste nível, os projetos da organização têm a garantia de que os requisitos são gerenciados, planejados, executados, medidos e controlados. Quando essas práticas são adequadas, os projetos são executados e controlados de acordo com o planejado. O Gerenciamento de Projetos é o foco principal deste nível.


##### C) Nível 3 - Definido.

Nível em que todos os objetivos específicos e genéricos atribuídos para os níveis de maturidade 2 e 3 foram alcançados, os processos são mais bem caracterizados e entendidos e são descritos em padrões, procedimentos, ferramentas e métodos. O Foco neste nível é a padronização do processo.


##### D) Nível 4 - Quantitavamente Gerenciado.

Neste quarto nível, os objetivos específicos e genéricos atribuídos para os níveis de maturidade 2, 3 e 4 foram alcançados e os processos são medidos e controlados. O foco neste nível é o gerenciamento quantitativo.


##### E) Nível 5 - Em Otimização.

É o nível mais alto de maturidade CMMI, onde uma organização atingi todos os objetivos específicos atribuídos para os níveis de maturidade 2, 3, 4 e 5. Os processos são continuamente aperfeiçoados, considerando que a variação de um processo esta relacionada às interações, entre seus componentes tendo como foco principal a melhoria contínua do processo.


### (Uso do modelo em cascata)

No modelo em cascata original de Royce, as seguintes fases são seguidas em perfeita ordem:

Requerimento
Projeto
Implementação
Integração
Teste e depuração (verificação)
Manutenção de software

![Waterfall](https://github.com/DevelopeJr/MeuPrimeiroRespositorio/blob/main/Waterfall.png)

Para seguir um modelo em cascata, o progresso de uma fase para a próxima se dá de uma forma puramente sequencial. Por exemplo, inicialmente completa-se a especificação de requisitos — elaborando um conjunto rígido de requisitos do software (Por exemplo, os requisitos para minha rede social (MercadoLivre e Clientes) 
devem permitir acesso através de Login e Senha, preenchimento de perfil do cliente, busca de produtos, chat para perguntas sobre o produto e campo para efetuar a compra, embora as especificações dos requisitos reais sejam mais detalhados, em um procedimento para projeto. Como o software sempre faz parte de um sistema (ou negócio) maior, o trabalho começa pelo estabelecimento de requisitos para todos os elementos do sistema e depois pela alocação de algum subconjunto desses requisitos para o software. Essa visão de sistema é essencial quando o software precisa interagir com outros elementos, tais como hardware, pessoas e bases de dados.

### (Problemas)

Entre os problemas às vezes encontrados quando se aplica o modelo cascata, temos:

1. Projetos reais raramente seguem o fluxo sequencial proposto pelo modelo. Embora o modelo linear possa conter iterações, ele o faz indiretamente. Como consequência, mudanças podem provocar confusão à medida que a equipe de projeto prossegue.

2. Frequentemente, é difícil para o cliente estabelecer explicitamente todas as necessidades. O modelo cascata exige isso e tem dificuldade para adequar a incerteza natural existente no início de muitos projetos.

3. O cliente deve ter paciência. Uma versão operacional do(s) programa(s) não estará disponível antes de estarmos próximos ao final do projeto. Um erro grave, se não detectado até o programa operacional ser revisto, pode ser desastroso.

Outro problema com essa abordagem é que, em geral, é fácil verificar se o código funciona direito, mas não é tão fácil verificar se os modelos e projetos estão bem escritos. Para ser efetivamente viável, esse tipo de ciclo de vida necessitaria de ferramentas de análise automatizada de diagramas e documentos para verificar sua exatidão, mas tais ferramentas ainda são bastante limitadas.

### (Requisitos de usuário)

Requisito de usuário são declarações, em uma linguagem natural somada a diagramas, dos serviços que se espera que o sistema forneça para os usuários e das limitações sob as quais ele deve operar. Esses requisitos podem variar de declarações amplas das características necessárias do sistema até descrições precisas e detalhadas da sua funcionalidade.

## 1. Requisitos funcionais

<center>


| Identificação | Requisito | Técnica utilizada |
| :--: |--|:--:|
| RF01 | Tela inicial intuitiva e de fácil utilização | Questionário |
| RF02 | Pops para cada item da página como orientação de uso | Questionário |
| RF03 | Campo de login do usuário  | Introspecção |
| RF04 | O usuário fornece e-mail, senha e confirmações  | Introspecção |
| RF05 | Os dados do usuário são validados, encriptados e persistidos pelo sistema  | Introspecção |
| RF06 | O sistema gera e envia um link, com prazo de expiração, para que o usuário confirme seu e-mail  | Introspecção |
| RF07 | O usuário confirma seu e-mail, clicando no link, antes do prazo de expiração  | Introspecção |
| RF08 | O sistema confirma que a conta do usuário foi criada com sucesso  | Introspecção |
| RF09 | O sistema redireciona o usuário para a página principal  | Introspecção |
| RF10 | O e-mail ou a senha do usuário não são válidos  | Introspecção |
| RF11 | O sistema exibe uma mensagem para o usuário  | Introspecção |
| RF12 | O usuário tenta confirmar o e-mail depois do prazo de expiração  | Introspecção |
| RF13 | O sistema sugere que o usuário realize um novo cadastro  | Introspecção |
| RF14 | Confirmação de e-mail e senha: o usuário deve fornecer os dados duas vezes para minimizar o risco de erro  | Introspecção |
| RF15 | Validação de e-mail: verificar se o e-mail está em um formato válido, se o e-mail já consta na base de dados  | Introspecção |
| RF16 | Validação de senha: verificar se a senha respeita os requisitos de segurança (Caractéres especiais, letras maiúsculas e minúsculas)   | Introspecção |
| RF17 | Sistema deve permitir postagem de produtos para venda ou compra | Introspecção |
| RF18 | Sistema deve permitir controle de estoque de produtos | Introspecção |
| RF19 | Sistema com chat p/ diálogo entre cliente/vendedor/fornecedor | Introspecção |
| RF20 | Campo para calculo de frete e acompanhamento do mesmo | Introspecção |
| RF21 | Permitir cancelamento de compra | Introspecção |
| RF22 | Permitir cancelamento de compra quando em trânsito para entrega | Introspecção |
| RF23 | Permitir troca de produto caso haja algum sinistro/produto errado/Motivos pessoais | Introspecção |
| RF24 | Poder trocar senha | Brainstorming |
| RF25 | Poder acessar site através de biometria/certificado digital/QRCode | Brainstorming |
| RF26 | Visualizar notificações de compra/venda/transferências/entrega de produto | Brainstorming |
| RF27 | Emitir boleto para pagamento de produto ou campo p/ pagto em cartão ou Bitcoin | Introspecção |
| RF28 | Ativar modo escuro | Brainstorming |
| RF29 | O sistema deve gerar nota fiscal eletrônica (NF-e) dos serviços prestados | Brainstorming |


<figcaption>Tabela 1: Listagem dos requisitos funcionais do tema MercadoLivre</figcaption>

</center>  


## 3. Requisitos não funcionais  


<center>

| Identificação | Requisito | Técnica utilizada |
| :--: |--|:--:|
| RNF01 | Apresentar as funcionalidades de uma forma mais visual | Questionário |
| RNF02 | Demonstrar como as funcionalidades acontecem | Questionário |
| RNF03 | Aumentar a acessibilidade para usuários com dificuldades | Questionário |
| RNF04 | Sistema ser enxuto | Introspecção |
| RNF05 | Sistema ser veloz | Introspecção |
| RNF06 | Sistema funcionar fora do Brasil | Introspecção |
| RNF07 | Tenha alguma forma de autenticação para utilizar o sistema, que garanta segurança | Introspecção |
| RNF08 | O aplicativo deverá rodar em qualquer plataforma mobile | Brainstorming |
| RNF09 | O aplicativo deverá manter os dados do usuário seguros | Brainstorming |
| RNF10 | O sistema deverá notificar o usuário sem falhas | Brainstorming |
| RNF11 | As funções do aplicativo não devem ser cansativas | Brainstorming |
| RNF12 | As notificações de status sobre andamento das operações devem ser instântaneas | Brainstorming |
| RNF13 | O aplicativo deverá ter um design intuitivo | Brainstorming |

<figcaption>Tabela 2: Listagem dos requisitos não funcionais do sistema MercadoLivre</figcaption>

</center>


## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 13/06/2021 | Elicitação dos requisitos | Júlio Cesar |
| 1.0.1 | 13/06/2021 | Revisão gramatical | E.F.Jr |
| 2.0 | 14/06/2021 | Uniformizando sub-títulos, centralizando tabelas e adicionando legendas | E.F.Jr |


# Requisitos Funcionais (RF)  

Definem as funcionalidades do sistema.  
  
Basicamente, especifícam o que o sistema deve fazer. Sem a implementação desses requisitos, o sistema não funciona como deveria-se chegar a funcionar.  

De acordo com a Wikipedia:  

"Requisitos Funcionais podem ser cálculos, detalhes técnicos, manipulação de dados e de processamento e outras funcionalidades específicas que definem o que um sistema, idealmente, será capaz de realizar."

# Requisitos Não-Funcionais (RNF)  

Indicam características de qualidade que o sistema deve possuir e que estão relacionadas às funcionalidades previstas.

Algumas dessas características são:

* Desempenho
* Confiabilidade
* Escalabilidade
* Portabilidade
* Usabilidade
* Segurança  

Os critérios que qualificam os requisitos não-funcionais são geralmente mensuráveis.


