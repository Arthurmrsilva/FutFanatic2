# Personas do Sistema

As personas representam os principais perfis de usuários que utilizarão o sistema. Elas ajudam a compreender os objetivos, necessidades, dificuldades e expectativas de cada tipo de usuário, contribuindo para a definição dos requisitos funcionais e dos critérios de qualidade do software.

## 1. Administrador: Rafael Oliveira

- **Idade:** 35 anos
- **Profissão:** Coordenador administrativo do clube
- **Nível de conhecimento tecnológico:** Intermediário
- **Frequência de uso:** Diária
- **Dispositivo principal:** Computador/notebook

### Perfil

Rafael é responsável pela administração das informações disponibilizadas no sistema do clube. Durante sua rotina de trabalho, precisa cadastrar partidas, atualizar resultados, publicar notícias e acompanhar a comercialização dos ingressos.

Possui familiaridade com sistemas administrativos, planilhas e ferramentas de escritório, mas busca uma solução centralizada que reduza tarefas manuais e facilite a organização das informações.

### Objetivo principal

Manter as informações do clube atualizadas e realizar o gerenciamento das partidas, conteúdos, usuários e vendas de ingressos de maneira organizada e segura.

### Necessidades

- Cadastrar, editar e excluir partidas.
- Informar datas, horários e locais dos jogos.
- Registrar e atualizar resultados das partidas.
- Cadastrar, editar e publicar notícias.
- Definir setores, valores e quantidade de ingressos disponíveis.
- Consultar informações relacionadas às vendas realizadas.
- Gerenciar usuários e suas respectivas permissões de acesso.
- Identificar rapidamente informações incorretas ou incompletas.
- Ter confirmação das operações realizadas no sistema.

### Dificuldades

- Informações armazenadas em diferentes planilhas e documentos.
- Possibilidade de erros durante o cadastro manual das informações.
- Dificuldade em manter os dados atualizados em diferentes canais.
- Risco de usuários sem autorização alterarem informações importantes.
- Necessidade de consultar diversas fontes para acompanhar vendas e partidas.

### Expectativas de qualidade

Rafael espera um sistema seguro, organizado e confiável, com controle de acesso às funcionalidades administrativas. Também espera que os campos possuam validações para evitar cadastros incorretos e que as operações apresentem mensagens claras de confirmação ou erro.

---

## 2. Torcedor: Lucas Santos

- **Idade:** 21 anos
- **Profissão:** Estudante
- **Nível de conhecimento tecnológico:** Alto
- **Frequência de uso:** Frequente, principalmente próximo aos dias de jogos
- **Dispositivo principal:** Smartphone

### Perfil

Lucas acompanha constantemente as notícias e partidas do clube. Costuma acessar o sistema pelo celular durante o deslocamento, intervalos da faculdade ou antes dos jogos.

Seu principal interesse é encontrar informações rapidamente, sem precisar navegar por diversas páginas ou procurar informações em redes sociais diferentes.

### Objetivo principal

Acompanhar de maneira rápida e prática as principais informações relacionadas ao clube e às partidas.

### Necessidades

- Consultar as próximas partidas.
- Visualizar datas, horários e locais dos jogos.
- Consultar resultados de partidas anteriores.
- Acompanhar notícias e novidades relacionadas ao clube.
- Identificar facilmente qual será o próximo jogo.
- Receber informações atualizadas sobre alterações de data, horário ou local.
- Acessar as informações utilizando dispositivos móveis.

### Dificuldades

- Encontrar informações desatualizadas em diferentes canais.
- Ter dificuldade para localizar rapidamente o próximo jogo.
- Sites com navegação confusa ou excesso de informações.
- Páginas que apresentam problemas de visualização em dispositivos móveis.
- Lentidão em períodos com grande quantidade de acessos.

### Expectativas de qualidade

Lucas espera que o sistema tenha uma interface simples, intuitiva e responsiva. As principais informações devem ser encontradas com poucos passos, especialmente as informações sobre o próximo jogo.

Também espera que o sistema possua bom desempenho e continue funcionando adequadamente mesmo em horários de grande acesso, como antes ou durante partidas importantes.

---

## 3. Cliente: Mariana Costa

- **Idade:** 29 anos
- **Profissão:** Assistente administrativa
- **Nível de conhecimento tecnológico:** Intermediário
- **Frequência de uso:** Ocasional, principalmente quando pretende comparecer aos jogos
- **Dispositivo principal:** Smartphone

### Perfil

Mariana acompanha alguns jogos do clube e costuma comparecer ao estádio ocasionalmente com familiares ou amigos. Utiliza o sistema principalmente quando deseja consultar preços e comprar ingressos.

Como não realiza compras com frequência, valoriza um processo simples e deseja ter segurança de que o pagamento foi realizado corretamente e que o ingresso estará disponível no momento da entrada no estádio.

### Objetivo principal

Comprar ingressos de maneira rápida, segura e confiável, recebendo uma confirmação clara após a conclusão da compra.

### Necessidades

- Consultar as partidas disponíveis para compra.
- Visualizar setores do estádio.
- Consultar preços dos ingressos.
- Verificar a quantidade ou disponibilidade de ingressos.
- Selecionar o ingresso desejado.
- Visualizar o valor total da compra antes do pagamento.
- Realizar o pagamento com segurança.
- Receber a confirmação da compra.
- Acessar o ingresso digital após a aprovação do pagamento.
- Consultar o histórico e o status de seus pedidos.

### Dificuldades

- Pagamentos recusados sem explicação clara.
- Possibilidade de cobrança duplicada.
- Falta de confirmação após concluir uma compra.
- Dificuldade para localizar o ingresso adquirido.
- Insegurança sobre a aprovação ou não do pagamento.
- Alteração inesperada do valor durante o processo de compra.

### Expectativas de qualidade

Mariana espera que o processo de compra seja simples, transparente e seguro. O sistema deve informar claramente o valor total antes da confirmação do pagamento e impedir cobranças duplicadas.

Após a aprovação do pagamento, o ingresso deve ficar disponível para consulta, juntamente com as informações da partida e da compra realizada.

---

## Relação das Personas com a Qualidade de Software

A definição das personas auxilia na identificação dos requisitos funcionais e não funcionais do sistema e também na elaboração dos testes de software.

Para o **Administrador**, os principais aspectos de qualidade estão relacionados à **segurança, integridade dos dados e controle de acesso**. Os testes devem verificar, por exemplo, se somente usuários autorizados podem acessar funções administrativas e se os dados cadastrados são corretamente validados.

Para o **Torcedor**, os aspectos mais importantes são **usabilidade, desempenho e compatibilidade com dispositivos móveis**. Os testes devem avaliar se o usuário consegue localizar rapidamente partidas, resultados e notícias e se o sistema mantém um bom desempenho mesmo com grande quantidade de acessos.

Para o **Cliente**, os principais aspectos estão relacionados à **confiabilidade, segurança e integridade das transações**. Os testes devem garantir que o pagamento seja processado corretamente, que não ocorram cobranças duplicadas e que o ingresso digital seja disponibilizado após a confirmação da compra.

Dessa forma, as personas ajudam a orientar o desenvolvimento e os testes do sistema considerando diferentes necessidades reais dos usuários, aumentando a qualidade e a adequação da solução proposta.
