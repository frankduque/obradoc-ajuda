# 7. Fluxos de aprovação

← [Índice](./index.md)

---

## Como funciona o fluxo de aprovação

Neste artigo, você entende como funciona o processo de aprovação de arquivos na ObraDoc.

### Visão geral

O fluxo de aprovação controla quando os documentos ficam visíveis para toda a equipe da obra. Ele funciona por fase: cada fase pode ou não exigir aprovação, dependendo da configuração do tenant.

Quando um arquivo é enviado para uma fase que exige aprovação, ele entra com o status **Em análise** — visível apenas para administradores e coordenadores. Após a revisão e aprovação, o status muda para **Liberado** e o arquivo passa a ser acessível a todos os membros com permissão naquela disciplina e fase.

### Ciclo de status dos documentos

| Status | Significado | Quem visualiza |
|---|---|---|
| **Em análise** | Aguardando aprovação | Administradores e coordenadores |
| **Liberado** | Aprovado e visível | Todos os membros com acesso |
| **Obsoleto** | Substituído por revisão mais recente | Administradores e coordenadores |

### Pontos importantes

- Nem todas as fases exigem aprovação — depende da configuração da sua operação.
- Fases sem aprovação obrigatória exibem os documentos imediatamente após o upload para todos os membros.
- O fluxo de aprovação pode ser uma funcionalidade exclusiva do plano contratado.

### Artigos relacionados

- [Como aprovar arquivos](#como-aprovar-arquivos)
- [O que significa cada status do fluxo](#o-que-significa-cada-status-do-fluxo)
- [Como funciona o versionamento de arquivos](./06-arquivos.md#como-funciona-o-versionamento-de-arquivos)

---

## Como aprovar arquivos

Neste artigo, você aprende como aprovar arquivos na ObraDoc.

### Antes de começar

Para aprovar arquivos, você precisa ter perfil de **Administrador**, **Proprietário** ou ser **Coordenador** da obra em questão.

### Passo a passo

1. No menu principal, acesse **Aprovação**.
2. Na fila de aprovação, você verá todos os arquivos com status **Em análise** das obras sob sua responsabilidade.
3. Clique no arquivo que deseja revisar para visualizá-lo.
4. Após a revisão, clique em **Liberar** para aprovar o arquivo.
5. O arquivo passará para o status **Liberado** e ficará visível para toda a equipe com acesso àquela disciplina e fase.

### Resultado esperado

O arquivo aprovado fica visível para todos os membros com acesso à disciplina e fase correspondentes. A revisão anterior, se existir, passa automaticamente para o status **Obsoleto**.

### Artigos relacionados

- [Como funciona o fluxo de aprovação](#como-funciona-o-fluxo-de-aprovação)
- [O que significa cada status do fluxo](#o-que-significa-cada-status-do-fluxo)
- [Quem pode aprovar arquivos](#quem-pode-aprovar-arquivos)

---

## O que significa cada status do fluxo

Neste artigo, você entende o significado de cada status de documento no fluxo de aprovação da ObraDoc.

### Em análise

O arquivo foi enviado para uma fase com aprovação obrigatória e aguarda revisão de um administrador ou coordenador. Nesse estado, o documento **não está visível** para projetistas e equipe de campo.

### Liberado

O arquivo foi revisado e aprovado. Ele está visível para todos os membros com acesso à disciplina e fase correspondentes.

### Obsoleto

O arquivo foi substituído por uma revisão mais recente. Isso acontece automaticamente quando um novo arquivo é enviado sobre a mesma revisão. Documentos obsoletos ficam visíveis apenas para administradores e coordenadores.

### Artigos relacionados

- [Como funciona o fluxo de aprovação](#como-funciona-o-fluxo-de-aprovação)
- [Como aprovar arquivos](#como-aprovar-arquivos)
- [Como funciona o versionamento de arquivos](./06-arquivos.md#como-funciona-o-versionamento-de-arquivos)

---

## Quem pode aprovar arquivos

Neste artigo, você entende quais perfis têm permissão para aprovar arquivos na ObraDoc.

### Regra geral

A aprovação de arquivos é restrita a **Administradores**, **Proprietários** e **Coordenadores** da obra à qual o arquivo pertence.

### Como funciona na prática

| Perfil | Acessa a fila de aprovação? | Escopo |
|---|---|---|
| Proprietário | ✅ Sim | Todas as obras do tenant |
| Administrador | ✅ Sim | Todas as obras do tenant |
| Coordenador | ✅ Sim | Apenas as obras em que é coordenador |
| Projetista | ❌ Não | — |
| Equipe de Campo | ❌ Não | — |

### Artigos relacionados

- [Como funciona o fluxo de aprovação](#como-funciona-o-fluxo-de-aprovação)
- [Como aprovar arquivos](#como-aprovar-arquivos)
- [Quais perfis de usuário existem](./04-usuarios.md#quais-perfis-de-usuário-existem)
