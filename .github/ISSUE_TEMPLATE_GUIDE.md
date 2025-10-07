# 📋 Guia de Templates de Issues

## Visão Geral

Este sistema utiliza **templates de issues** estruturados para facilitar a comunicação entre professores e o sistema. Os templates garantem que todas as informações necessárias sejam fornecidas, permitindo que agentes de codificação automatizados (como GitHub Copilot) possam processar e implementar as solicitações sem necessidade de esclarecimentos adicionais.

## 🎯 Por que usar Templates de Issues?

### Benefícios para Professores
- ✅ **Não precisa saber programar** - Apenas preencher formulários
- ✅ **Campos guiados** - Sabe exatamente que informação fornecer
- ✅ **Menos erros** - Validação automática de campos obrigatórios
- ✅ **Mais rápido** - Não precisa escrever descrições longas
- ✅ **Resultados melhores** - Informação completa = implementação correta

### Benefícios para o Sistema
- ✅ **Automação** - Copilot pode ser diretamente designado às issues
- ✅ **Consistência** - Todas as issues seguem o mesmo padrão
- ✅ **Rastreabilidade** - Histórico completo de mudanças
- ✅ **Documentação** - Issues servem como documentação de requisitos

## 📝 Templates Disponíveis

### 1. 🎓 Adicionar Nova Atividade Extracurricular
**Quando usar:** Para criar uma nova atividade para estudantes

**Informações necessárias:**
- Nome e descrição da atividade
- Tipo/categoria (Esportes, Artes, Música, etc.)
- Capacidade máxima de participantes
- Dias da semana e horários
- Professor responsável

**Exemplo de uso:**
> Criar "Clube de Robótica" que acontece às terças e quintas das 15:30 às 17:00, com capacidade para 15 alunos, sob responsabilidade do teacher.silva

### 2. ✏️ Modificar Atividade Existente
**Quando usar:** Para alterar detalhes de uma atividade já cadastrada

**Informações necessárias:**
- Nome da atividade a modificar
- Campos que deseja alterar (descrição, horário, capacidade, etc.)
- Novos valores para cada campo
- Motivo da modificação
- Como tratar participantes já inscritos

**Exemplo de uso:**
> Aumentar capacidade do "Chess Club" de 12 para 20 alunos devido à alta demanda

### 3. 🗑️ Remover Atividade
**Quando usar:** Para remover uma atividade do sistema

**Informações necessárias:**
- Nome da atividade a remover
- Motivo da remoção
- Como tratar estudantes inscritos
- Tipo de remoção (permanente ou desativação)

**Exemplo de uso:**
> Remover "Drama Club" porque o professor responsável se aposentou e não há substituto

### 4. 👨‍🏫 Gerenciar Conta de Professor
**Quando usar:** Para adicionar, modificar ou remover professores

**Informações necessárias:**
- Tipo de ação (adicionar/modificar/remover)
- Username do professor
- Nome para exibição
- Função (TEACHER ou ADMIN)
- Responsabilidades

**Exemplo de uso:**
> Adicionar novo professor "teacher.santos" (Prof. Maria Santos) como TEACHER para gerenciar atividades de música

### 5. 🐛 Reportar Bug
**Quando usar:** Para reportar problemas ou erros no sistema

**Informações necessárias:**
- Descrição clara do bug
- Passos para reproduzir
- Comportamento esperado vs. atual
- Gravidade e frequência
- Área afetada (frontend, backend, etc.)

**Exemplo de uso:**
> Quando tento inscrever um estudante no "Art Club", recebo erro 500 e a inscrição não é registrada

### 6. ✨ Solicitar Nova Funcionalidade
**Quando usar:** Para sugerir novas funcionalidades para o sistema

**Informações necessárias:**
- Descrição da funcionalidade
- Problema que resolve
- Solução proposta
- Categoria e prioridade
- Critérios de aceitação detalhados

**Exemplo de uso:**
> Adicionar funcionalidade de exportar lista de participantes para Excel para facilitar relatórios mensais

### 7. 🎨 Melhorias de Interface (UI/UX)
**Quando usar:** Para sugerir melhorias na aparência ou usabilidade

**Informações necessárias:**
- Tipo de melhoria (visual, usabilidade, acessibilidade, etc.)
- Página/componente afetado
- Estado atual e melhoria proposta
- Por que a melhoria é necessária

**Exemplo de uso:**
> Melhorar responsividade dos filtros em mobile - atualmente ficam muito comprimidos na tela pequena

