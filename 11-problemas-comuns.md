# 11. Problemas comuns

← [Índice](./index.md)

---

## Não consigo fazer login

Neste artigo, você encontra as causas mais comuns para problemas de acesso e como resolvê-los.

### Possíveis causas e soluções

**Senha incorreta**
Tente recuperar sua senha em **Esqueci minha senha** na tela de login. Você receberá um link de redefinição no e-mail cadastrado.

**Conta ainda não ativada**
Se você foi convidado recentemente, verifique o e-mail de convite e clique no link de aceite antes de tentar fazer login.

**Usuário inativo na empresa**
Um Administrador ou Proprietário pode ter desativado o seu acesso à empresa. Entre em contato com o responsável pela conta para solicitar a reativação.

**Empresa sem acesso ativo**
Se a assinatura da empresa estiver vencida ou cancelada, o acesso é suspenso. O Proprietário da conta precisa regularizar o faturamento.

### Artigos relacionados

- [Como fazer login na ObraDoc](./02-conta-e-acesso.md#como-fazer-login-na-obradoc)
- [Como recuperar minha senha](./02-conta-e-acesso.md#como-recuperar-minha-senha)
- [Como funciona o primeiro acesso](./02-conta-e-acesso.md#como-funciona-o-primeiro-acesso)

---

## Não consigo enviar arquivos

Neste artigo, você encontra as causas mais comuns para falhas no envio de arquivos.

### Possíveis causas e soluções

**Nome de arquivo inválido**
A ObraDoc valida o nome do arquivo antes do upload. Verifique se o nome segue as regras de nomenclatura:
- Campos separados por `-`
- Revisão no formato `R00`, `R01`, `R02` ao final do nome
- Comprimento máximo de cada campo respeitado

Consulte o artigo [Como funcionam as regras de validação da nomenclatura](./05-nomenclatura.md#como-funcionam-as-regras-de-validação-da-nomenclatura) para ver os erros mais comuns.

**Disciplina restrita**
Se a disciplina for administrativa, apenas Proprietários e Administradores podem enviar arquivos. Coordenadores e Projetistas não têm acesso.

**Limite de armazenamento atingido**
Verifique em **Configurações > Plano** se o limite de armazenamento do plano foi atingido. Nesse caso, nenhum novo arquivo pode ser enviado até que o espaço seja liberado ou o plano atualizado.

**Perfil sem permissão**
Usuários com perfil **Equipe de Campo** não podem enviar arquivos. Verifique seu perfil de projeto com o responsável da obra.

### Artigos relacionados

- [Como enviar arquivos](./04-arquivos.md#como-enviar-arquivos)
- [Como funcionam as regras de validação da nomenclatura](./05-nomenclatura.md#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Quem pode enviar arquivos](./08-permissoes.md#quem-pode-enviar-arquivos)

---

## O arquivo não aparece após o upload

Neste artigo, você entende por que um arquivo pode não aparecer na lista após o envio.

### Possíveis causas e soluções

**A fase exige aprovação**
Se a fase da obra tiver aprovação obrigatória, o arquivo ficará com status **Em análise** e só será visível para Administradores e Coordenadores. Para Projetistas e Equipe de Campo, o arquivo só aparece após ser aprovado.

**Upload incompleto**
O processo de upload tem três etapas: validação do nome, envio para o armazenamento e confirmação do registro. Se qualquer etapa falhar, o arquivo pode não ter sido salvo. Tente novamente.

**Filtro ativo na listagem**
Verifique se há filtros de disciplina, fase ou status ativos na listagem de documentos que estejam ocultando o arquivo.

### Artigos relacionados

- [Como enviar arquivos](./04-arquivos.md#como-enviar-arquivos)
- [Como visualizar um arquivo](./04-arquivos.md#como-visualizar-um-arquivo)
- [Como funciona o fluxo de aprovação](./06-fluxos-de-aprovacao.md#como-funciona-o-fluxo-de-aprovação)

---

## Não consigo aprovar um arquivo

Neste artigo, você entende por que pode não ter acesso à aprovação de arquivos.

### Possíveis causas e soluções

**Perfil sem permissão**
Somente Proprietários, Administradores e Coordenadores da obra podem aprovar arquivos. Se você tem perfil de Projetista ou Equipe de Campo, não terá acesso à fila de aprovação.

**A fase não exige aprovação**
Se a fase da obra não tiver aprovação obrigatória, os arquivos ficam disponíveis para todos imediatamente após o upload — não há nada a aprovar.

**O arquivo já foi aprovado**
Se o arquivo já estiver com status **Liberado**, ele não aparecerá na fila de aprovação.

### Artigos relacionados

- [Como aprovar arquivos](./06-fluxos-de-aprovacao.md#como-aprovar-arquivos)
- [Quem pode aprovar arquivos](./06-fluxos-de-aprovacao.md#quem-pode-aprovar-arquivos)
- [Quais perfis de usuário existem](./08-permissoes.md#quais-perfis-de-usuário-existem)

---

## A plataforma está lenta ou não carrega corretamente

Neste artigo, você encontra os primeiros passos para resolver problemas de desempenho ou carregamento.

### O que tentar

1. **Atualize a página** com `Ctrl+F5` (ou `Cmd+Shift+R` no Mac) para limpar o cache do navegador.
2. **Verifique sua conexão com a internet.** A ObraDoc requer conexão estável, especialmente para upload de arquivos.
3. **Tente outro navegador.** Chrome, Edge e Firefox atualizados são os navegadores recomendados.
4. **Desative extensões do navegador** que possam interferir, como bloqueadores de anúncios.
5. **Tente em uma aba anônima** para descartar problemas de cache ou extensões.

Se o problema persistir após essas tentativas, entre em contato com o suporte informando o navegador utilizado e uma descrição do que está acontecendo.

### Artigos relacionados

- [Como entrar em contato com o suporte](./12-suporte.md#como-entrar-em-contato-com-o-suporte)
- [Quais informações enviar para agilizar o atendimento](./12-suporte.md#quais-informações-enviar-para-agilizar-o-atendimento)
