


# ProjetoBloco-TP3-Edemir_Ferreira_Junior
### Professor: Júlio Cesar   
# Plataforma de comercio de produtos diversos MercadoLivre
### Objetivo do documento  
#### O documento presente, tem como papel fundamental, elucidar sobre os objetivos da plataforma MercadoLivre, onde a proposta da mesma é o livre mercado, que pode ser trabalhado sem a necessidade de obter os custos de uma loja física. Nesta plataforma, é possível fazer controle de entrada e saída de produto, histórico de 6 meses com relação a produtos negociado salvo os que temos oferecido garantia de 1 ano além da garantia de fábrica.   
#### É possível fazer emissão de Nota Fiscal, controle de envio de mercadorias.     

### Escopo do projeto  
#### Um sistema simples com objetivo de ligar pessoas que tenham interesse de comprar e vender sem sair de casa, um meio prático para ambas as partes e que nos az ter mais tempo para exercer outras atividades sociais.  



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

# Usuários

| Atores: |
|---------|  
* Usuário: Pessoa Física ou Jurídica  
    * Sistema: Compra e venda de produtos diversos.  
    
| Pré-condições: |  
|----------------|  
* Criar perfil obrigatório para acessar sistema.  

| Fluxo básico: |  
|---------------|
* O usuário fornece e-mail, senha e confirmações
    * Os dados do usuário são validados, encriptados e persistidos pelo sistema.  
    O sistema gera e envia um link, com prazo de expiração, para que o usuário confirme seu e-mail
    O usuário confirma seu e-mail, clicando no link, antes do prazo de expiração
    O sistema confirma que a conta do usuário foi criada com sucesso
    O sistema redireciona o usuário para a página principal  

| Fluxo alternativo: |  
|--------------------|  
* O e-mail ou a senha do usuário não são válidos  
    * O sistema exibe uma mensagem para o usuário e retorna para refazer login

        O usuário tenta confirmar o e-mail depois do prazo de expiração e recebe um erro pedindo para refazer processo anterior.

        O sistema sugere que o usuário realize verificação dos dados ou informa que os dados não fazem parte de nenhum cadastro e oferece link para cadastro.

| Dados: |  
|--------|  
Nome Fantasia: Texto, máximo de 150 caracteres, não pode conter números.
Nome completo do usuário: Texto, máximo de 100 caracteres, não pode conter números
CPF do usuário: Apenas números
Data de nascimento: Somente maiores de 18 anos
E-mail: Texto, máximo de 40 caracteres
CNPJ da empresa: Máximo de 15 caracteres, só pode conter números
Endereço: Logradouro, número, complemento, bairro, cidade e estado.
Senha: Mais de 8 caracteres 



| Regras de validação: |  
|----------------------|  
* Confirmação de e-mail e senha: o usuário deve fornecer os dados duas vezes para minimizar o risco de erro
Validação de e-mail: verificar se o e-mail está em um formato válido, se o e-mail já consta na base de dados
Validação de senha: verificar se a senha respeita os requisitos de segurança como:  
(Uso de caractéres Maiúsculos e Minúsculos e caractéres especiais e números)  

# Produtos  

| Atores: |
|---------|  
* Usuário: Pessoa Física ou Jurídica  

| Pré-condições: |  
|----------------|  
Possuir cadastro na plataforma do sistema  

| Fluxo Básico: |  
|---------------|
* Usuário seleciona o campo de adicionar produtos  
    * Informe título/nome do produto  
    * Informe categoria do produto  
    * Informe Preço  
    * Insira foto do produto .jpeg  
    * Insira localização do produto  

| Fluxo alternativo: |  
|--------------------|  
* Os dados do produto não conferem  
    * Nome do produto com categoria diferente  
    * Preço inválido  
    * Foto do produto em formato inválido  
    * Não inseriu localização do produto (Obrigatório) 

| Dados: |  
|--------|  
Nome Produto: Texto, máximo de 150 caracteres, não pode conter números.
Quantidade: Apenas números
Data de fabricação: Somente números
Marca: Texto, máximo de 40 caracteres

| Regras de validação: |  
|----------------------|  
* Confirmar sobre o produto adicionado  
    * Nome do produto esta correto?  
    * Preço esta correto?  
    * Foto do produto esta correta?
    * Inseriu localização do produto?

## Matriz de Rastreabilidade

EAS - Equipe de arquitetura de software

|ID|Nome|Solicitante|Complexidade|Prioridade|Requisito Relacionado|Status|
|:-:|:--:|:--------:|:----------:|:--------:|:-------------------:|:----:|
|Usuário|CRUD Vendedores/Compradores|MercadoLivre|Baixa|Média|n/a|Concluído|
|Produto|CRUD Produtos|MercadoLivre|Média|Média|n/a|Concluído|  

## Referências

Perguntas frequentes, acesse: https://www.mercadolivre.com.br/ajuda/vendendo_643  




