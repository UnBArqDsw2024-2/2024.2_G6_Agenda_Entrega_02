# Política de Commits

Este projeto adota o padrão Conventional Commits para garantir mensagens de
commit claras, consistentes e automatizáveis.  Seguir estas diretrizes
facilita a geração de changelogs, automatiza o versionamento semântico e 
facilita a compreensão do histórico do projeto.

## Formato da Mensagem

Cada mensagem de commit deve ser estruturada da seguinte forma:

```
<tipo>[escopo opcional]: <descrição resumida>

<corpo opcional>

<rodapé opcional>
```

## Tipos de Commit

Os seguintes tipos de commit são permitidos:

* **feat:**  Introduz uma nova funcionalidade.
* **fix:** Corrige um bug.
* **docs:**  Alterações apenas na documentação.
* **style:**  Alterações que não afetam o significado do código
(formatação, ponto e vírgula, etc.).
* **refactor:**  Refatoração do código (sem correções de bugs ou novas
funcionalidades).
* **perf:**  Melhora o desempenho.
* **test:**  Adiciona ou modifica testes.
* **chore:**  Alterações na configuração da build, scripts auxiliares, etc.
(sem alteração no código de produção).
* **revert:**  Reverte um commit anterior.

## Escopo

O escopo é opcional e fornece contexto adicional sobre a alteração. Exemplos:
`(api)`, `(ui)`, `(banco de dados)`.

## Descrição Resumida

A descrição resumida deve ser concisa e começar com uma letra maiúscula.  Deve
completar a frase: "Este commit irá...".

## Corpo

O corpo da mensagem é opcional e deve fornecer mais detalhes sobre a alteração,
incluindo a motivação e a implementação. Separe o corpo da descrição 
resumida por uma linha em branco.

## Rodapé

O rodapé é opcional e pode conter informações como breaking changes ou
referências a issues.

### Breaking Changes

Qualquer commit que introduza uma quebra de compatibilidade **deve** incluir
`BREAKING CHANGE:` no rodapé, seguido por uma descrição da alteração e como
migrar. Exemplo:

```
feat: implementar nova API de autenticação

BREAKING CHANGE: A antiga API de autenticação foi removida. Use a nova API
descrita na documentação.
```

### Referência a Issues

As issues relacionadas podem ser referenciadas no rodapé usando a palavra-chave
`Closes`, `Fixes` ou `Resolves`, seguida pelo número da issue. Exemplo:

```
fix: corrigir erro de login

Closes #123
```

## Co-autores

Este projeto suporta o uso de `Co-authored-by` para atribuir crédito a
múltiplos autores em um único commit.  A informação de co-autoria deve ser
adicionada no **rodapé** do commit, após o corpo da mensagem (se houver) e
antes de outros trailers, como `BREAKING CHANGE:` ou referências a issues.

**Formato:**

```
Co-authored-by: Nome do Co-autor <emailcoautor@example.com>
```

Você pode adicionar múltiplas linhas `Co-authored-by` para incluir vários
co-autores.

**Exemplo:**

```
feat(autenticação): adicionar suporte a login com GitHub

Implementar o login com GitHub usando a API do GitHub OAuth.

Co-authored-by: Nome do Co-autor <emailcoautor@example.com>
Co-authored-by: Outro Co-autor <outroemail@example.com>

Closes #123
```

**Integração com Validação de Commits:**

A validação de commits (ex: usando commitlint) geralmente ignora as linhas
`Co-authored-by`.  No entanto, se sua configuração for muito estrita, você pode
precisar ajustar as regras para permitir explicitamente esses trailers no
rodapé, conforme descrito na documentação da sua ferramenta de validação.

**Recomendações:**

* Utilize `Co-authored-by` sempre que houver colaboração significativa em um
commit.
* Mantenha a ordem consistente: `Co-authored-by` antes de outros trailers como
`BREAKING CHANGE:`.

## Exemplos

**Exemplo 1:**

```
feat(autenticação): adicionar suporte a login com Google

Implementar o login com Google usando a API do Google OAuth.
```

**Exemplo 2:**

```
fix: corrigir erro de cálculo no carrinho de compras

O cálculo do total do carrinho estava incorreto devido a um erro de
arredondamento.

Closes #456
```

## Política de Branches

Esta política define a estrutura de branches do projeto e como elas devem ser
utilizadas para organizar o desenvolvimento e garantir a estabilidade do código.

## Tipos de Branches

O projeto utiliza os seguintes tipos de branches:

* **`main`:** A branch principal e estável, representando o estado pronto para
produção do projeto.  Push direto nesta branch é proibido. Todas as alterações
devem ser incorporadas através de merge requests. 
<br>

* **`develop`:**  Uma branch de integração onde as alterações de diferentes
branches de recurso são mescladas antes de irem para a `main`.  Isso permite
testes de integração mais completos antes da liberação para produção. Se optar
por **não** usar a branch `develop`, as branches de artefato/módulo e outras
serão mescladas diretamente na `main`.
<br>

* **`artefato/{nome-do-artefato}` ou `modulo/{nome-do-modulo}`:** Branches
dedicadas ao desenvolvimento de um artefato ou módulo específico.  O nome da
branch deve ser descritivo e refletir a parte do sistema sendo modificada.
  * Exemplos: 

```
`artefato/diagrama-de-classes`; 
`modulo/autenticacao`;
`artefato/documentacao-usuario`.
```

<br>

* **`doc/{nome-da-alteracao-na-documentacao}`:** Branches específicas para
alterações na documentação. 
  * Exemplos: 

```
`doc/tutorial-instalacao`;
`doc/atualizacao-readme`.
```

<br>

* **`infra/{nome-da-tarefa-de-infra}`:** Branches para tarefas relacionadas à
infraestrutura do projeto, como configuração de CI/CD, scripts, automação, etc.
  * Exemplos: 

```
`infra/configurar-ci`;
`infra/adicionar-linter`;
`infra/padronizar-commits`.
```

<br>

## Fluxo de Trabalho

1. **Criação de Branches:**  Todas as novas funcionalidades, correções de bugs,
alterações na documentação ou infraestrutura devem ser feitas em branches
separadas, criadas a partir da `develop`.

2. **Nomenclatura:** Siga as convenções de nomenclatura descritas acima para
cada tipo de branch.

3. **Commits:**  Utilize o padrão Conventional Commits em todas as mensagens
de commit.

4. **Merge Requests:**  Antes de fazer o merge uma branch na `develop`, crie
um pull request.  Isso permite revisão de código e garante a qualidade do
projeto.

5. **Merge na `develop`:** Faça o merge das branches de recursos nela primeiro.

6. **Merge na `main`:** Após a revisão e aprovação do merge request a branch
`develop` deve ser mesclada na `main`.

7. **Exclusão de Branches:**  Após o merge, as branches de recursos,
documentação e infraestrutura devem ser excluídas para manter o repositório
organizado.

* Obs: Se possível o ideal é sempre manter a sua branch, ou repositório local, atualizada utilizando o comando `git pull nome-da-branch-mais atualizada`

## Bibliografia

* [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)
* [Semantic Versioning](https://semver.org/)

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Hugo Melo](https://github.com/melohugo) |  |  |
| `1.01` | 13/11/2024  | Acrescentando informações no artefato. | [Paulo Borba](https://github.com/paulohborba) | 13/11/2024 | [Hugo Melo](https://github.com/melohugo) |
| `1.01` | 18/11/2024  | Corrigindo exemplos. | [Hugo Melo](https://github.com/melohugo) | | |
