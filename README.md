# 🚀 Desafio QA Beedoo 2026 - Cadastro e Listagem de Cursos

Este repositório contém a solução para o desafio de QA, focado na validação das funcionalidades de **Cadastro** e **Listagem** de cursos na plataforma.

## 🌐 Link da Aplicação (Live Demo)
Acesse a aplicação hospedada na Netlify para realizar os testes manuais:
👉 [https://creative-sherbet-a51eac.netlify.app/](https://creative-sherbet-a51eac.netlify.app/)

---

## 🛠️ Tecnologias Utilizadas
* **Desenvolvimento:** HTML5, CSS3, JavaScript.
* **Hospedagem:** Netlify.
* **Testes (Planejamento):** [Insira aqui se usou Cypress, Playwright ou Testes Manuais].

---

## 📋 Funcionalidades Testadas

### 1. Módulo de Cadastro
* **Cenário de Sucesso:** Verificação se o curso é salvo corretamente ao preencher todos os campos.
* **Validações:** * Campos obrigatórios (Nome, Descrição, Carga Horária).
  * Formato de dados (ex: Carga horária aceitando apenas números).
  * Feedback visual após o cadastro.

### 2. Módulo de Listagem
* **Exibição:** Garantir que os dados cadastrados aparecem exatamente como inseridos.
* **Responsividade:** Verificar se a lista de cursos se ajusta a dispositivos móveis (Mobile-first).
* **Persistência:** Teste de recarregamento da página (verificar se os dados permanecem ou se resetam).

---

## 🧪 Como Executar os Testes

### Testes Manuais
1. Acesse o link da aplicação: https://creative-sherbet-a51eac.netlify.app/
2. Tente cadastrar um curso sem preencher o nome e observe a reação do sistema.
3. Cadastre um curso válido e verifique se ele aparece na lista abaixo do formulário.

### Testes Automatizados (Opcional - caso você tenha criado)
```bash
# Exemplo para Cypress
npm install
npx cypress open
