# Gerenciamento de Vans


**Natalie Santana Dias Abreu, natalie.abreu@pucminas.br**

**Maria Eduarda Paiva Ferraz, dudaferrazp@gmail.com**

**Gabriel dos Santos Silva Coelho, gabriel.coelho@sga.pucminas.br**

**Paulo Victor Fernandes de Araujo Silva, paulovictor0907@gmail.com**

**Luiz Gustavo Silva Oliveira, luiz.Igso12@gmail.com**

**João Pedro de Oliveira Santos, jjooao@gmail.com**

---

Professores:

**Michelle Hanne Soares de Andrade**

**Joana Gabriela Ribeiro de Souza**

**Danilo de Quadros Maia Filho**

---

_Curso de Engenharia de Software_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

**Resumo**. O Van Wise é um sistema que propõe soluções para otimizar o transporte escolar, nosso objetivo é acabar com alguns problemas como desorganização financeira, ineficiência nas rotas e a falta de transparência. As justificativas se baseiam em relatos e notícia que mostram incidentes como criança esquecida ou caindo da Van. Nosso projeto atende as necessidades para pessoas como motoristas, pais, estudantes e gestores.

---

## 1. Introdução

O transporte escolar é uma parte fundamental da rotina de muitas famílias, mas ainda enfrenta desafios significativos que comprometem sua eficiência e segurança. Entre os principais problemas, destacam-se a desorganização financeira, a ineficiência nas rotas e a falta de transparência, que muitas vezes resultam em incidentes como crianças esquecidas ou acidentes durante o trajeto. Com base nessas questões, o Van Wise surge como uma solução inovadora, visando otimizar o processo de transporte escolar. Este sistema foi desenvolvido para atender às necessidades de motoristas, pais, estudantes e gestores, oferecendo maior controle, organização e segurança. O objetivo do Van Wise é transformar a experiência do transporte escolar, trazendo benefícios concretos para todas as partes envolvidas.

### 1.1 Contextualização

O transporte escolar por vans é uma solução essencial para a locomoção de estudantes, garantindo acesso seguro e eficiente às instituições de ensino. No entanto, a gestão desse serviço pode ser desorganizada, com dificuldades no controle de pagamentos, rotas e comunicação entre responsáveis, motoristas e alunos. A digitalização desse processo pode oferecer mais segurança, transparência e eficiência para todos os envolvidos.

### 1.2 Problema

1-Dificuldade no Controle Financeiro – Muitos motoristas e responsáveis enfrentam problemas para registrar e acompanhar pagamentos, o que pode levar a inadimplência, cobranças incorretas e confusão sobre valores e prazos.

2-Desorganização nas Rotas – Sem uma plataforma integrada, a definição dos trajetos pode ser ineficiente, resultando em percursos mais longos, atrasos constantes e dificuldades na adaptação de novas rotas em casos de imprevistos.

3-Falta de Transparência e Comunicação – A comunicação entre motoristas, responsáveis e alunos ocorre por meios descentralizados, como grupos de WhatsApp ou ligações, dificultando o repasse de informações importantes sobre horários, atrasos ou mudanças no serviço.

4-Ausência de Monitoramento e Segurança – Os responsáveis muitas vezes não sabem exatamente quando seus filhos embarcaram ou desembarcaram da van, aumentando a preocupação com a segurança do transporte.

#### 1.3 Objetivo Geral

Desenvolver um aplicativo de gestão de transporte escolar por vans, proporcionando maior organização, eficiência e segurança na comunicação entre motoristas, responsáveis e alunos.

#### 1.3.1 Objetivos específicos

1- Criar um sistema para o controle de pagamentos, facilitando o acompanhamento de mensalidades e evitando inadimplência.
2- Implementar um gerenciamento eficiente de rotas, otimizando trajetos e garantindo pontualidade.
3- Disponibilizar notificações automáticas para informar horários de embarque e desembarque.
4- Estabelecer um canal de comunicação direto entre motoristas e responsáveis.
5- Incluir um sistema de avaliações para monitoramento da qualidade do serviço.

