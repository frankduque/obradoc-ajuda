# 3. Configurações da conta

← [Índice](./index.md)

---

## Visão geral das configurações

Neste artigo, você entende o que pode ser configurado na conta da ObraDoc e quando fazer isso.

### O que fica em configurações

A área de Configurações reúne os ajustes que valem para toda a conta da empresa — e que afetam todas as obras criadas a partir dali. São elas:

| Configuração | O que define |
|---|---|
| **Nomenclatura** | A estrutura e a ordem dos campos no nome dos arquivos |
| **Biblioteca de disciplinas** | As disciplinas disponíveis para seleção ao criar ou editar uma obra |
| **Biblioteca de fases** | As fases disponíveis para seleção ao criar ou editar uma obra |
| **Biblioteca de localizações** | As localizações disponíveis para uso na nomenclatura |
| **Biblioteca de conteúdos** | Os tipos de conteúdo disponíveis para uso na nomenclatura |
| **Tipos de obra** | Os modelos de obra que preenchem automaticamente disciplinas na criação |

### Quando configurar

Configure antes de criar a primeira obra. Ajustes feitos depois — especialmente na nomenclatura — podem causar inconsistências nos nomes de arquivos já enviados.

### Quem pode acessar

Apenas **Proprietários** e **Administradores** têm acesso às configurações da conta.

### Artigos relacionados

