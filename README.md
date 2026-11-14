# App-de-Vagas
# Rumo

Seu assistente de Processos Seletivos com IA Conversacional

## Aplicação

Link da aplicação publicada:

[INSERIR_URL_DA_APLICACAO]

---

# 1. A dor escolhida e por que ela vale um negócio

## Problema

Profissionais que estão buscando recolocação costumam participar de múltiplos processos seletivos simultaneamente.
Durante esse processo é comum perder o controle sobre:

- Quais vagas despertaram interesse.
- Onde já aplicaram.
- Em qual etapa cada candidatura está.
- Datas importantes.
- Preparação para entrevistas.

Grande parte das pessoas utiliza planilhas, notas ou simplesmente depende da memória.
Além disso, para cada candidatura, o candidato precisa pesquisar:

- Quem é a empresa.
- Como ela ganha dinheiro.
- Principais produtos.
- Notícias recentes.
- Como se preparar para a entrevista.

Esse trabalho é repetido dezenas de vezes durante uma busca por emprego.

## Por que isso pode virar um negócio

A busca por emprego é uma dor recorrente e previsível.
Características da oportunidade:

- Alta frequência de uso durante períodos de transição profissional.
- Mercado global.
- Forte aderência a IA generativa.
- Possibilidade futura de monetização via assinatura.
- Potencial para serviços premium de carreira.

Possíveis modelos de receita:

- Assinatura mensal.
- Consultoria de carreira.
- Simulações de entrevista.
- Ajuste de currículo com IA.
- Recomendações patrocinadas de vagas.

---

# 2. Tamanho de Mercado

## TAM
Todos os profissionais que participam de processos seletivos.
Mercado global de Career Services e HR Tech avaliado em bilhões de dólares e em constante crescimento devido à digitalização dos processos de recrutamento.

## SAM
Profissionais brasileiros que estão:
- Desempregados.
- Buscando recolocação.
- Buscando mudança de emprego.
- Participando ativamente de processos seletivos.

## SOM
Usuários digitais que:
- Aplicam para múltiplas vagas.
- Utilizam LinkedIn.
- Possuem familiaridade com ferramentas online.
- Estão dispostos a testar ferramentas baseadas em IA.

---

# Business Model Canvas

## Segmentos de Clientes

- Profissionais em recolocação.
- Jovens em busca do primeiro emprego.
- Profissionais em transição de carreira.

## Proposta de Valor

Organizar candidaturas através de IA conversacional e ajudar na preparação para entrevistas.

## Canais

- LinkedIn.
- Comunidades de tecnologia.
- Grupos de carreira.
- Indicação de usuários.

## Relacionamento com Clientes

- Autoatendimento.
- IA conversacional.
- Recomendações personalizadas.

## Fontes de Receita

- Plano gratuito.
- Assinatura Premium.
- Serviços de consultoria de carreira.

## Recursos Principais

- Modelo de IA.
- Banco de dados.
- Plataforma web.

## Atividades Principais

- Organização de candidaturas.
- Geração de conteúdo para entrevistas.
- Evolução da inteligência conversacional.

## Parceiros Principais

- APIs de IA.
- Plataformas de hospedagem.
- Plataformas de vagas.

## Estrutura de Custos

- Infraestrutura.
- APIs de IA.
- Desenvolvimento.
- Marketing.

---

# 3. Tese do MVP

## Hipótese Principal

Pessoas que participam de múltiplos processos seletivos preferem gerenciar suas candidaturas através de uma experiência conversacional com IA em vez de utilizar planilhas ou controles manuais.

## Hipótese Secundária

Usuários enxergam valor adicional quando recebem automaticamente:

- Resumo da empresa.
- Contexto básico da vaga.
- Dicas para entrevista.

---

# O que foi propositalmente mantido manual

Para acelerar a validação do MVP, algumas funcionalidades foram deixadas fora do escopo.
Não implementado nesta versão:

- Integração com LinkedIn.
- Integração com Gupy.
- Importação automática de candidaturas.
- Calendário de entrevistas.
- Simulação de entrevistas.
- Plano de ação personalizado.

A decisão foi focar apenas na validação da proposta de valor principal.

---

# 4. Mega Prompt Utilizado