### 8. 📚 Melhorar Documentação
**Quando usar:** Para solicitar melhorias na documentação

**Informações necessárias:**
- Tipo de documentação (README, guia de uso, API, etc.)
- Tipo de ação (adicionar, corrigir, melhorar)
- Problema atual e melhoria proposta
- Público-alvo

**Exemplo de uso:**
> Adicionar guia passo a passo para professores sobre como usar o sistema pela primeira vez

## 🚀 Como Usar os Templates

### Passo 1: Acessar Issues
1. Vá para a aba **Issues** no repositório GitHub
2. Clique no botão verde **New Issue**

### Passo 2: Escolher Template
Você verá uma lista de templates disponíveis. Escolha o que melhor se adequa à sua necessidade:

```
🎓 Adicionar Nova Atividade Extracurricular
✏️ Modificar Atividade Existente
🗑️ Remover Atividade
👨‍🏫 Gerenciar Conta de Professor
🐛 Reportar Bug
✨ Solicitar Nova Funcionalidade
🎨 Melhorias de Interface (UI/UX)
📚 Melhorar Documentação
```

### Passo 3: Preencher Formulário
- Preencha **todos os campos marcados com asterisco (*)** - são obrigatórios
- Seja específico e detalhado nas descrições
- Para campos de múltipla escolha, selecione todas as opções aplicáveis
- Adicione screenshots ou exemplos quando possível

### Passo 4: Revisar e Submeter
- Revise todas as informações fornecidas
- Verifique se não faltou nenhum detalhe importante
- Clique em **Submit new issue**

### Passo 5: Designar Copilot (Opcional)
Para issues que podem ser automatizadas:
1. Após criar a issue, adicione a label `copilot-assignable` se ainda não tiver
2. Mencione `@copilot` na issue para designar o agente
3. O Copilot processará a issue e criará um Pull Request com as mudanças

## 💡 Dicas para Boas Issues

### ✅ Faça:
- **Seja específico:** Quanto mais detalhes, melhor
- **Use exemplos:** Exemplos concretos ajudam a entender
- **Forneça contexto:** Explique o "porquê", não só o "o quê"
- **Adicione screenshots:** Uma imagem vale mil palavras
- **Verifique duplicatas:** Busque se já existe issue similar

### ❌ Evite:
- **Ser vago:** "Melhorar sistema" não é suficiente
- **Múltiplos pedidos:** Uma issue = uma solicitação
- **Informações incompletas:** Preencha todos os campos obrigatórios
- **Linguagem técnica desnecessária:** Use linguagem simples
- **Expectativas irrealistas:** Considere limitações técnicas

## 📊 Acompanhamento de Issues

### Status das Issues
- **Open:** Issue criada, aguardando processamento
- **In Progress:** Copilot ou desenvolvedor trabalhando na issue
- **Closed:** Issue resolvida e implementada

### Labels Importantes
- `copilot-assignable`: Pode ser processada automaticamente pelo Copilot
- `enhancement`: Melhoria ou nova funcionalidade
- `bug`: Correção de erro
- `activity`: Relacionado a atividades extracurriculares
- `teacher`: Relacionado a contas de professores
- `ui-ux`: Relacionado à interface do usuário
- `documentation`: Relacionado à documentação

### Notificações
- Você receberá notificações quando houver atualizações na sua issue
- Responda a comentários se mais informações forem necessárias
- Teste a implementação quando o Pull Request for criado

## 🤖 Como o Copilot Processa Issues

1. **Análise:** Copilot lê todos os campos da issue
2. **Planejamento:** Cria um plano de implementação
3. **Implementação:** Faz as mudanças necessárias no código
4. **Testes:** Executa testes para garantir qualidade
5. **Pull Request:** Cria PR com as mudanças para revisão
6. **Revisão:** PR é revisado antes de ser mesclado

## 📞 Precisa de Ajuda?

- **Dúvidas sobre templates:** Consulte este guia
- **Dúvidas técnicas:** Consulte [docs/README.md](../docs/README.md)
- **Discussões gerais:** Use [GitHub Discussions](../../discussions)
- **Problemas urgentes:** Mencione `@admin` na issue

## 📚 Recursos Adicionais

- [Documentação Completa do Sistema](../docs/README.md)
- [Guia de Contribuição](../CONTRIBUTING.md) (se existir)
- [GitHub Issues Documentation](https://docs.github.com/en/issues)

---

**Última atualização:** Outubro 2024  
**Versão:** 1.0  
**Mantido por:** Equipe de Desenvolvimento - Mergington High School
