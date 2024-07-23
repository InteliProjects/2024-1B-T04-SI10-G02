
## Objetivo Principal do Teste A/B

O objetivo principal do teste A/B é aumentar o número de conversões na nova tela do site da Wizard On, desenvolvida pelo grupo Gaviões da Fiel (G02). Para atingir esse objetivo, o teste avaliará diversas métricas que refletem o engajamento dos usuários, a adoção do serviço e o sucesso nas tarefas. Entre as métricas específicas que pretendemos melhorar estão o número de interações com elementos interativos na página, o aumento de usuários ativos, a taxa de engajamento (proporção de seções por usuários ativos) e a razão de seções por conversões.

Além disso, também pretendemos monitorar e melhorar outras métricas como visualizações de página, início de sessão, engajamento do usuário, scroll (indicando que os usuários estão explorando a página), cliques em elementos interativos e no botão WhatsApp. A coleta e análise detalhada dessas métricas fornecerão uma visão abrangente do comportamento dos usuários, permitindo identificar áreas de sucesso e oportunidades de melhoria. Dessa forma, podemos garantir que as alterações implementadas na nova tela não apenas aumentem as conversões, mas também aprimorem a experiência geral do usuário, orientando futuras decisões e ajustes necessários para a evolução contínua do site da Wizard On.

## Estratégias de Monitoramento

Para garantir que o teste A/B seja bem-sucedido e que os dados coletados sejam precisos e úteis para a análise, implementamos várias estratégias de monitoramento. Primeiro, configuramos o Looker Studio para visualizar e organizar os dados coletados em tempo real. Isso nos permite monitorar continuamente as métricas-chave, como número de interações com elementos interativos, número de usuários ativos, taxa de engajamento, visualizações de página, início de sessão, scroll, cliques em elementos interativos e cliques no botão WhatsApp.

Além disso, definimos alertas automáticos para nos notificar sobre quaisquer anomalias ou quedas significativas nas métricas de desempenho. Isso inclui monitorar a integridade dos dados coletados, garantindo que todas as interações e eventos sejam devidamente registrados e analisados. Implementamos também checkpoints regulares, onde a equipe revisa os dados coletados e ajusta as estratégias conforme necessário para abordar quaisquer problemas identificados.

Essas estratégias de monitoramento contínuo são essenciais para garantir que o teste A/B funcione conforme o planejado e que possamos tomar decisões informadas com base nos dados coletados, permitindo uma análise precisa e eficaz do desempenho das novas telas propostas no site da Wizard On.

## Procedimentos de Integração

Os passos necessários para a criação e integração da variável B estão descritos no seguinte tutorial:
[Link para o tutorial](https://github.com/Inteli-College/2024-1B-T04-SI10-G02/blob/main/document/Sprint%2004/20240503-M10-documentacao_tecnica_landing_page_wizardon_v1%20(1).pdf)

Informações sobre pipeline e CI/CD estão fora do nosso alcance durante o projeto. Utilizamos o FileZilla para enviar os arquivos e, a partir daí, o parceiro faz o encaminhamento da variável B para produção.

## Desafios da Implementação

Durante a configuração do ambiente, passamos por várias dificuldades seguindo o tutorial enviado. Uma delas foi a incompatibilidade do tutorial com as máquinas de alguns membros do grupo, pois ele necessitava de permissões que não eram aplicadas nessas máquinas. Esse problema exigiu que ajustássemos as permissões manualmente, o que consumiu tempo e atrasou o início da implementação. Outro ponto foi o link para download da versão do PHP, que não funcionava. Tivemos que buscar essa versão em outras fontes, o que gerou inconsistências em relação à documentação original e obrigou a equipe a realizar uma série de testes para garantir que a versão encontrada era compatível com o restante do ambiente.

Além disso, mesmo seguindo o relatório completo, o website não funcionou como esperado; nossa página aparecia sem CSS, apenas o HTML ficava disponível. Esse problema foi particularmente desafiador, pois a ausência de CSS impactava diretamente na usabilidade e na apresentação da aplicação. Investigamos várias possíveis causas, incluindo configurações de servidor, permissões de arquivos e possíveis falhas na importação dos arquivos CSS. Para superar esse problema, tentamos configurar o ambiente em outras duas máquinas, e em uma delas, o tutorial funcionou como pretendido. Isso nos permitiu identificar que a falha não estava no código em si, mas nas configurações específicas das máquinas que estavam sendo usadas.
