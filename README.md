# Desafio de QA - Beedoo 2026 🚀

Olá! Este é o meu caso de teste para o desafio de QA da Beedoo. Aqui eu realizei o desenvolvimento e os testes de um módulo de cadastro e listagem de cursos.

## 🔗 Link do Projeto
Você pode acessar a aplicação rodando ao vivo aqui:
👉 [https://creative-sherbet-a51eac.netlify.app/](https://creative-sherbet-a51eac.netlify.app/)

---

 📝 Descrição do programa:
- Cadastro de Cursos: Trata-se de  um formulário onde é possível dar nome e detalhes aos cursos.
- Listagem: Os cursos aparecem logo abaixo assim que são cadastrados.
- Testes Manuais: Testei cada campo para garantir que tudo está funcionando como deveria.

 🛠️ Tecnologias usadas no programa:
- HTML5 e CSS3 (para a estrutura e o visual)
- JavaScript (para a lógica de cadastrar e listar)
- Netlify (para colocar o site no ar)

---

 🧪 Como foi realizado o teste:
1. Clique no link do projeto acima.
2. Tente cadastrar um curso preenchendo as informações.
3. Verifique se o curso apareceu na lista.
4. Tente deixar algum campo vazio para ver como o sistema se comporta.
5. Verifiquei se há dificuldade em cadastrar novos cursos.
6. Verifiquei a vulnerabilidade do programa.

---

🤔 Reflexão sobre o desafio
Responda brevemente:

- Qual foi o bug mais interessante que você encontrou durante o desafio?
  
O bug mais interessante que encontrei foi o fato de o curso após criado não poder ser excluído.
  
- Qual foi o cenário de teste mais difícil de pensar?
  
 Foi o que se refere a busca de imagens para fazer a URL da capa. Perdi muito tempo procurando uma imagem autorizada e não ficou bom.
  
- O que você faria diferente se tivesse mais tempo para testar a aplicação?

Colocaria o nome da empresa no formulário do curso, retiraria a url da capa e no lugar já acrescentava o logo da empresa, já acrescentaria uma palavra linkada para abrir uma página de condições de pagamento, parcelamento, débito, crédito.

🗒️ Erros encontrados no programa:
1. O programa permite deixar espaços em branco. Não emite nenhum aviso de que espaços em branco não são permitidos.
2. A função excluir curso não está funcionando. A mensagem aparece mas o curso cadastrado continua lá.
3. Falta um espaço onde o administrador do programa possa entrar para editar e corrigir algum erro no curso cadastrado.
4. Qualquer pessoa pode entrar e cadastrar cursos, mostrando a vulnerabilidade do sistema. Não existe uma senha administrativa.
5. Acredito que o fundo de cada caixa de curso já deveria vir com um plano de fundo, evitando assim, mais tempo para cadastrar o curso.
6. Falta um ítem de editar, para que se possa corrigir algum erro ao cadastrar o curso, logicamente permitido apenas para o(s) administrador(es).
7. Falta uma página mostrando o valor de cada curso, as condições de pagamento, parcelamento, uso de cartões e, consequentemente uma segurança para o usuário.

---
Link da planilha de testes:
https://us.docworkspace.com/d/sIJiz_YDRAoLCwM0G

Link dos prints de vulnerabilidades:
https://docs.google.com/document/d/1aDa0HzaaFeepoBdKflLnuoBi1OI-ShUv/edit?usp=sharing&ouid=110739296009895388008&rtpof=true&sd=true

**Feito por [Mirna]** *Buscando minha primeira oportunidade como Desenvolvedor Front-End / QA.*