## Prompt Inicial
```
Olá copilot. Você pode me ajudar a revisar esse PRD - Product Requirements Document - que cirei? Pretendo usá-lo no lovable para exercitar minhas skills de Vibe Coding. Me envie como resposta o PRD revisado, por favor.
# Contexto
Quero criar um aplicativo de Organização de Processos Seletivos que funcione por meio de conversas com o usuário em linguagem natural.<br>A ideia é facilitar o controle de quem está se candidatando para várias vagas, de forma simples e natural, sem formulários manuais ou planilhas complexas.
# Problema
Muitas pessoas estão buscando um novo emprego ou uma realocação no mercado e acabam aplicando para muitas vagas ao mesmo tempo, para ter uma maior chance de ser aprovada.<br>Quero resolver isso com uma experiência de conversa, adicionando qual vaga a pessoa pretende se candidatar, qual vaga ela já se candidatou e qual parte do processo seletivo ela está. 
Junto à isso, quero que quando ela se candidate em uma vaga, a IA traga um resumo sobre a empresa, últimos acontecimentos no mercado em que a empresa está e dicas para a entrevista.
# Público-Alvo
Pessoas que estão em busca de um novo emprego ou realocação no mercado de trabalho.
# Funcionalidades-Chave
- Registrar as vagas de interesse.
-Registrar as vagas aplicadas.
-Enviar detalhes da empresa, situação econômica atual e dicas para a entrevista.
-Ter visão clara de todos os processos.
-Ter uma aba para desistência.
-Ter uma aba para reprovação.
-Visualizar relatórios simples e personalizados.
-Receber um plano de ação simples e recomendações para buscar vagas.
# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial. Usar tom educativo e linguagem acessível, em português. Deve ter um Design Universal, para que possa ser usado com boa experiência com o maior número de usuários possíveis.
```
**Primeiro Prompt Retornado**
```
# PRD - Assistente de Organização de Processos Seletivos

## Visão Geral

Criar um aplicativo conversacional que ajude profissionais em busca de recolocação ou crescimento de carreira a gerenciar processos seletivos de forma simples, intuitiva e centralizada.

O diferencial do produto é substituir planilhas e formulários complexos por interações em linguagem natural, permitindo que o usuário registre vagas, acompanhe etapas dos processos seletivos e receba suporte inteligente para aumentar suas chances de sucesso.

---

# Problema

Pessoas que estão em busca de emprego costumam se candidatar simultaneamente a diversas vagas em diferentes empresas.

Ao longo da jornada, torna-se difícil acompanhar:

- Quais vagas despertaram interesse.
- Quais candidaturas já foram realizadas.
- Em qual etapa cada processo seletivo está.
- Quais empresas exigem preparação adicional.
- Quais processos foram encerrados por reprovação ou desistência.

Como consequência, muitos candidatos perdem prazos, esquecem informações importantes ou não conseguem se preparar adequadamente para entrevistas.

---

# Objetivo do Produto

Permitir que candidatos organizem toda sua jornada de busca por emprego utilizando apenas conversas em linguagem natural.

O sistema deverá registrar e acompanhar processos seletivos, gerar insights úteis e oferecer suporte contextual para aumentar a preparação e o desempenho dos usuários.

---

# Público-Alvo

## Primário

- Profissionais em processo de recolocação.
- Pessoas desempregadas buscando retorno ao mercado.
- Profissionais buscando transição de carreira.
- Jovens em busca da primeira oportunidade.

## Secundário

- Profissionais empregados que desejam monitorar oportunidades de mercado.
- Consultores de carreira.
- Mentores profissionais.

---

# Proposta de Valor

Ao invés de preencher planilhas ou sistemas complexos, o usuário conversa com a aplicação como faria com um assistente pessoal.

Exemplos:

"Quero acompanhar uma vaga de Product Manager na Nubank."

"Fui chamado para entrevista na Totvs."

"Recebi uma proposta da Ambev."

O sistema interpreta a intenção, organiza automaticamente os dados e atualiza o status do processo.

---

# Funcionalidades Principais (MVP)

## 1. Cadastro Conversacional de Vagas

Permitir ao usuário registrar vagas utilizando linguagem natural.

### Exemplo

Usuário:

"Tenho interesse em uma vaga de Analista de Dados na Magazine Luiza."

Resultado:

- Empresa: Magazine Luiza
- Cargo: Analista de Dados
- Status: Interesse

---

## 2. Gestão de Status dos Processos

Cada vaga deverá possuir um fluxo de acompanhamento.

### Status disponíveis

- Interesse
- Aplicação Realizada
- Triagem
- Entrevista RH
- Entrevista Técnica
- Case/Teste
- Entrevista Final
- Oferta Recebida
- Contratado
- Reprovado
- Desistência

O usuário poderá alterar status apenas conversando com a plataforma.

### Exemplo

"Passei para entrevista técnica na vaga da XP."

O sistema atualiza automaticamente o processo.

---

## 3. Inteligência sobre Empresas

Após registrar uma candidatura, o sistema deverá gerar automaticamente:

### Perfil da Empresa

- Descrição resumida.
- Segmento de atuação.
- Principais produtos e serviços.
- Cultura organizacional.

### Contexto de Mercado

- Notícias recentes relevantes.
- Movimentações do setor.
- Tendências que podem aparecer na entrevista.

### Preparação para Entrevista

- Perguntas comuns.
- Competências mais valorizadas.
- Pontos importantes para estudar.
- Sugestões de perguntas para fazer ao recrutador.

---

## 4. Painel de Processos

Visão consolidada de todas as vagas.

### Filtros

- Por status.
- Por empresa.
- Por cargo.
- Por data de candidatura.

### Indicadores

- Total de vagas monitoradas.
- Total de candidaturas realizadas.
- Entrevistas em andamento.
- Reprovações.
- Ofertas recebidas.
- Taxa de avanço entre etapas.

---

## 5. Área de Reprovações

Espaço dedicado a registrar aprendizados e histórico.

### Objetivos

- Entender padrões.
- Identificar pontos de melhoria.
- Evitar perda de informações importantes.

### Campos sugeridos

- Empresa.
- Motivo informado.
- Feedback recebido.
- Lições aprendidas.

---

## 6. Área de Desistências

Permitir registrar oportunidades abandonadas pelo usuário.

### Motivos comuns

- Faixa salarial incompatível.
- Modelo de trabalho.
- Cultura da empresa.
- Mudança de estratégia de carreira.
- Aceite de outra proposta.

---

## 7. Relatórios Inteligentes

Geração automática de insights simples.

### Exemplos

- Quantidade de candidaturas por mês.
- Taxa de conversão para entrevistas.
- Empresas com mais retorno.
- Tempo médio em cada etapa.
- Evolução da busca de emprego.

---

## 8. Plano de Ação Personalizado

A IA deverá atuar como orientadora de carreira.

### Exemplos de recomendações

- Aumentar volume semanal de candidaturas.
- Melhorar currículo para determinada área.
- Reforçar conhecimentos técnicos específicos.
- Buscar certificações relevantes.
- Expandir networking.

---

# Requisitos Funcionais

### RF01

Registrar vagas por linguagem natural.

### RF02

Atualizar status dos processos por linguagem natural.

### RF03

Consultar histórico de qualquer oportunidade.

### RF04

Exibir painel consolidado de vagas.

### RF05

Gerar resumo da empresa cadastrada.

### RF06

Apresentar notícias e contexto de mercado.

### RF07

Sugerir preparação para entrevistas.

### RF08

Gerar relatórios e métricas do usuário.

### RF09

Criar planos de ação personalizados.

### RF10

Registrar desistências e reprovações.

---

# Requisitos Não Funcionais

### RNF01 - Usabilidade

Interface simples, acessível e focada em conversação.

### RNF02 - Performance

Respostas principais em até 3 segundos.

### RNF03 - Responsividade

Compatível com desktop, tablet e smartphone.

### RNF04 - Acessibilidade

Aplicar princípios de Design Universal:

- Navegação por teclado.
- Compatibilidade com leitores de tela.
- Alto contraste.
- Tipografia legível.
- Linguagem simples.
- Indicadores visuais e textuais.

### RNF05 - Segurança

- Autenticação de usuário.
- Proteção de dados pessoais.
- Consentimento para uso de IA.
- Exclusão de conta e histórico.

---

# Principais Telas do MVP

## Tela 1 - Assistente Conversacional

### Objetivo

Receber o usuário e permitir registrar ou atualizar processos seletivos através de conversas.

### Componentes

- Área de chat.
- Histórico das conversas.
- Sugestões rápidas de comandos.
- Resumo das atividades recentes.

---

## Tela 2 - Dashboard

### Objetivo

Exibir uma visão geral dos processos seletivos.

### Componentes

- Total de vagas de interesse.
- Total de aplicações.
- Entrevistas em andamento.
- Reprovações.
- Propostas recebidas.
- Gráficos simples de evolução.

---

## Tela 3 - Lista de Processos

### Objetivo

Visualizar todas as oportunidades cadastradas.

### Componentes

- Lista de vagas.
- Busca.
- Filtros.
- Ordenação por data e status.

---

## Tela 4 - Detalhes da Vaga

### Objetivo

Centralizar todas as informações relacionadas à oportunidade.

### Componentes

- Dados da vaga.
- Histórico de movimentações.
- Próxima etapa.
- Resumo da empresa.
- Notícias recentes.
- Recomendações para entrevista.

---

## Tela 5 - Plano de Ação

### Objetivo

Ajudar o usuário a aumentar suas chances de sucesso.

### Componentes

- Recomendações personalizadas.
- Metas semanais.
- Sugestões de estudo.
- Sugestões de networking.
- Próximas ações recomendadas.

---

# Fluxo Principal do Usuário

1. Usuário cria conta.
2. Usuário informa uma vaga em linguagem natural.
3. Sistema interpreta e estrutura os dados.
4. Sistema registra a oportunidade.
5. Sistema gera resumo da empresa e contexto de mercado.
6. Usuário atualiza os status ao longo do processo seletivo.
7. Sistema gera indicadores e recomendações.
8. Usuário acompanha sua evolução até contratação, reprovação ou desistência.

---

# Métricas de Sucesso do MVP

## Engajamento

- Número de vagas registradas por usuário.
- Número de interações conversacionais por semana.
- Número de atualizações de status.

## Retenção

- Usuários ativos após 7 dias.
- Usuários ativos após 30 dias.
- Frequência média de retorno.

## Valor Percebido

- Visualizações de resumos de empresas.
- Visualizações de relatórios.
- Uso das recomendações de IA.

## Resultado

- Usuários que avançam para entrevistas.
- Usuários que recebem propostas.
- Tempo médio para organização de uma candidatura.

---

# Hipóteses para Validação Inicial

## Hipótese 1

Usuários preferem gerenciar candidaturas através de conversa ao invés de planilhas.

### Validação

Realizar testes com 10 a 15 usuários e medir tempo de cadastro e satisfação.

---

## Hipótese 2

Resumos sobre empresas aumentam a percepção de valor do produto.

### Validação

Monitorar taxa de acesso aos conteúdos gerados pela IA.

---

## Hipótese 3

Planos de ação personalizados aumentam a frequência de uso do aplicativo.

### Validação

Comparar retenção entre usuários que utilizam recomendações e aqueles que não utilizam.

---

# Escopo Futuro (Pós-MVP)

- Integração com LinkedIn.
- Integração com Gupy.
- Integração com Greenhouse.
- Integração com Lever.
- Calendário de entrevistas.
- Simulação de entrevistas com IA.
- Avaliação automática de currículo.
- Personalização de currículo por vaga.
- Alertas inteligentes.
- Aplicativo mobile nativo.
- Recomendações automáticas de novas oportunidades.

---

# Diretrizes de Design

## Princípios

- Simplicidade acima de tudo.
- Linguagem acessível.
- Baixa curva de aprendizado.
- Navegação intuitiva.
- Inclusão e acessibilidade desde a concepção.

## Design Universal

O produto deve ser utilizável pelo maior número possível de pessoas, independentemente de idade, experiência digital ou limitações físicas, cognitivas ou sensoriais.

Deve contemplar:

- Compatibilidade com leitores de tela.
- Navegação por teclado.
- Contraste adequado.
- Fontes legíveis.
- Mensagens objetivas.
- Feedback visual e textual em todas as ações.
- Estrutura consistente em todas as telas.

---

# Resumo Executivo

O Assistente de Organização de Processos Seletivos é uma plataforma conversacional baseada em IA que permite aos usuários registrar, acompanhar e otimizar candidaturas de emprego utilizando linguagem natural.

O MVP terá como foco validar três pilares principais:

1. Gestão conversacional de processos seletivos.
2. Inteligência contextual sobre empresas e mercado.
3. Recomendações personalizadas para aumentar a empregabilidade.

O sucesso inicial será medido pela adoção da experiência conversacional, engajamento recorrente e percepção de valor gerado pelos insights e orientações da IA.
```

