# 💸 App de Finanças Pessoais com Vibe Coding

Esse projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Lovable e o Copilot Web.
A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural

---

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).


---

📄 PRD refinado no Copilot web:

````markdown
PRD – Aplicativo de Organização de Finanças Pessoais

1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de conversas em linguagem natural.
A proposta é substituir formulários e planilhas complexas por uma experiência fluida e acessível, onde o usuário interage com um “Agente Financeiro” que entende suas necessidades e oferece recomendações.

2. Problema
- Os aplicativos atuais exigem entrada manual excessiva e oferecem pouca personalização.
- Isso gera frustração e leva muitas pessoas a desistirem de organizar suas finanças.
- O desafio é criar uma experiência mais humana e prática, que incentive o usuário a manter o hábito de registrar e acompanhar seus gastos.

3. Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma simples.
- Usuários iniciantes, sem experiência prévia em controle financeiro.
- Pessoas que preferem interações naturais em vez de interfaces técnicas.
- Nota importante: a solução deve seguir princípios de Design Universal, garantindo que o máximo de pessoas, independentemente de idade, nível de experiência ou possíveis limitações, tenham uma boa experiência de uso.

4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações (ex.: alimentação, transporte, lazer).
3. Definição e acompanhamento de metas financeiras (ex.: economizar R$200/mês).
4. Dicas de economia personalizadas fornecidas pelo “Agente Financeiro”.
5. Relatórios simples e visuais, adaptados ao perfil do usuário.
6. Design Universal: interface acessível, clara e inclusiva, com suporte a diferentes perfis de usuários.
7. Chat fluido e educativo: além de registrar transações, deve responder dúvidas sobre finanças pessoais.

5. Entregável da IA
- Plano de MVP contendo:
  - Principais telas: chat, visão geral de gastos, metas, relatórios.
  - Recursos necessários: NLP para entender linguagem natural, categorização automática, motor de recomendações.
  - Esboço de validação inicial:
    - Testar com grupo piloto de usuários iniciantes e diversos perfis.
    - Avaliar engajamento (quantidade de registros feitos).
    - Medir clareza das recomendações e satisfação com relatórios.
    - Verificar acessibilidade e usabilidade para diferentes públicos.

6. Requisitos Específicos

1. Requisito de Login e Acesso à Conta
1. Objetivo: Garantir que cada usuário tenha acesso seguro e individual ao seu histórico financeiro.
- Descrição Funcional:
 - Criar conta única com ID de usuário e senha.
 - Autenticar login e carregar histórico individual.
 - Manter sessão segura e permitir logout.
 - Suporte para recuperação e alteração de senha.

2. Critérios de Aceitação:
1. Usuário consegue se registrar com ID e senha.
2. Após login, acessa apenas seus próprios dados.
3. Sistema impede acesso não autorizado.
4. Usuário consegue redefinir senha.

7. Requisito de Histórico e Metas
1. Objetivo: Permitir que o usuário visualize e gerencie seus dados e metas.
Descrição Funcional:
- Visualizar histórico completo de informações.
- Excluir dados registrados, se desejar.
- Criar metas financeiras personalizadas.
- Excluir metas criadas anteriormente.
- Alterações refletidas imediatamente nos relatórios.

Critérios de Aceitação:
1. Usuário visualiza histórico completo.
2. Usuário exclui dados específicos.
3. Usuário cria metas personalizadas.
4. Usuário exclui metas criadas.
5. Relatórios atualizados automaticamente.

8. Requisito de Chat Fluido e Educativo
1. Objetivo: Garantir que o chat seja natural e educativo.
Descrição Funcional:
- Compreender perguntas sobre finanças pessoais.
- Responder de forma clara e acessível.
- Alternar entre registro e dúvidas sem mudar de tela.
- Agente Financeiro fornece dicas e explicações.

Exemplos de Perguntas:
- "Como posso economizar no supermercado?"
- "O que é uma reserva de emergência?"
- "Qual a diferença entre gasto fixo e gasto variável?"
- "Como funciona o cartão de crédito?"
- "Qual a melhor forma de começar a poupar?"
- "O que significa taxa de juros?"
- "Como posso organizar meu orçamento mensal?"
- "Qual a importância de ter metas financeiras?"

Critérios de Aceitação:
1. Usuário registra transações pelo chat.
2. Usuário faz perguntas e recebe respostas compreensíveis.
3. Chat alterna entre registro e dúvidas sem interrupções.
4. Respostas são educativas e relevantes para iniciantes.
````
---

💬 Interações com o Lovable:

````
 Crie um App de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}
````

````
Requisito de Login e Acesso à Conta

Objetivo

Garantir que cada usuário tenha acesso seguro e individual ao seu histórico financeiro dentro do aplicativo.

Descrição Funcional

O sistema deve permitir que cada usuário crie uma conta única com ID de usuário (e-mail ou nome de usuário) e senha individual.

O processo de login deve autenticar o usuário e carregar seu histórico de informações financeiras pessoais.

O sistema deve manter a sessão ativa de forma segura e permitir logout a qualquer momento.

Deve haver suporte para recuperação de senha e alteração de credenciais.

Critérios de Aceitação

Usuário consegue se registrar com ID e senha.

Após login, o usuário acessa apenas seus próprios dados financeiros.

O sistema impede acesso não autorizado.

O usuário consegue redefinir senha em caso de esquecimento.

Requisito de Chat Fluido e Educativo – Exemplos de Perguntas

Objetivo

Garantir que o chat do aplicativo seja uma experiência natural e contínua, permitindo não apenas o registro de recebimentos e gastos, mas também o esclarecimento de dúvidas sobre finanças pessoais.