- [Como configurar os campos da nomenclatura](#como-configurar-os-campos-da-nomenclatura)
- [Como gerenciar a biblioteca de disciplinas](#como-gerenciar-a-biblioteca-de-disciplinas)
- [Como gerenciar a biblioteca de fases](#como-gerenciar-a-biblioteca-de-fases)

---

## Como configurar os campos da nomenclatura

Neste artigo, você aprende como ajustar o padrão de nomenclatura da sua operação na ObraDoc.

### Antes de começar

A configuração da nomenclatura fica em **Configurações > Nomenclatura** e só pode ser alterada por administradores.

> ⚠️ A alteração do padrão afeta todos os arquivos — o nome é gerado no momento da visualização e do download.

### Passo a passo

1. No menu principal, acesse **Configurações**.
2. Clique em **Nomenclatura**.
3. Na tela de configuração, você verá os campos disponíveis listados em ordem.
4. Arraste os campos para definir a ordem desejada no nome dos arquivos.
5. Se quiser incluir um **Código Personalizado**, marque o campo correspondente. Ele será sempre posicionado após os demais campos, antes da revisão.
6. Confira a **prévia da nomenclatura** exibida na parte superior da tela.
7. Clique em **Salvar padrão** para concluir.

### Resultado esperado

Ao final, o novo padrão passará a valer para todos os uploads realizados na plataforma.

### Artigos relacionados

- [Como funcionam as regras de validação da nomenclatura](./06-arquivos.md#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Boas práticas de nomenclatura](#boas-práticas-de-nomenclatura)
- [Como enviar arquivos](./06-arquivos.md#como-enviar-arquivos)

---

## Como gerenciar a biblioteca de disciplinas

Neste artigo, você aprende como visualizar, adicionar e ajustar as disciplinas disponíveis na sua conta.

### Visão geral

A ObraDoc vem com uma biblioteca global de disciplinas — como Arquitetura, Estrutura, Hidráulica e Elétrica — que pode ser usada diretamente ao criar obras. A biblioteca da conta permite estender essa lista com disciplinas específicas da sua operação ou ajustar os nomes e códigos das existentes.

### Como acessar

No menu principal, acesse **Configurações > Disciplinas**.

### O que você pode fazer

- **Adicionar disciplina** — cria uma nova disciplina disponível para seleção em obras.
- **Editar nome ou código** — ajusta o nome ou o código de uma disciplina existente.
- **Sobrescrever disciplina global** — altera o nome ou código de uma disciplina que vem da biblioteca padrão da plataforma, sem removê-la.
- **Remover disciplina** — remove a disciplina da biblioteca. Disciplinas vinculadas a obras existentes não são afetadas.
- **Restaurar disciplina removida** — recupera uma disciplina que foi removida anteriormente.

### Pontos importantes

- O código da disciplina é usado na validação da nomenclatura. Certifique-se de que ele é único e segue o padrão da sua operação.
- Disciplinas removidas da biblioteca não são automaticamente removidas das obras que já as utilizam.

### Artigos relacionados

- [Como criar uma obra](./05-gestao-de-obras.md#como-criar-uma-obra)
- [Como funcionam as regras de validação da nomenclatura](./06-arquivos.md#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [O que são disciplinas restritas](./04-usuarios.md#o-que-são-disciplinas-restritas)

---

## Como gerenciar a biblioteca de fases

Neste artigo, você aprende como visualizar, adicionar e ajustar as fases disponíveis na sua conta.

### Visão geral

Assim como as disciplinas, as fases vêm de uma biblioteca global da plataforma — como Estudo Preliminar, Anteprojeto, Projeto Executivo e As Built. A biblioteca da conta permite adicionar fases personalizadas ou ajustar as existentes.

### Como acessar

No menu principal, acesse **Configurações > Fases**.

### O que você pode fazer

- **Adicionar fase** — cria uma nova fase disponível para seleção em obras.
- **Editar nome ou código** — ajusta o nome ou o código de uma fase existente.
- **Sobrescrever fase global** — altera o nome ou código de uma fase da biblioteca padrão.
- **Remover fase** — remove a fase da biblioteca. Fases vinculadas a obras existentes não são afetadas.
- **Restaurar fase removida** — recupera uma fase removida anteriormente.

### Pontos importantes

- O código da fase é usado na validação da nomenclatura dos arquivos. Defina códigos curtos, únicos e consistentes entre obras.
- Fases podem ter aprovação obrigatória habilitada ou não — essa configuração é feita dentro de cada obra, não na biblioteca.

### Artigos relacionados

- [Como criar uma obra](./05-gestao-de-obras.md#como-criar-uma-obra)
- [Como funciona o fluxo de aprovação](./07-fluxos-de-aprovacao.md#como-funciona-o-fluxo-de-aprovação)
- [Como funcionam as regras de validação da nomenclatura](./06-arquivos.md#como-funcionam-as-regras-de-validação-da-nomenclatura)

---

## Boas práticas de nomenclatura

Neste artigo, você encontra recomendações para organizar os arquivos da sua operação com mais eficiência na ObraDoc.

### Defina o padrão antes de começar

Configure a ordem dos campos da nomenclatura antes do primeiro upload. Alterar o padrão depois que os arquivos já foram enviados pode causar inconsistências na visualização dos nomes.

### Use códigos curtos e consistentes

Prefira códigos simples, padronizados e fáceis de memorizar. Por exemplo:

- Disciplinas: `ARQ`, `EST`, `HID`, `ELE`
- Fases: `EP`, `AP`, `PE`, `AS`
- Localizações: `PAV`, `COB`, `SS`

### Padronize os códigos entre obras

Se a sua operação tem várias obras, use os mesmos códigos de disciplina e fase em todas elas. Isso facilita a organização e reduz erros no momento do upload.

### Revise os códigos antes de enviar

Antes de enviar arquivos, consulte os códigos disponíveis para a obra clicando em **Ver os códigos de nomenclatura** na tela de upload.

### Corrija erros antes de reenviar

Se o upload falhar por erro de nomenclatura, ajuste o nome do arquivo conforme o padrão indicado antes de tentar novamente. Reenviar com o mesmo nome incorreto resultará no mesmo erro.

### Artigos relacionados

- [Como funcionam as regras de validação da nomenclatura](./06-arquivos.md#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Como configurar os campos da nomenclatura](#como-configurar-os-campos-da-nomenclatura)
- [Como enviar arquivos](./06-arquivos.md#como-enviar-arquivos)
