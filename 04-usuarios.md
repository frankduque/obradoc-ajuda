# 4. Usuários e permissões

← [Índice](./index.md)

---

## Como convidar um usuário para a ObraDoc

Neste artigo, você aprende como adicionar usuários à sua conta na ObraDoc.

### Antes de começar

Apenas **Proprietários** e **Administradores** podem convidar novos usuários. Os usuários precisam estar cadastrados na conta antes de serem adicionados à equipe de uma obra.

### Passo a passo

1. No menu principal, acesse **Usuários**.
2. Clique em **Convidar usuário**.
3. Informe o **e-mail** do usuário a ser convidado.
4. Selecione o **perfil de empresa**: `Administrador` ou `Usuário`.
5. Clique em **Enviar convite**.

O usuário receberá um e-mail com o link de aceite. Após aceitar o convite e definir sua senha, ele estará disponível na plataforma para ser adicionado à equipe das obras.

### Gerenciar usuários existentes

Na lista de usuários, você pode:

- **Desativar um usuário** — suspende o acesso do usuário à plataforma sem removê-lo.
- **Reativar um usuário** — restaura o acesso de um usuário desativado.
- **Alterar o perfil de empresa** — muda o perfil entre Administrador e Usuário.
- **Cancelar convite pendente** — cancela um convite que ainda não foi aceito.

### Resultado esperado

Ao final, o usuário convidado ficará disponível na plataforma para seleção na definição da equipe das obras.

### Artigos relacionados