### 1.4 Justificativas
A recorrência de incidentes no transporte, como crianças esquecidas ou caindo de veículos, mostra a necessidade de mais segurança e controle. Falhas na gestão financeira, nas rotas e na comunicação aumentam os riscos e a ineficiência. Por isso, é essencial desenvolver um sistema que melhore o controle financeiro, organize rotas, aprimore a comunicação e garanta mais segurança no transporte.

## 2. Participantes do processo

Nome: Ricardo Santos
Idade: 45 anos
Profissão: empresário do ramo de transporte escolar.
Objetivo: Gerenciar as vans garantindo eficiência, segurança e rentabilidade.

Necessidades:
- Garantir que o motorista cumpra horários e rotas.
- Controlar pagamentos e faturamento.
- Manter um serviço confiável para atrair mais clientes.

Nome: Marcos Oliveira
Idade: 38 anos
Profissão: motorista autônomo de transporte escolar.
Objetivo: Transportar os alunos com segurança e garantir o recebimento do serviço prestado.

Necessidades:
- Visualizar sua rota com clareza.
- Confirmar presença dos alunos da van.
- Canal de comunicação com os pais e gestor da frota.

Nome: Ana Carvalho
Idade: 39 anos
Profissão: Advogada
Objetivo: Garantir que seu filho chegue à escola e volte para casa com segurança.

Necessidades:
- Confirmar se o filho está na van em tempo real.
- Acompanhar o trajeto da van pelo aplicativo.
- Realizar pagamentos de forma simples e segura.


Nome: Pedro Henrique
Idade: 19 anos
Profissão: Estudante universitário
Objetivo: Ter um transporte confiável para ir à faculdade sem depender de transporte público.

Necessidades:
- Saber o horário exato da chegada da van.
- Ter um meio de comunicação rápido com o motorista.
- Confirmar a presença ou ausência pelo sistema


## 3. Modelagem do processo de negócio

### 3.1. Análise da situação atual

_Apresente uma descrição textual de como os sistemas atuais resolvem o problema que se propõe a resolver.  Caso sua proposta seja inovadora e não existam processos claramente definidos, **apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente**, mesmo que não se utilize tecnologia computacional._

### 3.2. Descrição geral da proposta de solução
O Van Wise é um sistema digital para otimização do transporte escolar por vans. Ele visa solucionar desafios comuns, como a desorganização financeira, ineficiência das rotas e falta de transparência na comunicação. A proposta envolve a criação de um aplicativo que conecte motoristas, responsáveis e estudantes, permitindo um gerenciamento mais eficiente das operações.

Apesar das vantagens, o sistema enfrenta alguns desafios e limitações:
- Adoção da tecnologia: Alguns motoristas e responsáveis podem resistir à digitalização, preferindo métodos tradicionais.
- Conectividade e acessibilidade: O aplicativo exige acesso contínuo à internet para algumas funcionalidades, o que pode ser um obstáculo em áreas com sinal instável. (chek in)
- Implementação gradual: A transição do modelo atual para o digital pode exigir treinamentos e ajustes no processo de uso.

O Van Wise se alinha às seguintes estratégias e objetivos:
- Eficiência operacional: O aplicativo reduz o tempo gasto em processos manuais, como cobranças e definição de rotas, permitindo que motoristas e gestores foquem na qualidade do serviço.
- Segurança e confiabilidade: Funcionalidades como monitoramento em tempo real e confirmação de embarque/desembarque aumentam a confiança dos responsáveis.
- Valorização do serviço: O sistema de avaliações melhora a percepção de qualidade, tornando o transporte escolar mais competitivo.
- Sustentabilidade financeira: O controle financeiro automatizado reduz inadimplência e melhora o fluxo de caixa dos motoristas.

