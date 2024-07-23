# Conclusões e Recomendações de Negócio a Partir da Análise Detalhada dos Resultados dos Testes A/B para a Pearson

## Contextualização
&emsp;&emsp; Após a aplicação do teste A/B multivariado, é essencial analisar os resultados obtidos, como a taxa de conversão dos usuários em cada tela. Somente por meio dessa análise será possível avaliar o desempenho do teste A/B, identificando quais telas alcançaram os melhores resultados, quais alterações na página geraram esses efeitos e quais estratégias a Pearson deve adotar para desenvolver novas páginas ou até mesmo novos testes A/B.

## Dados Acumulados Durante o Teste

&emsp;&emsp; Duas fontes principais de dados foram utilizadas durante o teste. A primeira, foi o Looker, plataforma do Google configurada pela Pearson para monitoramnto dos dados gerados pelas telas. Em sua seção "AB Test - Acessos", e exclusivamente nela, o resultados de cada tela em específico era mostrado, mais especificamente, o número de "Usuários Ativos" e "Seções". A segunda fonte de dados era diretamente a Pearson, que, extraindo esses dados de fontes internas, nos enviava uma planilha com o número de sessões, número de conversões e a taxa dessas conversões (calculado a partir do número de conversões dividido pelo número de sessões). Os dados referentes ao looker podiam ser acompanhados diariamente, com constantes atualizações, já os dados diretos da Pearson foram disponibilizados em uma série de cinco autualizações entre o final da Sprint 4 até o final da sprint 5.

&emsp;&emsp; Os dados coletados ficaram abaixo das expectativas do grupo e do planejamento estabelecido no "Plano de Coleta de Resultados" (Sprint 4). Métricas como tempo de carregamento da página, rolagem e cliques em cada página B não estão disponíveis no Looker. A ausência desses dados específicos limita as conclusões e recomendações derivadas do teste. Portanto, como recomendação para futuras coletas de dados, sugerimos que os meios de coleta incluam essas métricas mais detalhadas (comumente identificadas em testes A/B de páginas web). Dessa forma, será possível evitar uma visão macro que limita uma análise mais profunda e específica.

## Evolução dos Resultados da Tela B ao Longo do Período de Teste

### Leads (Dados Extraídos do Looker)

Duas datas aleatórias com um certo espaçamento de tempo forma escolhidos para a coleta desses dados

**Data: 04/06/2024**
- Grupo 2: 11 leads

**Data: 07/06/2024**
- Grupo 2: 12 leads

### Conversões (Dados Fornecidos Pela Pearson)
**Data: 10/06/2024**
- Grupo 2:
  - Sessões: 164
  - Conversões: 17
  - Taxa de Conversão (%CR): 10,4%

**Data: 11/06/2024**
- Grupo 2:
  - Sessões: 303
  - Conversões: 19
  - Taxa de Conversão (%CR): 6,3%

**Data: 14/06/2024**
- Grupo 2:
  - Sessões: 379
  - Conversões: 22
  - Taxa de Conversão (%CR): 5,8%

**Data: 18/06/2024**
- Grupo 2:
  - Sessões: 600
  - Conversões: 30
  - Taxa de Conversão (%CR): 5,0%

### Análise e Insights da Progressão

&emsp;&emsp; Observamos um aumento expressivo no número de sessões ao longo do período analisado para o Grupo 2, com um salto de 164 sessões em 10/06/2024 para 600 sessões em 18/06/2024. No entanto, a taxa de conversão diminuiu de 10,4% para 5,0%. Este declínio na taxa de conversão, apesar do aumento nas sessões, sugere que, embora mais usuários tenham visitado a página, uma menor proporção deles realizou a conversão esperada.

### Impacto do Volume de Sessões na Conversão
&emsp;&emsp; É importante considerar que um maior número de visitas pode influenciar a percepção da taxa de conversão. Com um volume maior de sessões, é possível que haja uma maior diversidade de perfis de usuários, incluindo muitos que podem não estar suficientemente qualificados ou prontos para converter. A alta quantidade de sessões na Página A sugere que esta página atrai um público mais amplo, o que pode diluir a taxa de conversão. Entretanto, a análise comparativa direta das taxas de conversão sugere que a estrutura e os elementos da Página A são mais eficazes para converter um público qualificado.

## Conclusão dos Resultados Finais entre as Telas A e B

![image](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/assets/99208815/7948f55e-b502-4550-85d0-e4a7cbe93245)

&emsp;&emsp; Fazendo uma análise comparativa dos resultados numéricos, podemos observar que a tela B do Grupo 2 teve um desempenho percentualmente superior à tela A. A tela B alcançou uma taxa de conversão de 5%, enquanto a tela A registrou 3,5%, resultando em uma diferença de 1,5 pontos percentuais.

## Impactos e Implicações para o Negócio

&emsp;&emsp; A análise dos resultados obtidos com o teste A/B entre as telas A e B revela insights importantes para a estratégia de negócios da Pearson. Primeiramente, a tela B demonstrou um desempenho superior em termos de taxa de conversão, alcançando 5% em comparação com os 3,5% da tela A. Essa diferença de 1,5 pontos percentuais é significativa e indica que as mudanças implementadas na tela B foram mais eficazes em converter usuários.

Essa superioridade da tela B sugere que elementos específicos presentes nela (a serem detalhados no próximo tópico) foram mais atrativos e convincentes para os usuários. Assim, a Pearson pode considerar adotar permanentemente esses elementos nas futuras páginas para melhorar a taxa de conversão de maneira consistente.

