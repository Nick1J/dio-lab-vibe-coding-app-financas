
# 💸 App de Organização de Finanças Pessoais com Vibe Coding  
por Tiago Mendes

---
# Finança AI – Pitch Inicial

O **Finança AI** é um aplicativo de organização de finanças pessoais que usa **conversas em linguagem natural** para simplificar o controle de gastos e metas.  
Ele substitui formulários e planilhas complexas por uma experiência acessível e inclusiva, baseada em **Design Universal**, permitindo que qualquer pessoa registre transações, acompanhe objetivos e receba recomendações financeiras de forma prática e personalizada.


## 1. PRD Refinado com o Copilot

```txt
PRD – App de Organização de Finanças Pessoais

1. Contexto
Criar um aplicativo que permita ao usuário organizar suas finanças pessoais por meio de conversas em linguagem natural, sem depender de formulários ou planilhas complexas. O foco é tornar o controle financeiro acessível, simples e intuitivo.

2. Problema
- Apps atuais exigem muita entrada manual.
- Pouca personalização e experiência engajante.
- Usuários iniciantes desistem rapidamente por acharem o processo burocrático.

Oportunidade: oferecer uma experiência conversacional com recomendações automáticas de economia.

3. Público-Alvo
- Pessoas que querem começar a organizar suas finanças sem complicação.
- Usuários iniciantes em controle financeiro.
- Pessoas que preferem interações naturais em vez de interfaces tradicionais.
- Compromisso com Design Universal: garantir que o app seja acessível e ofereça boa experiência para o maior número possível de usuários, incluindo pessoas com diferentes idades, níveis de letramento digital e necessidades de acessibilidade.

4. Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Metas financeiras: definir e acompanhar objetivos.
4. Agente Financeiro: dicas de economia personalizadas.
5. Relatórios simples e visuais, adaptados ao perfil do usuário.
6. Design Universal aplicado:
   - Interface clara e intuitiva.
   - Suporte a acessibilidade (voz, contraste, navegação simplificada).
   - Experiência consistente em diferentes dispositivos.

5. Entregável da IA (MVP)
- Principais telas:
  - Tela de Conversa (chat com o agente financeiro).
  - Tela de Metas (definição e acompanhamento).
  - Tela de Relatórios (gráficos simples e personalizados).

- Recursos necessários:
  - Processamento de linguagem natural (NLP).
  - Motor de classificação automática de transações.
  - Módulo de geração de relatórios.
  - Sistema de recomendações financeiras.
  - Implementação de boas práticas de Design Universal.

- Validação inicial:
  - Testes com grupo piloto de usuários iniciantes.
  - Inclusão de usuários com diferentes perfis (idade, acessibilidade).
  - Coleta de feedback sobre clareza da conversa e utilidade das dicas.
  - Ajustes rápidos no fluxo de interação antes de expandir.
```

---

## 2. Iterações com o Lovable

- **Prompt inicial:**  
  > Crie um APP de Finanças Pessoais com base no seguinte PRD(Product Requeriments Documents ): {PRD}

- **Ajuste solicitado:**  
  > Ative o Lovable Cloud e conecte o chat a uma IA real para processar linguagem natural de verdade, com banco de dados para salvar transações e metas  
  {O Lovable criou o app sem ativar o Cloud e sem ativar o chat}

- **Correção de erro:**  
  > Está ocorrendo um erro no recebimento da mensagem, veja e conserte esse erro.  
  {Ocorreu um erro no recebimento das mensagens, o Lovable consertou o erro}

- **Resultado Final no Lovable:**  
  [Finança AI no Lovable](https://james-financas.lovable.app/)

---

## 3. Prints das Interações

<img width="1599" height="721" alt="image" src="https://github.com/user-attachments/assets/f219ffa2-1f26-4ede-a7a5-8cb193115c12" />

<img width="1597" height="729" alt="image" src="https://github.com/user-attachments/assets/1906f8d1-4dd5-4f3e-9699-c275ad5a67f3" />

<img width="1591" height="725" alt="image" src="https://github.com/user-attachments/assets/d3f5257a-3e80-495e-920a-caf7c438a383" />

<img width="1581" height="726" alt="image" src="https://github.com/user-attachments/assets/6bc36a72-e0aa-49ee-a9f5-2aaaacf7ee2d" />

---

## 4. Finança AI – Resumo do Aplicativo

### Visão Geral
O **Finança AI** é um aplicativo de organização de finanças pessoais que funciona por meio de **conversas em linguagem natural**. Ele substitui formulários e planilhas complexas por uma experiência interativa e acessível, permitindo que o usuário registre gastos, acompanhe metas e receba recomendações de forma simples e natural.

### Problema que resolve
Muitos usuários desistem de controlar suas finanças porque os apps tradicionais exigem entradas manuais e oferecem pouca personalização.  
O Finança AI resolve isso com uma interface conversacional e recomendações automáticas.

### Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários que buscam praticidade e simplicidade.  
- Compromisso com **Design Universal**, garantindo acessibilidade e boa experiência para o maior número possível de pessoas, independentemente de idade, nível de letramento digital ou necessidades específicas.

### Funcionalidades-Chave
- Registro de gastos via chat em linguagem natural.  
- Classificação automática das transações.  
- Definição e acompanhamento de metas financeiras.  
- Dicas personalizadas do “Agente Financeiro”.  
- Relatórios simples e visuais.  
- Interface inclusiva e acessível (Design Universal).

### Exemplo prático
O usuário interage com o chatbot “Finança AI” para atualizar metas financeiras, como a compra de um carro.  
O sistema reconhece aportes, atualiza o progresso e motiva o usuário com mensagens positivas, além de oferecer opções para visualizar relatórios ou planejar próximos passos.

### MVP – Entregável da IA
- **Principais telas:** Conversa, Metas e Relatórios.  
- **Recursos necessários:** NLP, classificação automática, relatórios, recomendações financeiras, acessibilidade.  
- **Validação inicial:** testes com usuários iniciantes e perfis diversos para garantir clareza, utilidade e acessibilidade.

---

## 5. Reflexão

### O que funcionou bem?
A interação com a IA em conjunto com o PRD ficou muito boa. O app foi desenvolvido pelo Lovable de uma forma que torna a experiência simples e prática para o usuário.

### O que não funcionou como o esperado?
O Lovable implementou o app sem salvar no banco de dados; foi preciso pedir para ativar o Lovable Cloud. No final, o problema foi resolvido.

### O que aprendeu sobre conversar com IAs?
Foi muito interessante conversar com a IA, porque ela entende bem os objetivos e ajuda a estruturar o projeto. O resultado final ficou melhor do que o esperado.
```

---

Essa versão deixa o README mais **limpo, organizado e profissional**, sem acrescentar nada além do que você já trouxe.  

Quer que eu também prepare uma **versão curta (pitch inicial)** para colocar logo no topo do README, como uma apresentação rápida do projeto?
