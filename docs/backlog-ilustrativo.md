# Backlog ilustrativo | Atendimento pelo WhatsApp

> **Status:** material proposto para estudo de caso e entrevista. Não são requisitos aprovados, nem funcionalidades comprovadamente desenvolvidas.

## HU-01 — Navegação inicial

**Como** pessoa que inicia atendimento pelo WhatsApp, **quero** visualizar categorias claras de ajuda **para** escolher o caminho relacionado à minha necessidade.

**Critérios de aceite:**
- Dado que o usuário inicia o contato, quando a jornada começa, então são apresentadas opções com nomes claros.
- Dado que o usuário está em uma etapa secundária, quando seleciona “Voltar”, então consegue retornar à etapa anterior ou ao menu, quando aplicável.
- Quando a opção escolhida não estiver disponível, então deve haver mensagem de orientação.

## HU-02 — Orientações e autosserviço

**Como** cliente ou corretor, **quero** entender as informações e documentos necessários à minha solicitação **para** reduzir dúvidas e contatos repetidos.

**Critérios de aceite:**
- O fluxo informa claramente o objetivo da etapa antes de solicitar dados.
- São solicitados apenas os dados necessários à finalidade da jornada.
- Caso seja preciso autenticação ou autorização, o fluxo orienta o usuário a seguir o procedimento seguro definido pelo negócio.
- Não são expostos dados pessoais ou informações contratuais sem autorização.

## HU-03 — Transferência para atendimento humano

**Como** usuário, **quero** ter um caminho de atendimento humano **para** continuar a solicitação quando o autosserviço não resolver o problema.

**Critérios de aceite:**
- Existe orientação objetiva para casos não atendidos pelo fluxo automático.
- O usuário recebe informação sobre o próximo passo.
- Se houver compartilhamento de contexto com atendente, o tratamento de dados respeita as regras de segurança e privacidade.

## HU-04 — Classificação de contatos

**Como** pessoa responsável pela experiência de atendimento, **quero** identificar categorias de solicitação e pontos de abandono **para** propor melhorias na jornada.

**Critérios de aceite:**
- Motivos de contato são classificados em categorias de negócio definidas.
- Eventos relevantes para análise são documentados.
- Relatórios utilizam dados agregados ou minimizados, conforme a finalidade e as políticas aplicáveis.

## Perguntas em aberto para refinamento

- Quais necessidades mais frequentes devem entrar no primeiro ciclo de automação?
- Que tipos de solicitação exigem autenticação, autorização ou atendimento humano?
- Quais sistemas, documentos e integrações estariam autorizados e disponíveis?
- Qual é o canal de escalonamento e quais horários de atendimento precisam ser comunicados?
- Como medir a jornada atual antes de prometer ganhos de eficiência?

## Possível definição de pronto (proposta)

Uma história só poderia ser considerada pronta depois de regras de negócio validadas, fluxo revisado com stakeholders, critérios de aceite testáveis, avaliação de privacidade/segurança e homologação pelos responsáveis.