- [Como criar uma obra](./05-gestao-de-obras.md#como-criar-uma-obra)
- [Como definir a equipe de uma obra](./05-gestao-de-obras.md#como-definir-a-equipe-de-uma-obra)
- [Quais perfis de usuário existem](#quais-perfis-de-usuário-existem)

---

## Quais perfis de usuário existem

Neste artigo, você conhece os perfis de acesso disponíveis na ObraDoc.

### Perfis de empresa (tenant)

Esses perfis controlam o que o usuário pode fazer dentro da conta da empresa.

| Perfil | Como é atribuído | Descrição |
|---|---|---|
| **Proprietário** | Criador da conta | Acesso completo, incluindo assinatura e cancelamento do plano. Não pode ser removido. |
| **Administrador** | Convidado como `admin` | Gerencia obras, membros, disciplinas e aprovações. Não acessa faturamento. |
| **Usuário** | Convidado como `user` | Acesso às obras com base no perfil de projeto atribuído. |

> **Importante:** Ao convidar alguém, você escolhe entre dois perfis de empresa: `admin` (Administrador) ou `user` (Usuário). O perfil Proprietário não pode ser compartilhado via convite.

### Perfis de projeto (obra)

Esses perfis controlam o acesso dentro de uma obra específica.

| Perfil | Descrição |
|---|---|
| **Coordenador** | Aprova documentos, visualiza revisões obsoletas e envia arquivos para qualquer disciplina não restrita. |
| **Projetista** | Envia e visualiza documentos nas disciplinas e fases às quais foi associado. |
| **Equipe de Campo** | Visualiza apenas documentos com status **Liberado** nas disciplinas e fases às quais tem acesso. |

### Artigos relacionados

- [Como funcionam as permissões de acesso](#como-funcionam-as-permissões-de-acesso)
- [Como definir a equipe de uma obra](./05-gestao-de-obras.md#como-definir-a-equipe-de-uma-obra)
- [Glossário da ObraDoc](./01-visao-geral.md#glossário-da-obradoc)

---

## Como funcionam as permissões de acesso

Neste artigo, você entende como as permissões de acesso funcionam na ObraDoc.

### Dois níveis de permissão

A ObraDoc usa dois níveis de permissão independentes:

1. **Permissão de empresa** — define o que o usuário pode fazer na conta da empresa (gerenciar membros, obras, configurações, aprovações).
2. **Permissão de projeto** — define o que o usuário pode fazer dentro de uma obra específica (enviar arquivos, aprovar, visualizar).

Um usuário precisa ter acesso nos dois níveis para trabalhar em uma obra. Um Administrador (empresa) que não estiver na equipe de uma obra ainda assim pode visualizá-la — mas apenas Coordenadores e Projetistas atribuídos podem enviar arquivos.

### Regra das disciplinas restritas

Disciplinas marcadas como **restritas** só aceitam upload de **Proprietários** e **Administradores** da empresa — coordenadores de projeto não têm essa permissão, a menos que a regra seja sobrescrita no nível do tenant.

### Artigos relacionados

- [Quais perfis de usuário existem](#quais-perfis-de-usuário-existem)
- [Quem pode visualizar arquivos](#quem-pode-visualizar-arquivos)
- [Quem pode enviar arquivos](#quem-pode-enviar-arquivos)
- [O que são disciplinas restritas](#o-que-são-disciplinas-restritas)

---

## O que são disciplinas restritas

Neste artigo, você entende o que são disciplinas restritas na ObraDoc.

### Visão geral

Disciplinas restritas são disciplinas usadas para organizar documentos com acesso limitado dentro da plataforma. O envio de arquivos para essas disciplinas é permitido apenas para usuários com perfil de **Administrador** ou **Proprietário** da conta.

### Como funcionam

Essas disciplinas ajudam a separar documentos sensíveis ou de acesso controlado dos demais documentos da obra. Coordenadores e projetistas não conseguem enviar arquivos para disciplinas marcadas como restritas.

### Pontos importantes

- Disciplinas restritas são usadas para conteúdos com acesso limitado.
- O upload para essas disciplinas é reservado a usuários com perfil Administrador ou Proprietário.
- A definição de quais disciplinas são restritas pode ser configurada pelo administrador da conta.

### Artigos relacionados

- [Como gerenciar a biblioteca de disciplinas](./03-configuracoes.md#como-gerenciar-a-biblioteca-de-disciplinas)
- [Quem pode enviar arquivos](#quem-pode-enviar-arquivos)
- [Como funcionam as regras de validação da nomenclatura](./06-arquivos.md#como-funcionam-as-regras-de-validação-da-nomenclatura)

---

## Quem pode visualizar arquivos

Neste artigo, você entende quais perfis têm permissão para visualizar arquivos na ObraDoc.

### Regra geral

A visibilidade de arquivos depende do **status do documento** e do **perfil do usuário**:

| Perfil | Vê documentos em análise? | Vê documentos liberados? | Vê documentos obsoletos? |
|---|---|---|---|
| Proprietário | ✅ Sim | ✅ Sim | ✅ Sim |
| Administrador | ✅ Sim | ✅ Sim | ✅ Sim |
| Coordenador | ✅ Sim | ✅ Sim | ✅ Sim |
| Projetista | ❌ Não | ✅ Sim | ❌ Não |
| Equipe de Campo | ❌ Não | ✅ Sim | ❌ Não |

> **Observação:** Quando uma fase **não** exige aprovação, todos os membros veem o documento imediatamente após o upload, independentemente do status.

### Artigos relacionados

- [Quem pode enviar arquivos](#quem-pode-enviar-arquivos)
- [Como funcionam as permissões de acesso](#como-funcionam-as-permissões-de-acesso)
- [Como visualizar um arquivo](./06-arquivos.md#como-visualizar-um-arquivo)

---

## Quem pode enviar arquivos

Neste artigo, você entende quais perfis têm permissão para enviar arquivos na ObraDoc.

### Regra geral

O envio de arquivos está disponível para **Proprietários**, **Administradores**, **Coordenadores** e **Projetistas** — desde que tenham acesso à obra e à disciplina em questão.

| Perfil | Pode enviar arquivos? | Restrições |
|---|---|---|
| Proprietário | ✅ Sim | Nenhuma |
| Administrador | ✅ Sim | Nenhuma |
| Coordenador | ✅ Sim | Não pode enviar para disciplinas restritas |
| Projetista | ✅ Sim | Apenas nas disciplinas e fases às quais foi associado |
| Equipe de Campo | ❌ Não | — |

### Disciplinas restritas

Disciplinas configuradas como restritas só aceitam upload de Proprietários e Administradores. Coordenadores e Projetistas não têm essa permissão por padrão.

### Artigos relacionados

- [Quem pode visualizar arquivos](#quem-pode-visualizar-arquivos)
- [Como funcionam as permissões de acesso](#como-funcionam-as-permissões-de-acesso)
- [Como enviar arquivos](./06-arquivos.md#como-enviar-arquivos)
- [O que são disciplinas restritas](#o-que-são-disciplinas-restritas)
