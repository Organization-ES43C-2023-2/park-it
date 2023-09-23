# Requisitos Funcionais - Projeto Park It

Este documento descreve os requisitos funcionais para o projeto "Park It", um sistema de gerenciamento/utilização de estacionamento.

## Requisitos Funcionais

| Identificador | Descrição | Prioridade | Depende de |
| ------------- | ---------------------------------------------------------- | ---------- | ---------- |
| [RF01] | Os donos de estacionamentos devem poder cadastrar suas instalações no aplicativo "Park It". O cadastro deve incluir informações como nome do estacionamento, localização, número total de vagas disponíveis e detalhes de contato. | Alta | - |
| [RF02] | Os proprietários de estacionamentos cadastrados no "Park It" devem poder compartilhar, em tempo real, a disponibilidade de vagas em seus estacionamentos. Isso inclui o número de vagas disponíveis a qualquer momento. | Alta | - |
| [RF03] | O sistema "Park It" deve ser capaz de rastrear o tráfego de carros em um estacionamento durante o uso e manter um registro do número de carros que utilizam o estacionamento nas últimas 24 horas. É fundamental declarar um termo e/ou uma política referente à utilização dos dados do usuário no contexto do rastreamento de tráfego de carros para garantir a transparência e a privacidade dos dados.
- Política de Privacidade: O sistema "Park It" garantirá que todos os dados de rastreamento de tráfego de carros sejam coletados e armazenados de forma anônima e agregada, de modo a não identificar indivíduos específicos. Os dados coletados serão utilizados exclusivamente para fins de melhoria do serviço, como otimização do fluxo de carros e disponibilidade de vagas. Os usuários serão informados sobre essa política de privacidade no momento do cadastro e poderão optar por não participar do rastreamento, se desejarem.| Alta | - |
| [RF04] | Os usuários do aplicativo "Park It" devem poder compartilhar sua localização para que o aplicativo possa identificar estacionamentos cadastrados mais próximos. Para garantir a confiança dos usuários, é importante especificar como a localização será compartilhada e processada, bem como declarar uma política de privacidade que aborde o uso desses dados.
- Política de Privacidade de Compartilhamento de Localização: O aplicativo "Park It" solicitará permissão aos usuários para acessar sua localização. Essa localização será usada exclusivamente para identificar estacionamentos próximos e melhorar a experiência do usuário. Os dados de localização serão tratados com total confidencialidade e não serão compartilhados com terceiros. Os usuários serão informados sobre essa política de privacidade no momento do cadastro e poderão revogar a permissão de acesso à localização a qualquer momento nas configurações do aplicativo. | Média | - |
| [RF05] | Os usuários do aplicativo "Park It" devem poder visualizar a lista de estacionamentos próximos à sua localização e verificar se há vagas disponíveis em cada um deles, juntamente com o número de vagas disponíveis. Para garantir uma experiência clara e informativa, o processo de visualização de vagas disponíveis deve ser detalhado da seguinte forma:
   
   - Entradas:
     - Localização do usuário: O aplicativo receberá a localização atual do usuário.
     - Lista de estacionamentos próximos: O aplicativo identificará os estacionamentos mais próximos com base na localização do usuário.

   - Processamento:
     - Identificação de vagas disponíveis: O aplicativo verificará a disponibilidade de vagas em cada estacionamento próximo.
     - Contagem de vagas disponíveis: O sistema contará o número de vagas disponíveis em cada estacionamento.
     - Exibição de informações: O aplicativo exibirá a lista de estacionamentos próximos, indicando quais têm vagas disponíveis e o número de vagas em cada um.

   - Saídas:
     - Lista de estacionamentos: O aplicativo apresentará uma lista de estacionamentos próximos.
     - Disponibilidade de vagas: Cada estacionamento na lista indicará se há vagas disponíveis e, se disponíveis, o número de vagas. | Alta | - |
| [RF06] | O aplicativo "Park It" deve permitir que os usuários tenham a opção de efetuar o pagamento pelo estacionamento diretamente através do aplicativo, proporcionando maior comodidade. Para garantir uma experiência completa e transparente no processo de pagamento, os seguintes detalhes serão fornecidos:
  
   - Processamento de Pagamento:
     - Métodos de Pagamento Aceitos: O aplicativo "Park It" aceitará diversos métodos de pagamento, incluindo cartões de crédito, débito e serviços de pagamento digital (como Apple Pay e Google Pay).
     - Taxas e Custos Adicionais: Quaisquer taxas ou custos adicionais associados ao pagamento pelo aplicativo, como taxas de processamento, serão claramente indicados durante o processo de pagamento.
     - Segurança de Pagamento: Todas as transações de pagamento serão protegidas por medidas de segurança robustas para garantir a segurança dos dados financeiros dos usuários.

   - Política de Pagamento:
     - Cancelamento e Reembolso: O aplicativo "Park It" definirá uma política de cancelamento e reembolso que descreverá as condições sob as quais os usuários podem solicitar reembolsos de pagamentos efetuados pelo aplicativo. | Média | - |

## Conclusão

Esses requisitos funcionais definem as principais funcionalidades do sistema de gerenciamento de estacionamento "Park It". Eles servem como base para o desenvolvimento do aplicativo, garantindo que ele atenda às necessidades dos proprietários de estacionamentos e dos usuários finais.
