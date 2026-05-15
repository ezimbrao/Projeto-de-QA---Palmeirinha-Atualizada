📌 Projeto de QA - Palmeirinha Atualizada
🧠 Visão Geral

O Projeto Palmeirinha Atualizada consiste no desenvolvimento de uma API de gerenciamento de receitas, com foco em boas práticas de Qualidade de Software (QA), incluindo planejamento de testes, automação e organização de projeto.

A proposta é simular um ambiente real de squad de QA, aplicando conceitos de organização, validação e melhoria contínua.

👥 Identificação da Squad
🏷️ Nome da equipe


Palmeirinha Atualizada


👨‍💻 Integrantes e Funções
Nome	Função
Arthur Mattos	Desenvolvedor (Dev)
Enzo Zimbrão	Desenvolvedor (Dev)
Giovanna Bottcher	Documentação (Doc)
Ian Oliveira	Desenvolvedor (Dev)
Paulo Gomes	Documentação (Doc)


💡 Ideia do Projeto
📛 Nome do sistema


API de Receitas - Palmeirinha


🎯 Objetivo principal


Criar uma API para cadastro, gerenciamento e organização de receitas culinárias.


👥 Público-alvo


Pessoas que gostam de cozinhar e desejam organizar suas receitas de forma prática.


⚠️ Problema que o sistema resolve


Muitas pessoas perdem receitas ou não possuem um sistema centralizado para organizá-las de forma eficiente.


🔄Fluxo Visual do Sistema


📱 Fluxo de telas


Tela principal de cadastro de receitas
Listagem de receitas cadastradas
Edição e exclusão de receitas


🧭 Navegação



Interface simples e direta

Navegação baseada em ações CRUD (Create, Read, Update, Delete)



🏗️ Estrutura do sistema


API REST
Backend responsável pelas regras de negócio
Integração com banco de dados


👤 Processo principal do usuário


Usuário acessa o sistema
Cadastra uma receita
Adiciona ingredientes e instruções
Salva a receita
Pode editar ou excluir posteriormente




🧪 Planejamento de QA


✅ Casos de teste


Cadastro válido de receita
Cadastro com título inválido
Cadastro com menos de 3 ingredientes
Cadastro com campos vazios
Cadastro com exatamente 3 ingredientes
Cadastro com mais de 3 ingredientes
Limpeza dos campos do formulário



🎭 Cenários de teste


Usuário cadastra receita corretamente
Usuário tenta cadastrar com dados incompletos
USuário insere dados inválidos



⚙️ Testes funcionais


Validação de campos obrigatórios
Persistência correta dos dados
Retorno adequado da API



❌ Testes negativos


Campos vazios
Dados inválidos
InpuTs incompletos
Falha na estrutura da requisição



⚠️ Possíveis falhas esperadas


Erros de validação
Falhas de conexão com banco
Dados inconsistentes
Problemas de formatação


🤖 Automação

🧩 Estratégia de automação

Automatizar testes principais da API para garantir consistência e evitar regressões.

🛠️ Ferramentas utilizadas


Postman / Insomnia
(Possível) Jest / Supertest
(Possível) Cypress para integração



📜 Scripts desenvolvidos


Scripts de testes automatizados para endpoints
Testes de validação de entrada



🔄 Fluxo automatizado


Requisição enviada
Validação da resposta
Comparação com resultado esperado
Registro de sucesso ou falha



📊 Gestão do Projeto
📋 Organização de tarefas

Separação por áreas: Dev, QA e Documentação
Distribuição entre membros da equipe


🎯 Responsabilidades

Scrum Master / Organização
Front-end
Back-end
QA/Testes
UI/UX + Documentação


✅ Etapas concluídas

Planejamento
Criação do layout
Desenvolvimento inicial
Cadastro de receitas


⏳ Pendências

Finalização dos testes
Ajustes visuais
Implementação de melhorias


📸 Evidências
🖼️ Prints


FigJam da squad
Execução dos testes
Resultados da API


📈 Resultados dos testes


Testes funcionais validados
Identificação de falhas em inputs inválidos


🐞 Bugs encontrados


Validação incorreta de campos
Possíveis falhas em dados incompletos



🚀 Melhorias realizadas


Ajuste nas validações
Melhor organização dos dados
Refinamento da estrutura da API