Para fortalecer a nossa proposta, algumas melhorias podem ser implementadas:
- Integração com meios de pagamento diversificados – Inclusão de PIX, cartão de crédito e boletos automáticos para facilitar pagamentos.
- Sistema de inteligência artificial para otimização de rotas – Utilizar IA para sugerir os melhores trajetos em tempo real, reduzindo atrasos.
- Gamificação e incentivos – Criar um sistema de recompensas para motoristas e usuários com bom histórico, incentivando boas práticas.
- Suporte offline para funcionalidades essenciais – Permitir que informações básicas, como a rota planejada, fiquem disponíveis mesmo sem internet.

### 3.3. Modelagem dos processos

[PROCESSO 1 - Nome do Processo](processo-1-nome-do-processo.md "Detalhamento do Processo 1.")

[PROCESSO 2 - Nome do Processo](processo-2-nome-do-processo.md "Detalhamento do Processo 2.")

[PROCESSO 3 - Nome do Processo](processo-3-nome-do-processo.md "Detalhamento do Processo 3.")

[PROCESSO 4 - Nome do Processo](processo-4-nome-do-processo.md "Detalhamento do Processo 4.")

## 4. Projeto da solução

_O documento a seguir apresenta o detalhamento do projeto da solução. São apresentadas duas seções que descrevem, respectivamente: modelo relacional e tecnologias._

[Projeto da solução](solution-design.md "Detalhamento do projeto da solução: modelo relacional e tecnologias.")


## 5. Indicadores de desempenho

_O documento a seguir apresenta os indicadores de desempenho dos processos._

[Indicadores de desempenho dos processos](performance-indicators.md)


## 6. Interface do sistema

_A sessão a seguir apresenta a descrição do produto de software desenvolvido._ 

[Documentação da interface do sistema](interface.md)

## 7. Conclusão
O Van Wise representa uma solução estratégica para os desafios enfrentados no transporte escolar, proporcionando uma gestão mais eficiente e segura. Ao resolver problemas como a desorganização financeira, a ineficiência das rotas e a falta de transparência, o sistema contribui para um ambiente mais seguro e organizado tanto para os estudantes quanto para os gestores e motoristas. Além disso, ao garantir maior controle e facilitar a comunicação entre todos os envolvidos, o Van Wise visa transformar a experiência do transporte escolar, promovendo confiança e tranquilidade para pais, alunos e profissionais. Dessa forma, o projeto oferece uma resposta eficaz às necessidades atuais, potencializando a qualidade do serviço e, consequentemente, a segurança e bem-estar das crianças.


# REFERÊNCIAS
http://portal.pucminas.br/imagedb/documento/DOC_DSC_NOME_ARQUI20160217102425.pdf
**[1.1]** - _Band Vale, Seu Bairro no BC. **Pais reclamam de vans escolares em Guaratinguetá**. Guaratinguetá, SP: c2024._

**[1.2]** - Record, R7. **menina-de-9-anos-cai-de-van-escolar-em-movimento-**. São Paulo, SP: c2024._

**[1.3]** - _Balanço geral. **Reportagem do Dia: Criança é esquecida dentro de van escolar por quatro horas**. São Bernardo do Campo, SP. c2023._

**[1.4]** - _Globo, G1. **Número de vans escolares cadastradas na prefeitura tem queda de 50% em Campinas**. Campinas, SP. c2024_

**[1.5]** - _UNIVERSIDADE FEDERAL DE GOIÁS FACULDADE DE CIÊNCIAS E TECNOLOGIA ENGENHARIA DE TRANSPORTES, UFG. **Caracterização e Avaliação do Transporte
Escolar do Brasil**. Goiás, GO. c2018._


# APÊNDICES
_Atualizar os links e adicionar novos links para que a estrutura do código esteja corretamente documentada._


## Apêndice A - Código fonte

[Código do front-end](../src/front) -- repositório do código do front-end

[Código do back-end](../src/back)  -- repositório do código do back-end


## Apêndice B - Apresentação final


[Slides da apresentação final](presentations/)


[Vídeo da apresentação final](video/)






