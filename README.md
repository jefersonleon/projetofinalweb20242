# Projeto Final - Desenvolvimento em PHP

**Descrição:** Este é o projeto final do curso. O tema do sistema será definido pelo(s) aluno(s), e deverá incluir funcionalidades mínimas obrigatórias, além de pelo menos um requisito especial à escolha do grupo.

## Requisitos Obrigatórios
Todos os projetos devem incluir as seguintes funcionalidades:

1. **CRUDs Funcionais:**
   - Cada entidade deve permitir: criar, listar, editar e excluir registros.

2. **Autenticação de Usuários:**
   - Login com senha segura (mínimo 8 caracteres, incluindo letras, números e caracteres especiais).
   - Logout funcional.

3. **Validação de Dados:**
   - Validações no *frontend* (JavaScript) e no *backend* (PHP).
   - Exemplo: campos obrigatórios, formatos válidos (e-mails, CPF, etc.).

4. **Interface Responsiva:**
   - Layout que se adapte a diferentes tamanhos de tela (pode usar frameworks como Bootstrap).

## Requisitos Especiais (Escolha pelo Menos 1)
Cada projeto deverá incluir, obrigatoriamente, pelo menos um dos requisitos abaixo:

- **Consumo de API Externa:** 
  - Utilize uma API pública para adicionar uma funcionalidade ao sistema.  
  - Exemplos:
    - API ViaCEP: preenchimento automático de endereços.
    - API OpenWeather: exibição da previsão do tempo.
- **Geração de Relatórios em PDF:**
  - Crie relatórios dinâmicos que podem ser baixados pelo usuário.
  - Ferramenta sugerida: [DOMPDF](https://github.com/dompdf/dompdf) ou [FPDF](http://www.fpdf.org/).
- **Envio de E-mails:**
  - Envie notificações automáticas ou confirmações (ex.: cadastro ou recuperação de senha).
  - Ferramenta sugerida: [PHPMailer](https://github.com/PHPMailer/PHPMailer).
- **Recuperação de Senha:**
  - Permita ao usuário redefinir sua senha.
  - Sugestão: simular envio de link para redefinição.
- **Paginação e Filtro em Listagens:**
  - Inclua paginação e busca avançada nas tabelas do sistema.
- **Upload de Arquivos:**
  - Permita upload de imagens ou documentos, com validações (ex.: tipo e tamanho do arquivo).

## Tecnologias Recomendadas
- **Linguagens:** PHP, MySQL, HTML, CSS, JavaScript.
- **Frameworks:** Bootstrap (opcional).
- **Bibliotecas:** PHPMailer, DOMPDF, ou outras que ajudem no desenvolvimento.

## Estrutura de Entregas
1. **Repositório no GitHub:**
   - Crie um repositório com o nome: `ProjetoFinal_<SeuNomeOuGrupo>`.
   - Mantenha commits frequentes e com mensagens claras.
   - Organize os arquivos em pastas (ex.: `/css`, `/js`, `/php`, `/assets`).

2. **Datas Importantes:**
   - **Definição do Tema:** Até [data].
   - **Protótipo Inicial:** Até [data].
   - **Entrega Final:** Até [data].

3. **Checklist de Requisitos:**
   - [ ] CRUD de [entidade 1].
   - [ ] CRUD de [entidade 2].
   - [ ] Login funcional.
   - [ ] Escolha do requisito especial: **[Nome do Requisito]**.
   - [ ] Responsividade implementada.
   - [ ] Validações no frontend e backend.

## Avaliação
- **Funcionalidade (50%):** Requisitos obrigatórios e especiais implementados.
- **Código (20%):** Organização, boas práticas e uso do GitHub.
- **Interface (20%):** Layout intuitivo e responsivo.
- **Apresentação (10%):** Clareza na demonstração do projeto.

---

### Dicas
1. **Escolha um Tema Simples e Focado:** Exemplo: um sistema de gerenciamento (clientes, produtos, pedidos, etc.).
2. **Priorize os Requisitos Obrigatórios:** Garanta que o básico funcione antes de adicionar o requisito especial.
3. **Use o GitHub para Organização:** Crie commits frequentes e mantenha o histórico atualizado.
4. **Trabalhem em Equipe:** Dividam tarefas para aproveitar melhor o tempo (em caso de grupos).