No entanto, é crucial abordar a diminuição da taxa de conversão observada ao longo do tempo para a tela B, mesmo com o aumento no número de sessões. Esse declínio aponta para a necessidade de uma análise mais aprofundada para entender por que, apesar de atrair mais usuários, a tela B não manteve a mesma eficácia em conversões. Fatores como a qualidade do tráfego, a adequação da mensagem aos diferentes segmentos de público e possíveis problemas de usabilidade devem ser investigados.

Por fim, como já citado anteriomente, a ausência de dados mais granulares por página, como tempo de carregamento, rolagem e cliques, limita a capacidade de realizar uma análise mais detalhada e identificar pontos específicos de melhoria. Recomenda-se que futuras coletas de dados incluam essas métricas para permitir uma compreensão mais completa do comportamento dos usuários e a eficácia das páginas.


## Sugestões de Ações

### Novos Testes Mais Graduais e Isolados

&emsp;&emsp; Dado o melhor desempenho da tela B em relação à tela A, é crucial analisar os fatores e elementos que contribuíram para esse resultado. O teste A/B é caracterizado por mudanças graduais que permitem uma fácil identificação dos elementos que geraram melhorias. No entanto, neste teste específico, várias alterações foram implementadas na tela B de uma única vez, tornando difícil identificar quais mudanças específicas resultaram no aumento das conversões. Ao todo, as mudanças realizadas foram:

- Botão do WhatsApp minimalista e reposicionado.
- Formulário com texto simplificado e direto.
- Alteração na ordem dos elementos, destacando o WIZ.me mais acima.
- Vídeo explicativo posicionado abaixo do WIZ.me.
- Texto do Compromisso de Aprendizagem em bullet points.

Dada a quantidade de mudanças implementadas, não é possível determinar exatamente qual elemento (ou conjunto de elementos) foi responsável pelo aumento das conversões. É possível que alguns elementos tenham contribuído negativamente, mas foram compensados por outros com efeitos positivos. 

Para ações futuras, é recomendável adotar uma abordagem mais incremental nas modificações das páginas. Realizar testes A/B com alterações específicas e isoladas permitirá identificar com precisão quais mudanças impactam positivamente as conversões. Isso facilitará a criação de páginas mais eficientes e orientadas para resultados. Contudo , é essencial ordenar as prioridades dos testes e mudanças de acordo com o risco associado. 

### Riscos Associados a Cada Tipo de Mudança

&emsp;&emsp; No nível de baixo risco, recomendamos começar pelo formulário com texto simplificado e direto. Alterar o texto para uma linguagem mais clara e objetiva pode reduzir empecilhos no processo de conversão, tornando-o mais acessível para os usuários. Esta é uma alteração de baixo risco, que pode ser implementada rapidamente e monitorada para verificar melhorias nas conversões. Além disso, transformar o texto do Compromisso de Aprendizagem em bullet points pode facilitar a leitura e compreensão das informações-chave, potencialmente aumentando a confiança do usuário. Este ajuste é também de baixo risco, com impacto médio na clareza da mensagem.

No nível de médio risco, a reordenação dos elementos na página é um ponto crucial a ser testado. Posicionar o WIZ.me mais acima na página pode destacar informações importantes, melhorando a experiência do usuário e potencialmente aumentando o engajamento. Esta mudança possui um risco moderado, mas tem um impacto significativo no layout da página. Além disso, reposicionar o vídeo explicativo abaixo do WIZ.me pode aumentar o engajamento e a compreensão do produto ou serviço oferecido, com um impacto médio no design geral da página e no tempo de carregamento.

Finalmente, no nível de alto risco, sugerimos testar o botão do WhatsApp minimalista e reposicionado. Ele tem um impacto significativo na usabilidade e nas novas conversões (que agoram se focar no formulário tradicional), sendo esse o principal ponto de mudança na tela B proposta. Esta alteração envolve um risco significativo devido à sua importância na comunicação direta com os usuários e crucial meio de conversão.

### Resumo de Riscos e Mudanças

**Baixo Risco:**

- Formulário com texto simplificado e direto
- Texto do Compromisso de Aprendizagem em bullet points

**Médio Risco:**

- Alteração na ordem dos elementos, destacando o WIZ.me mais acima
- Vídeo explicativo posicionado abaixo do WIZ.me

**Alto Risco:**

- Botão do WhatsApp minimalista e reposicionado


### Outra Sugestão de Ação: Testes Qualitativos

&emsp;&emsp; Embora o grupo não tenha tido a oportunidade de realizar testes qualitativos para as novas telas B, sugerimos fortemente a implementação dessa abordagem no futuro. Testes qualitativos, como entrevistas com usuários e sessões de usabilidade, podem fornecer insights valiosos sobre quais elementos das novas telas estão potencialmente convertendo ou não. Esse tipo de teste permite uma análise mais direta e detalhada do comportamento do usuário, ajudando a identificar pontos específicos de melhoria e a entender melhor as preferências e dificuldades dos usuários. Implementar testes qualitativos pode acelerar o processo de otimização, garantindo que as mudanças realizadas sejam baseadas em feedback real e direcionado.


## Conclusão Final

&emsp;&emsp; A tela B superou a tela A em termos de taxa de conversão, indicando que as mudanças implementadas foram eficazes. No entanto, a análise também revelou uma diminuição na taxa de conversão ao longo do tempo, sugerindo a necessidade de investigações mais detalhadas e incrementais. Para otimizar futuras estratégias, recomendamos a adoção de testes qualitativos para as telas Bs. Além disso, uma coleta de dados mais abrangente, incluindo métricas detalhadas, é essencial para melhorar a qualidade de novos testes A/Bs e telas propostas.