---

## Ajustes Solicitados Durante o Desenvolvimento

### Ajuste 1
Redução do escopo para MVP.
Removidos:

- Dashboard avançado.
- Relatórios complexos.
- Integrações externas.
- Plano de ação.

Objetivo:
Acelerar aprendizado e validação.

### Ajuste 2

Manutenção das funcionalidades de IA.
Mantidos:

- Resumo da empresa.
- Dicas para entrevista.

Motivo:
São os principais diferenciais percebidos pelo usuário.

### Ajuste 3

Aplicação dos princípios de Design Universal.
Incluído:

- Responsividade.
- Legibilidade.
- Contraste adequado.
- Navegação simplificada.

# **Prompt Final Usado**
```
# PRD - MVP Assistente de Processos Seletivos com IA

## Visão Geral

Criar uma aplicação que ajude profissionais a organizar processos seletivos através de conversas em linguagem natural.

O usuário poderá registrar vagas, atualizar etapas do processo seletivo e acompanhar oportunidades sem depender de planilhas ou ferramentas complexas.

Como diferencial, a aplicação utilizará IA para gerar automaticamente um resumo da empresa e orientações para preparação de entrevistas, transformando o produto em um assistente de carreira prático e contextual.

---

# Problema

Pessoas que estão procurando emprego frequentemente participam de diversos processos seletivos ao mesmo tempo.

Com isso, enfrentam dificuldades para controlar:

- Vagas de interesse.
- Empresas onde já aplicaram.
- Etapa atual de cada processo.
- Histórico das movimentações.
- Informações relevantes sobre as empresas.
- Preparação para entrevistas.

Além disso, muitos candidatos gastam tempo realizando pesquisas repetitivas sobre empresas e sobre como se preparar para cada oportunidade.

---

# Objetivo

Validar se usuários preferem gerenciar processos seletivos por meio de uma experiência conversacional com IA em vez de utilizar planilhas, anotações ou ferramentas genéricas.

---

# Público-Alvo

- Profissionais em busca de recolocação.
- Pessoas desempregadas.
- Profissionais buscando transição de carreira.
- Estudantes e recém-formados.
- Profissionais que participam simultaneamente de diversos processos seletivos.

---

# Proposta de Valor

Ao cadastrar uma vaga, o usuário não apenas organiza sua candidatura, mas também recebe contexto relevante para aumentar sua preparação e suas chances de sucesso.

A aplicação atua como um organizador de candidaturas e um assistente de preparação para entrevistas.

---

# Funcionalidades do MVP

## 1. Cadastro de Vagas por Conversa

O usuário deve registrar oportunidades utilizando linguagem natural.

### Exemplo

Usuário:

"Me candidatei para Product Manager na Nubank."

A IA identifica automaticamente:

- Empresa.
- Cargo.
- Status.

O sistema exibe os dados para confirmação antes do salvamento.

---

## 2. Atualização de Status por Conversa

O usuário pode atualizar seus processos seletivos através de mensagens.

### Exemplo

"Passei para entrevista na vaga da XP."

### Status disponíveis

- Interesse
- Aplicação Realizada
- Entrevista
- Oferta
- Contratado
- Reprovado
- Desistência

---

## 3. Lista de Processos

Exibir todas as oportunidades cadastradas.

### Funcionalidades

- Busca por empresa.
- Busca por cargo.
- Filtro por status.
- Ordenação por data.

---

## 4. Detalhes da Vaga

Cada oportunidade deve possuir uma página própria.

### Informações exibidas

- Empresa.
- Cargo.
- Status atual.
- Data de registro.
- Histórico de atualizações.

---

## 5. Resumo Automático da Empresa

Após o cadastro da vaga, a IA deve gerar automaticamente um resumo simples e objetivo da empresa.

### Conteúdo

- O que a empresa faz.
- Segmento de atuação.
- Principais produtos e serviços.
- Informações gerais sobre cultura organizacional.

### Objetivo

Reduzir o esforço de pesquisa inicial do candidato.

---

## 6. Dicas para Entrevista

A IA deve gerar recomendações relacionadas à vaga cadastrada.

### Conteúdo

- Competências importantes para a função.
- Possíveis perguntas de entrevista.
- Temas recomendados para estudo.
- Sugestões de perguntas para fazer ao recrutador.

### Objetivo

Ajudar o usuário a se preparar rapidamente para cada oportunidade.

---

# Principais Telas

## Tela 1 - Chat

Objetivo:

Permitir registrar e atualizar processos seletivos através de conversas.

### Componentes

- Campo de mensagem.
- Histórico da conversa.
- Sugestões rápidas de ações.

---

## Tela 2 - Processos

Objetivo:

Visualizar todas as oportunidades cadastradas.

### Componentes

- Lista de vagas.
- Busca.
- Filtros.
- Status visíveis.

---

## Tela 3 - Detalhes da Vaga

Objetivo:

Centralizar todas as informações da oportunidade.

### Componentes

- Dados da vaga.
- Histórico do processo.
- Resumo da empresa.
- Dicas para entrevista.

---

# Fluxo Principal

1. Usuário cria conta.
2. Usuário informa uma vaga utilizando linguagem natural.
3. IA interpreta empresa, cargo e status.
4. Sistema salva a vaga.
5. Sistema gera automaticamente resumo da empresa.
6. Sistema gera recomendações para entrevista.
7. Usuário atualiza o processo conforme avança.
8. Usuário acompanha todas as oportunidades em uma única interface.

---

# Requisitos Funcionais

## RF01

Registrar vagas através de conversa.

## RF02

Atualizar status através de conversa.

## RF03

Listar todas as vagas cadastradas.

## RF04

Consultar histórico de uma vaga.

## RF05

Gerar resumo automático da empresa.

## RF06

Gerar recomendações para entrevistas.

---

# Requisitos Não Funcionais

## RNF01 - Simplicidade

A aplicação deve exigir o mínimo possível de preenchimento manual.

## RNF02 - Responsividade

Funcionamento adequado em desktop e dispositivos móveis.

## RNF03 - Acessibilidade

Aplicar princípios de Design Universal:

- Navegação por teclado.
- Compatibilidade com leitores de tela.
- Contraste adequado.
- Fontes legíveis.
- Linguagem simples.

## RNF04 - Performance

Respostas visíveis em até 3 segundos para operações comuns.

---

# Fora do Escopo do MVP

As funcionalidades abaixo não fazem parte da primeira versão:

- Dashboard com gráficos.
- Relatórios avançados.
- Plano de ação personalizado.
- Simulação de entrevistas.
- Integrações com LinkedIn.
- Integrações com Gupy.
- Calendário de entrevistas.
- Importação automática de vagas.
- Matching automático de oportunidades.
- Aplicativo mobile nativo.

---

# Hipótese Principal

Profissionais que participam de múltiplos processos seletivos preferem acompanhar suas candidaturas através de uma experiência conversacional com IA, especialmente quando recebem contexto sobre empresas e orientações para entrevistas sem precisar realizar pesquisas manuais.

---

# Métricas de Sucesso

## Adoção

- Número de usuários cadastrados.
- Número de vagas registradas.

## Engajamento

- Quantidade de atualizações realizadas.
- Frequência semanal de uso.

## Valor Percebido

- Visualizações de resumos de empresas.
- Visualizações de dicas para entrevistas.

## Validação

- Usuários que afirmam preferir a aplicação em relação a planilhas.
- Número médio de vagas acompanhadas por usuário.

---

# Critério de Sucesso do MVP

O MVP será considerado validado se os usuários conseguirem:

- Registrar uma vaga em menos de 30 segundos.
- Atualizar processos apenas utilizando conversas.
- Acompanhar todas as candidaturas em uma única lista.
- Perceber valor nos resumos automáticos das empresas.
- Utilizar as recomendações para preparação de entrevistas.
- Demonstrar preferência pelo produto em relação ao uso de planilhas ou anotações manuais.
```

---

# Fluxo do Usuário

1. Usuário cria conta.
2. Registra uma vaga através de conversa.
3. Sistema identifica empresa e cargo.
4. Vaga é salva.
5. IA gera resumo da empresa.
6. IA gera recomendações para entrevista.
7. Usuário atualiza o status da candidatura.

---

## Aplicação Publicada

Endereço:

[INSERIR_URL_DA_APLICACAO]

---

# Resultados Esperados

Indicadores monitorados:

- Usuários cadastrados.
- Vagas registradas.
- Atualizações realizadas.
- Uso do resumo da empresa.
- Uso das dicas de entrevista.

---