Descrição Funcional

O chat deve compreender perguntas do usuário relacionadas a finanças pessoais.

O sistema deve responder de forma clara e educativa, oferecendo explicações simples e acessíveis.

O chat deve manter fluidez, permitindo alternar entre registro de transações e perguntas sem necessidade de mudar de tela ou modo.

O “Agente Financeiro” deve atuar como guia, fornecendo dicas, recomendações e respostas contextualizadas.

Exemplos de Perguntas que o Chat Deve Responder

"Como posso economizar no supermercado?"

"O que é uma reserva de emergência?"

"Qual a diferença entre gasto fixo e gasto variável?"

"Como funciona o cartão de crédito?"

"Qual a melhor forma de começar a poupar?"

"O que significa taxa de juros?"

"Como posso organizar meu orçamento mensal?"

"Qual a importância de ter metas financeiras?"

Critérios de Aceitação

Usuário consegue registrar gastos e recebimentos pelo chat.

Usuário consegue fazer perguntas sobre finanças pessoais e recebe respostas compreensíveis.

O chat permite alternar entre registro e dúvidas sem interrupções.

As respostas fornecidas pelo sistema são educativas, claras e relevantes para iniciantes.

Requisito de Histórico e Metas

Objetivo

Permitir que o usuário tenha controle total sobre suas informações financeiras registradas no aplicativo, incluindo a visualização e exclusão de dados, além da criação e gerenciamento de metas pessoais.

Descrição Funcional

O sistema deve disponibilizar uma área onde o usuário possa visualizar todo o histórico de informações já incluídas (gastos, entradas, metas).

O usuário deve ter a opção de excluir qualquer dado registrado, caso deseje.

O sistema deve permitir que o usuário crie suas próprias metas financeiras personalizadas (ex.: economizar R$500 em 3 meses).

O usuário deve poder excluir metas criadas anteriormente, caso não queira mais acompanhá-las.

As alterações realizadas (exclusão de dados ou metas) devem ser refletidas imediatamente no histórico e nos relatórios.

Critérios de Aceitação

Usuário consegue visualizar o histórico completo de informações registradas.

Usuário consegue excluir dados específicos do histórico.

Usuário consegue criar metas financeiras personalizadas.

Usuário consegue excluir metas criadas anteriormente.

Relatórios e visão geral são atualizados automaticamente após exclusões ou alterações
````

---

> Resultado final no Lovable: https://chat-cash-coach-63.lovable.app/auth

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/7dc70a7e-585a-44c0-a39f-90f370c928d6" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/1abce8e0-dd08-4ac9-af72-397d4c3beb3f" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/13e3b257-8497-4737-8e3e-58d8580d1293" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/7b6f4965-a4f1-4ad5-b589-2d67006d576c" />

---

# Funcionalidades do App Finny – Seu Agente Financeiro

## 1. Chat Inteligente e Educativo
- Registro de gastos e receitas via linguagem natural.
- Respostas claras e acessíveis para dúvidas sobre finanças pessoais.
- Assistente financeiro que oferece dicas e orientações educativas.

## 2. Visão Geral Financeira
- Exibição de saldo atual, receitas e despesas mensais.
- Evolução percentual do saldo.
- Listagem dos maiores gastos por categoria.
- Histórico de transações recentes com data e valor.

## 3. Gestão de Metas Financeiras
- Criação de metas personalizadas (ex.: reserva de emergência).
- Acompanhamento do progresso de cada meta.
- Adição de valores às metas.
- Exclusão de metas quando desejado.

## 4. Relatórios Visuais e Insights
- Gráficos de gastos por categoria.
- Resumo mensal com valores e porcentagens por tipo de despesa.
- Insights automáticos sobre hábitos financeiros.
- Dicas práticas para melhorar o controle financeiro.

## 5. Design Universal e Acessível
- Interface clara e intuitiva com navegação lateral.
- Linguagem amigável e inclusiva.
- Funcionalidades acessíveis para diferentes perfis de usuários.

## 6. Login Seguro e Histórico Individual
- Acesso com ID de usuário e senha.
- Histórico de transações e metas exclusivo e protegido.
- Suporte para recuperação de senha e logout.

## 7. Histórico e Gerenciamento de Dados
- Visualização completa do histórico de informações registradas.
- Exclusão de dados específicos do histórico.
- Atualização automática dos relatórios após alterações.

## 8. Exemplos de Perguntas que o Chat Deve Responder
- Como posso economizar no supermercado?
- O que é uma reserva de emergência?
- Qual a diferença entre gasto fixo e gasto variável?
- Como funciona o cartão de crédito?
- Qual a melhor forma de começar a poupar?
- O que significa taxa de juros?
- Como posso organizar meu orçamento mensal?
- Qual a importância de ter metas financeiras?

---

## Reflexão:
### O que funcionou bem?  
O refinamento do PRD no Copilot de fato ajudou bastante, ficou tudo bem claro para mim quanto ao que foi expressado para a ferramenta realizar.
O registro de metas com acompanhamento percentual de alcance, o registro de gastos e proventos e o relatório gráfico, ficaram bem de acordo com o desejado.
A possibilidade de excluir informações ou metas também ficou dentro do esperado.

### O que não funcionou como o esperado?  
Devido a limitação de solicitações grátis, o processo de histórico do chat ficou diferente do esperado podendo ser ajustado através do Lovable em solicitações posteriores.

### O que aprendeu sobre conversar com IAs?
Aprendi que tudo se complementa. 
Quando já existe uma ideia preestabelecida ou uma tendência a criatividade fica muito fluido obter retorno assertivo das informações solicitadas. 
É como conversar com uma pessoa.

