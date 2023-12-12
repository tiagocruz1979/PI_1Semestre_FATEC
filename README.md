# DSM01-PI1S #
## Projeto Interdisciplinar das disciplina: Engenharia de Software I / Desenvolvimento Web I / Design Digital ##

**Integrantes:**
Fabrício Rangel de Sousa
Murillo Torres Lopes
Tiago Cruz Moraes
***

### Desenvolvimento ###

1. Introdução

**Propósito (ou Finalidade)**

Este documento apresenta a modelagem do sistema Tecnologia da Alta Mogiana. O público alvo deste documento inclui  pessoas envolvidas com o desenvolvimento (analistas de sistemas e programadores), testes do sistema e avaliadores do projeto.

**Escopo**

O Documento de Modelagem de Sistema provê uma visão completa dos modelos do sistema Tecnologia da Alta Mogiana. Ele é produzido e utilizado pelos desenvolvedores da equipe para documentar os requisitos, modelos e arquitetura do sistema.

**Benefícios esperados**

*Espera-se que o público frequentador do site fique melhor informado sobre as tecnologias relevantes ao mercado da região da alta mogiana.
*Que o site possibilite a geração de negócios entre empresas interessadas no mercado da região.

**Modelo Canvas**

![Modelo de Negócio Canvas - Tecnologia da Alta Mogiana](https://user-images.githubusercontent.com/79008813/119232191-a81d1280-bafa-11eb-9f03-620c7c3ba33f.PNG)

2. Especificação dos Requisitos

**Requisitos Funcionais**

Número | Descrição do Requisito Funcional
--- | ---
RF01 | O site usará a seguinte paleta de cores: #4D9470 #69E0A4 #2F5994 #538EE0.
RF02 | O site deverá permitir que os leitores comentem as materias publicadas.
RF03 | A página principal (home) deverá exibir sempre as últimas notícias publicadas, havendo transição automática entre elas.
RF04 | O site terá um campo de formulário para interatividade com os leitores com a finalidade de receber sugestão de materias / pautas, críticas, sugestões, elogios, intenção de postagem patrocinada.
RF05 | O *header* e o *footer* são padronizados e iguais para todas as páginas criadas internamente.
RF06 | O site deverá ser responsivo para dispositivos moveis (mínimo para tablets, celulares e telas windescreen(16:9))
RF07 | Lateralmente a direita o site deverá contar com *aside* para publicações externas e monetizadas.
RF08 | No *header* deverá constar menu por tema, lupa de pesquisa por palavra chave das publicações, "formulário" para assinatura de *newsletter*.
RF09 | No *footer* deve constar links para as redes sociais, meios de contato, institucional (quem somos; a alta mogiana).


**Requisitos Não Funcionais**

Número | Descrição do Requisito Não Funcional
--- | ---
RNF01 | O acesso administrativo da hospedagem deve ser realizado apenas por pessoas autorizadas
RNF02 | O site será escrito em HTML5 e CSS3
RNF03 | O site não deverá permanecer mais que 5h *offline*
RNF04 | As páginas devem ser carregadas em até 6s
RNF05 | A responsividade da página deverá atender telas de 600, 800 e 1020 de *width*.


**Regra de Negócio**

Número | Descrição da Regra de Negócio
--- | ---
RN01 | Noticias serão avaliadas pelos editores quando o conteúdo vier de fora.
RN02 | Só divulgaremos notícias relevantes a região da Alta Mogiana.
RN03 | As notícias terão foco em técnologia, independente do tipo.
RN04 | A linguagem usada será técnica, atingindo especificamente ao público alvo.
RN05 | Empresas poderão solicitar divulgação de suas atividades como postagem no site e em troca será exigido um valor, à definir, para manutenção e remuneração de seus criadores.
RN06 | Os conteúdo publicados acompanharão as tendências tecnológicas do mercado.
RN07 | As postagens patrocinadas só serão veiculadas após confirmação de pagamento.
RN08 | Os valores de postagens patrocinadas seguirão uma tabela de valores, variando o custo conforme tempo de exposição.
RN09 | A visualização do site será impulsionado por divulgação via redes sociais e por *newsletter*.
RN10 | As postagens passarão por revisão gramatical, feito por um profissional da área, antes de serem publicadas.
RN11 | Para as postangens, usaremos fontes externas que estejam em acordo com o propósito do site.


#### Descrição de Requisito Funcional ####

***
**RF01 - Paleta de cores** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [ ] Altíssima
- [x] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** O site usará a seguinte paleta de cores: #4D9470 #69E0A4 #2F5994 #538EE0.

**Requisitos Não Funcionais**

**Nome: RNF1.1 Acessibilidade**

**Restrição:** O site não deverá usar cores que confundam daltônicos.

**Categoria:** Interface

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório

**Nome: RNF1.2 Identidade Visual**

**Restrição:** As cores terão restrição quando a mudanças não autorizadas pela equipe diretora.

**Categoria:** Segurança

**Obrigatoriedade:**
- [ ] Desejável
- [x] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório



**RF02 -Comentários dos leitores** 
    
**Categoria:**
- [ ] Oculto                              
- [X] Evidente

**Prioridade:**
- [ ] Altíssima
- [X] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** O site deverá permitir que os leitores comentem as materias publicadas.

**Requisitos Não Funcionais**

**Nome: RNF2.1** Filtro *family friendly*

**Restrição:** O filtro deverá encaminhar para moderação humana quando identificar palavras ofensivas.

**Categoria:** UX (*user experience*)

**Obrigatoriedade:**
- [X] Desejável
- [ ] Obrigatório

**Permanência:**
- [X] Permanente
- [ ] Transitório

**Nome: RNF2.2** Limitação de caracteres

**Restrição:** Os comentários dos leitores possuirão no máximo 300 caracteres.

**Categoria:** Interface

**Obrigatoriedade:**
- [X] Desejável
- [ ] Obrigatório

**Permanência:**
- [X] Permanente
- [ ] Transitório



**RF03 - Formação da HomePage**
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [x] Altíssima
- [ ] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** A página principal (home) deverá exibir sempre as últimas notícias publicadas, havendo transição automática entre elas.

**Requisitos Não Funcionais**

**Nome: RNF3.1** Atualização das noticias

**Restrição:** A atualização das noticias em destaque devem ocorrer a cada 30 minutos.

**Categoria:** UX (*user experience*)

**Obrigatoriedade:**
- [X] Desejável
- [ ] Obrigatório

**Permanência:**
- [X] Permanente
- [ ] Transitório


**RF04 -Formulário** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [ ] Altíssima
- [ ] Alta
- [x] Média
- [ ] Baixa

**Descrição:** O site terá um campo de formulário para interatividade com os leitores com a finalidade de receber sugestão de materias / pautas, críticas, sugestões, elogios, intenção de postagem patrocinada.

**Requisitos Não Funcionais**

**Nome:RNF4.1 Segurança**

**Restrição:** Os dados trafegados via formulário devem passarm por criptografia, protegendo o usuário, caso use rede de internet sem proteção.

**Categoria:** Segurança

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [X] Permanente
- [ ] Transitório

**Nome:RNF4.2 Obrigatoriedade**

**Restrição:** O formulário deverá exigir preenchimento dos campos e-mail, nome, telefone, caixa de texto.

**Categoria:** Layout

**Obrigatoriedade:**
- [ ] Desejável
- [X] Obrigatório

**Permanência:**
- [X] Permanente
- [ ] Transitório



**RF05 -Padronização do Layout** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [x] Altíssima
- [ ] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** O *header* e o *footer* são padronizados e iguais para todas as páginas criadas internamente.

**Requisitos Não Funcionais**

**Nome: RFN**

**Restrição:**

**Categoria:**

**Obrigatoriedade:**
- [ ] Desejável
- [ ] Obrigatório

**Permanência:**
- [ ] Permanente
- [ ] Transitório



**RF06 -Reponsividade** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [x] Altíssima
- [ ] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** O site deverá ser responsivo para dispositivos moveis (mínimo para tablets, celulares e telas windescreen(16:9))

**Requisitos Não Funcionais**

**Nome: RNF 6.1**

**Restrição:** A responsividade da página deverá atender telas de 600, 800 e 1020 de *width*.

**Categoria:**Interface

**Obrigatoriedade:**
- [ ] Desejável
- [x] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório



**RF07 -Conteúdo relacionado** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [ ] Altíssima
- [x] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** Lateralmente a direita o site deverá contar com *aside* para publicações externas e monetizadas.

**Requisitos Não Funcionais**

**Nome: RNF7.1**

**Restrição:** Os conteúdo relacionados de fonte externa e monetizadas deverão atender ao padrão de conteudo do proprio site. 

**Categoria:** UX *user experience*

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório



**RF08 - Formatação Menu** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [ ] Altíssima
- [x] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** No *header* deverá constar menu por tema, lupa de pesquisa por palavra chave das publicações, "formulário" para assinatura de *newsletter*.

**Requisitos Não Funcionais**

**Nome: RNF8.1** Temas

**Restrição:** As publicações devem conter *tags* que as viincule a algum tema interno do portal.

**Categoria:** UX *user experience*

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório

**Nome: RNF8.2** Lupa de pesquisa

**Restrição:** Deve conter integração com o serviço de busca interna do Google melhorando a navegação pelas postagens do site.

**Categoria:** UX *user experience*

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório

**Nome: RNF8.3** NewsLetter

**Restrição:** A campo de assinatura deverá estar visivel para os visitantes do site e após assinatura, o portal deverá encaminhar automaticamente um e-mail dando as boas vindas.

**Categoria:** UX *user experience*

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório

**Nome: RNF8.4** Layout da NewsLetter

**Restrição:** Os e-mails encaminhados via NewsLetter devem respeitar um padrão de layout.

**Categoria:** Layout

**Obrigatoriedade:**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório



**RF09 - Footer** 
    
**Categoria:**
- [ ] Oculto                              
- [x] Evidente

**Prioridade:**
- [ ] Altíssima
- [x] Alta
- [ ] Média
- [ ] Baixa

**Descrição:** No *footer* deve constar links para as redes sociais, meios de contato, institucional (quem somos; a alta mogiana).

**Requisitos Não Funcionais**

**Nome:**

**Restrição:**

**Categoria:**

**Obrigatoriedade:**
- [ ] Desejável
- [ ] Obrigatório

**Permanência:**
- [ ] Permanente
- [ ] Transitório
***


#### Descrição de Requisito Não Funcional ####

***
**Nome:** RNF01 - Hospedagem

**Restrição** O acesso administrativo da hospedagem deve ser realizado apenas por pessoas autorizadas

**Categoria** Segurança

**Obrigatoriedade**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório


**Nome:** RNF02 - Linguagem

**Restrição** O site será escrito em HTML5 e CSS3

**Categoria** CodeType

**Obrigatoriedade**
- [ ] Desejável
- [x] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório


**Nome:** RNF03 - Acesso

**Restrição** O site não deverá permanecer mais que 5h *offline*

**Categoria** Funcionalidade

**Obrigatoriedade**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório


**Nome:** RNF04 - Carregamento

**Restrição** As páginas devem ser carregadas em até 6s

**Categoria** Performance

**Obrigatoriedade**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório


**Nome:** RNF05 - Responsividade

**Restrição** A responsividade da página deverá atender telas de 600, 800 e 1020 de *width*.

**Categoria** Interface

**Obrigatoriedade**
- [x] Desejável
- [ ] Obrigatório

**Permanência:**
- [x] Permanente
- [ ] Transitório
***

#### Descrição de Regra de Negócio ####

***
**RN001 - ** Notícias
**Descrição** Notícias serão avaliadas pelos editores quando o conteúdo vier de fora.

**RN002 - ** Relevância 
**Descrição** Só divulgaremos notícias relevantes a região da Alta Mogiana.

**RN003 - ** Foco
**Descrição** As notícias terão foco em tecnologia, independentemente do tipo.

**RN004 - ** Linguagem 
**Descrição** A linguagem usada será técnica, atingindo especificamente ao público-alvo.

**RN005 - ** Conteúdo
**Descrição** Empresas poderão solicitar divulgação de suas atividades como postagem no site e em troca será exigido um valor, à definir, para manutenção e remuneração de seus criadores.

**RN006 - ** Postagem patrocinada
**Descrição** Os conteúdos publicados acompanharão as tendências tecnológicas do mercado.

**RN007 - ** Regras de publicidade
**Descrição** As postagens patrocinadas só serão veiculadas após confirmação de pagamento.

**RN008 - ** Valores a serem cobrados
**Descrição** Os valores de postagens patrocinadas seguirão uma tabela de valores, variando o custo conforme tempo de exposição.

**RN009 - ** Divulgação
**Descrição** A visualização do site será impulsionada por divulgação via redes sociais e por newsletter.

**RN010 - ** Revisão
**Descrição** As postagens passarão por revisão gramatical, feito por um profissional da área, antes de serem publicadas.

**RN011 - ** Responsividade
**Descrição** Para as postagens, usaremos fontes externas que estejam em acordo com o propósito do site.

***
**Matriz de Rastreabilidade entre Requisitos Funcionais e Regras de Negócio**

 | | RF01 | RF02 | RF03 | RF04 | RF05 | RF06 | RF07 | RF08 | RF09 
 --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
 RN01 | | | x | | | | x | | 
 RN02 | | | | | | | x | | 
 RN03 | | | | | | | x | | 
 RN04 | | | x | | | | x | | 
 RN05 | | | x | x | | | x | | 
 RN06 | | x | | | | | x | | 
 RN07 | | | x | x | | | | | 
 RN08 | | | x | x | | | | | 
 RN09 | | | | | | | | x | x 
 RN10 | | x | | | | | | | 
 RN11 | x | | x | | x | x | x | x | x 
***

***
**Matriz de Rastreabilidade entre Requisitos Funcionais**

 | | RF01 | RF02 | RF03 | RF04 | RF05 | RF06 | RF07 | RF08 | RF09
 --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
 RF01 | x | | | | x | | x | x | x 
 RF02 | | x | x | x | | | | x | 
 RF03 | | x | x | x | | x | | | 
 RF04 | | x | x | x | | | x | | 
 RF05 | x | | | | x | x | | x | x 
 RF06 | | | | | x | x | x | x | x
 RF07 | x | | x | | | x | x | | 
 RF08 | x | x | | x | x | x | | x | 
 RF09 | x | | | | x | x | | | x 
***
