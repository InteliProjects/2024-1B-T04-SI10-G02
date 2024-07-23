## Sumário

[1. Introdução e Contexto](#c1)

[2. Metodologia Utilizada](#c2)

[3. Análise Quantitativa](#c3)

[4. Análise Qualitativa](#c4)

[5. Conclusão e Recomendações Preliminares](#c5)

<br>


# <a name="c1"></a>1. Introdução e Contexto

&emsp;&emsp; A análise preliminar tem como objetivo realizar uma primeira investigação do escopo do problema apresentado na página de vendas do curso Wizard On, coletando, reunindo e estudando dados e informações relevantes para o seu entendimento. A partir dessa análise, foram desenvolvidas as primeiras hipóteses que constituirão as próximas propostas de solução, as quais serão construídas a partir da sprint 2 em diante. A estrutura da análise preliminar foi composta pela aplicação do Framework HEART, Pesquisas Quantitativas (utilizando dados do Google Analytics fornecidos pela Wizard) e Pesquisas Qualitativas (realizadas através de testes de uso pessoalmente). Além disso, com base nos dados e informações obtidas durante a análise, foi elaborada uma conclusão geral acompanhada de recomendações preliminares.

# <a name="c2"></a>2. Metodologia Utilizada

&emsp;&emsp; Para este projeto, utilizamos a metodologia HEART. Mais detalhes podem ser encontrados nos seguintes documentos:

- [Aplicação da Metodologia HEART e GSM](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/main/document/Sprint%2001/Grupo%202%20-%20HEART%20%2B%20GSM.pdf)

- [Documentação do Framework HEART para WizardOn](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/main/document/Sprint%2001/HEART.md)

# <a name="c3"></a>3. Análise Quantitativa

&emsp;&emsp; Os dados dos logs da plataforma LP fornecem *insights* valiosos sobre a interação dos usuários com a plataforma, permitindo identificar padrões de uso e comportamento. A análise dos eventos registrados permite entender como os usuários navegam, interagem e se engajam com o conteúdo da plataforma, além de fornecer informações críticas para aprimorar a experiência do usuário e aumentar a taxa de conversão.

## Principais Eventos Registrados

&emsp;&emsp; O evento mais frequente registrado é o carregamento de página, com mais de 22 milhões de ocorrências. Isso sugere uma alta taxa de acessos e interesse contínuo na plataforma. A visualização de página, com quase 2,3 milhões de ocorrências, indica que os usuários estão explorando diferentes seções ou conteúdos da plataforma, refletindo um engajamento significativo. Eventos como o início de sessão e a primeira visita, ambos ultrapassando a marca de um milhão de ocorrências, revelam que os usuários estão tanto retornando quanto acessando a plataforma pela primeira vez. Apesar de menos frequentes, os eventos de engajamento do usuário e rolagem ainda registram centenas de milhares de ocorrências, indicando uma interação ativa com o conteúdo.

| Nome do Evento       | Contagem de Eventos |
|----------------------|---------------------|
| Carregamento de página | 22.538.287 |
| Visualização de página | 2.299.685   |
| Início de sessão       | 2.012.375   |
| Primeira visita        | 1.402.714   |
| Engajamento do usuário | 412.624     |
| Rolagem               | 234.792     |

*Tabela 1: Dados dos Logs da LP*  
*Fonte: Dados disponibilizados*

## Sistemas Operacionais

&emsp;&emsp; Em relação aos sistemas operacionais, o Android domina significativamente com mais de 24 milhões de eventos, seguido pelo iOS, Windows, Linux e Chrome OS. Isso sugere que a base de usuários é predominantemente móvel, com dispositivos Android liderando os acessos à plataforma. A predominância de Android e iOS destaca a importância de otimizar a experiência da plataforma para dispositivos móveis.

| Sistema Operacional | Contagem de Eventos |
|---------------------|---------------------|
| Android             | 24.814.051          |
| iOS                 | 3.466.762           |
| Windows             | 990.519             |
| Linux               | 128.601             |
| Chrome OS           | 36.199              |

*Tabela 2: Dados dos Logs da LP*  
*Fonte: Dados disponibilizados*

## Informações Gerais

&emsp;&emsp; As informações gerais destacam que houve mais de 1,5 milhão de usuários ativos, participando de mais de 2 milhões de sessões. O número total de conversões, cerca de 148 mil, indica que aproximadamente 7.04% das sessões resultaram em alguma forma de ação desejada, como uma compra ou inscrição. A taxa de conversão é um indicador crucial para avaliar a eficácia das estratégias de engajamento e marketing.

```
Soma de Active users: 1.538.922
Soma de Sessions: 2.114.268
Soma de Conversions: 148.911
Taxa de conversão: 7.04 %
```

## Análise por Idade dos Usuários

&emsp;&emsp; A distribuição etária dos usuários revela uma diversidade significativa, com uma grande proporção de usuários cuja idade não foi identificada. Entre os grupos etários identificados, os jovens de 18 a 24 anos representam uma parcela considerável, seguidos pelos grupos de 25 a 34 anos e 35 a 44 anos. Isso pode orientar campanhas de marketing mais segmentadas e estratégias de conteúdo adaptadas a diferentes faixas etárias.

| Faixa Etária | Sessões   |
|--------------|-----------|
| Desconhecida | 1.509.472 |
| 18-24        | 175.969   |
| 25-34        | 134.545   |
| 35-44        | 88.545    |
| 45-54        | 55.278    |
| 55-64        | 35.077    |
| 65+          | 22.822    |

*Tabela 3: Dados dos Logs da LP*  
*Fonte: Dados disponibilizados*

## Visualizações por País

&emsp;&emsp; As visualizações por país mostram um forte domínio do Brasil, com mais de 2,2 milhões de visualizações, seguido por uma lacuna considerável entre os Estados Unidos, Indonésia, Hungria e Alemanha. Isso sugere uma base de usuários concentrada principalmente no Brasil, com menor presença em outros países. A presença inesperada de países como Indonésia, Hungria e Alemanha pode oferecer novos *insights* para expansão de mercado.

```
Brazil: 2.278.578
United States: 6.768
Indonesia: 3.422
Hungary: 1.533
Germany: 1.439
```

## Distribuição Geográfica das Cidades

&emsp;&emsp; A análise do número de cidades por país destaca a extensão da presença da plataforma, com mais de mil cidades no Brasil e centenas nos Estados Unidos, Portugal, Reino Unido e Alemanha. Isso indica uma presença global, embora com uma concentração regional mais forte.

```
Brazil: 1.063
United States: 335
Portugal: 60
United Kingdom: 46
Germany: 44
```


## Picos de Atividade por Horário

&emsp;&emsp; A análise dos picos de horário revela que os momentos de maior atividade na plataforma ocorrem à noite, especificamente às 20h e 21h. Isso sugere que os usuários tendem a ser mais ativos durante esses períodos, possivelmente devido ao tempo livre após o horário de trabalho ou estudo. Esses *insights* são cruciais para programar lançamentos de conteúdo e campanhas de marketing.

| Hora        | Usuários Ativos |
|-------------|-----------------|
| 20          | 143.411         |
| 19          | 137.369         |
| 21          | 134.477         |
| 18          | 126.677         |
| 22          | 122.786         |

*Tabela 4: Dados dos Logs da LP*  
*Fonte: Dados disponibilizados*

## Conclusões e Próximos Passos

&emsp;&emsp; A análise detalhada dos dados dos logs da plataforma LP oferece uma compreensão abrangente do comportamento dos usuários e seus padrões de uso. As informações obtidas são essenciais para consolidar possíveis causas das taxas de conversão e, assim, melhorar a performance no Teste A/B. As seguintes conclusões podem ser destacadas:

1. **Alta Taxa de Acesso e Engajamento**: O elevado número de carregamentos de página e visualizações indica que a plataforma atrai e mantém o interesse dos usuários.
2. **Predominância Móvel**: A maioria dos acessos ocorre via dispositivos Android, sugerindo a necessidade de foco contínuo na otimização para dispositivos móveis.
3. **Diversidade Etária**: A plataforma atende a uma ampla gama de idades, necessitando de estratégias segmentadas para diferentes grupos etários.
4. **Concentração Geográfica**: A presença majoritária no Brasil oferece uma base sólida para expansão internacional, especialmente em países emergentes.
5. **Picos de Atividade Noturna**: Conhecer os horários de maior atividade permite programar campanhas e lançamentos de conteúdo de forma mais eficaz.

&emsp;&emsp; Para os próximos passos, é recomendável aprofundar a análise qualitativa dos dados para identificar motivos específicos que impulsionam o engajamento e a conversão, além de realizar testes A/B focados nas hipóteses levantadas. Isso permitirá um refinamento contínuo da plataforma, maximizando a satisfação do usuário e as taxas de conversão.

# <a name="c4"></a>4. Análise Qualitativa

&emsp;&emsp; A eficácia de uma interface de usuário é fundamental para facilitar a interação desejada entre o usuário e a plataforma digital. Na análise da página inicial da Wizard, objetiva-se identificar como os elementos de design e usabilidade influenciam tanto a percepção do usuário quanto a sua decisão de engajar-se com os mecanismos de cadastro oferecidos. Os testes foram projetados para avaliar a clareza da comunicação, a intuitividade da navegação e a eficiência dos processos de interação com o usuário, fornecendo assim dados essenciais para identificar barreiras e oportunidades de melhoria na experiência do usuário.

**Metodologia dos Testes**

&emsp;&emsp; A metodologia empregada consistiu em entrevistar uma amostra representativa de usuários potenciais, com diferentes faixas etárias, submetendo-os a um conjunto estruturado de perguntas que exploravam suas reações imediatas e as escolhas feitas ao acessar a página inicial pela primeira vez. As questões abordadas incluíram:

- A escolha do método de cadastro.
- As razões para evitar métodos alternativos.
- Impressões sobre o propósito da plataforma.
- Avaliações sobre a estética e a funcionalidade do site.

**Participantes e Respostas**

| Participante     | Método de Cadastro | Opinião sobre WhatsApp                                   | Percepção do WizardOn                 | Opinião Geral do Site                                      |
|------------------|--------------------|----------------------------------------------------------|---------------------------------------|-------------------------------------------------------------|
| Carolina Fricks  | Formulário         | Não gosta, associado a falta de preferência pelo uso.    | Aula online com uso de caneta.        | Poluído.                                                    |
| Mateus Neves     | Formulário         | Não gosta, sensação de que é para suporte.               | Aula online.                          | Poluído.                                                    |
| Luana Parra      | Formulário         | Não gosta.                                               | Aula somente de inglês online.        | Muita informação.                                           |
| Pedro Romão      | Formulário         | Prefere, mas o formulário chamou mais atenção.           | Aula de inglês.                       | Poluído.                                                    |
| Afonso Brandão   | Formulário         | Fica na frente do “eu quero”, obstruindo elementos.      | Escola EAD de inglês.                 | Muita informação, necessidade de acesso rápido a redes sociais. |
| Pedro Faria      | Formulário         | Prefere, mas o formulário foi o primeiro instinto.       | Aula EAD de inglês.                   | Parece um site de spam.                                     |
| Luíza Santana    | Formulário         | Prefere, mas viu primeiro o formulário.                  | Aula online de inglês.                | Comum, estética similar a muitos outros cursos de inglês online. |


&emsp;&emsp; Todos optaram pelo uso do formulário de cadastro, apesar de alguns expressarem preferência pelo WhatsApp. A presença do WhatsApp foi frequentemente vista como mais relacionada ao suporte do que ao cadastro.

**Percepções Comuns**
- Aparência do Site: Descrito como "poluído" e com "muita informação". Luíza mencionou que o site tem uma estética comum, similar a muitos outros cursos de inglês online.
- Identificação do Serviço: Os usuários identificaram a WizardOn principalmente como uma plataforma de aulas de inglês online. O termo "escola EAD de inglês" também foi utilizado para descrever o serviço.
- Elementos Visuais e Funcionalidades: Afonso comentou que o ícone do WhatsApp obstruiu o botão "Eu quero", sugerindo problemas no layout que podem afetar a usabilidade.

**Diretrizes para Ações Futuras**
- Simplificar o Design: Reduzir a quantidade de conteúdo visual e textual para despoluir a interface.
- Melhorar a Distinção Visual: Criar uma hierarquia visual mais clara para ajudar os usuários a navegarem pelo site de forma mais intuitiva.
- Testar Alternativas de Layout: Realizar testes A/B com diferentes layouts para o formulário e a presença do WhatsApp, avaliando qual configuração gera melhor engajamento e satisfação dos usuários.

# <a name="c5"></a>5. Conclusão e Recomendações Preliminares

&emsp;&emsp; Os dados quantitativos e qualitativos coletados durante a análise revelam padrões significativos no comportamento e nas percepções dos usuários. A predominância do uso de dispositivos Android e os altos números de carregamento e visualização de páginas indicam uma forte interação dos usuários com a plataforma. Entretanto, a análise qualitativa destaca uma série de desafios relativos à usabilidade e ao design da página inicial, que podem estar impactando negativamente a experiência do usuário e, consequentemente, as taxas de conversão.

&emsp;&emsp; A recorrência de termos como "poluído" e "muita informação" nas respostas dos participantes aponta para uma sobrecarga visual e informativa na interface atual, que exige atenção imediata. Adicionalmente, a interação com o elemento do WhatsApp, frequentemente associada ao suporte em vez de cadastro, sugere confusão na comunicação das funcionalidades disponíveis, o que pode desviar os usuários de ações desejadas como o cadastro.

**Recomendações Preliminares:**
- Redesign da Interface: É crucial implementar um design mais limpo e menos carregado. Isso pode incluir a redução de elementos distrativos, a simplificação da paleta de cores e a reorganização dos componentes da interface para garantir uma hierarquia visual clara e intuitiva.
- Clarificação das Funções de Comunicação: Reavaliar o papel do WhatsApp na página inicial, assegurando que sua função esteja claramente definida e seja imediatamente compreensível para os novos visitantes. Considerar separar claramente as opções de cadastro e suporte.
- Otimização para Dispositivos Móveis: Com o domínio do acesso via dispositivos Android, é essencial garantir que a interface seja totalmente otimizada para uso móvel, proporcionando uma experiência suave e intuitiva para todos os usuários, independentemente do dispositivo.
- Testes A/B Contínuos: Implementar uma rotina de testes A/B para explorar diferentes layouts e estratégias de comunicação, especialmente em torno das áreas críticas identificadas, como o formulário de cadastro e a integração do WhatsApp. Isso ajudará a identificar as configurações que maximizam a usabilidade e o engajamento do usuário.
- Análise de Feedback Contínuo: Estabelecer um mecanismo sistemático para coletar e analisar feedback dos usuários em tempo real, permitindo ajustes ágeis e fundamentados em dados para aperfeiçoar continuamente a página inicial.
