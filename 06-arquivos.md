# 6. Arquivos

← [Índice](./index.md)

---

## Como enviar arquivos

Neste artigo, você aprende como enviar arquivos para uma obra na ObraDoc.

### Antes de começar

Para enviar arquivos, a obra já precisa estar criada, com disciplinas e fases cadastradas.

### Passo a passo

1. No painel de Obras, localize a obra desejada.
2. Clique no centro do card da obra para abrir a página da obra.
3. Na página da obra, selecione a **disciplina** e a **fase** desejadas.
4. Verifique se o botão de envio de arquivo está disponível nessa disciplina e fase.
   - Para projetistas, ele aparece apenas na disciplina sob sua responsabilidade.
   - Para coordenadores e administradores, ele pode aparecer nas disciplinas disponíveis para seu perfil.
5. Clique em **Novo arquivo**.
6. Verifique se o arquivo segue a nomenclatura indicada pela plataforma.
   - Se precisar consultar os códigos da nomenclatura, clique em **Ver os códigos de nomenclatura**.
7. Envie o arquivo de uma destas formas:
   - arrastando o documento para a área de upload;
   - clicando em **Enviar arquivos**;
   - clicando em **Enviar pasta de arquivos** para selecionar uma pasta e enviar todos os arquivos dentro dela.
8. Aguarde a conclusão do envio.
9. Se houver mensagem de erro relacionada à nomenclatura, ajuste o nome do arquivo conforme o padrão indicado e tente novamente.

### Resultado esperado

Ao final, o arquivo será enviado para a disciplina e fase selecionadas dentro da obra.

### Artigos relacionados

- [Como visualizar um arquivo](#como-visualizar-um-arquivo)
- [Como funcionam as regras de validação da nomenclatura](#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Qual é o tamanho máximo por arquivo](#qual-é-o-tamanho-máximo-por-arquivo)

---

## Como visualizar um arquivo

Neste artigo, você aprende como visualizar um arquivo na ObraDoc.

### Passo a passo

1. No painel de Obras, localize a obra desejada.
2. Clique no centro do card da obra para abrir a página da obra.
3. Selecione a **disciplina** e a **fase** em que o arquivo está localizado.
4. Clique sobre o arquivo que deseja visualizar.
   - Arquivos em formato DWG devem ser baixados para a máquina local para possibilitar a visualização.

### Resultado esperado

Ao final, o arquivo será aberto para consulta. No caso de arquivos em PDF, a visualização pode ser carregada automaticamente no navegador.

### Artigos relacionados

- [Como enviar arquivos](#como-enviar-arquivos)
- [Como funciona o versionamento de arquivos](#como-funciona-o-versionamento-de-arquivos)
- [Como definir a equipe de uma obra](./05-gestao-de-obras.md#como-definir-a-equipe-de-uma-obra)

---

## Qual é o tamanho máximo por arquivo

Neste artigo, você entende quais são os limites de envio de arquivos na ObraDoc.

### Regra geral

O tamanho máximo por arquivo e o número de arquivos enviados por vez dependem do plano contratado pela sua empresa. Consulte as informações do seu plano em **Configurações > Faturamento** ou entre em contato com o suporte.

### Como a regra se aplica

Além do limite por arquivo, o armazenamento total da conta também é limitado pelo plano. A plataforma bloqueia o upload quando o espaço restante não for suficiente para o arquivo enviado.

### Impacto para o usuário

Se o upload for bloqueado por limite de armazenamento, você receberá uma mensagem indicando que o limite do plano foi atingido.

### Artigos relacionados

- [Como enviar arquivos](#como-enviar-arquivos)
- [Não consigo enviar arquivos](./10-problemas-comuns.md#não-consigo-enviar-arquivos)
- [Como funciona o armazenamento na ObraDoc](./05-gestao-de-obras.md#como-funciona-o-armazenamento-na-obradoc)

---

## Como funciona o versionamento de arquivos

Neste artigo, você entende como funciona o versionamento de arquivos na ObraDoc.

### Visão geral

O versionamento permite que novas revisões de um mesmo arquivo sejam enviadas sem perder o histórico anterior.

### Como funciona

Quando uma nova revisão é enviada, a versão anterior deixa de ser a versão atual do arquivo.

- Para **administradores e coordenadores**, as versões anteriores continuam disponíveis para consulta na plataforma.
- Para **projetistas e equipe de campo**, o arquivo anterior fica com status **Obsoleto** e não aparece na listagem principal.

### Pontos importantes

- O versionamento mantém o histórico completo do arquivo.
- Cada nova revisão também consome armazenamento.
- A visualização das versões anteriores depende do perfil de acesso do usuário.

### Artigos relacionados

- [Como enviar arquivos](#como-enviar-arquivos)
- [Como funciona o armazenamento na ObraDoc](./05-gestao-de-obras.md#como-funciona-o-armazenamento-na-obradoc)
- [Como aprovar arquivos](./07-fluxos-de-aprovacao.md#como-aprovar-arquivos)

---

## Como funcionam as regras de validação da nomenclatura

Neste artigo, você entende como a ObraDoc valida os nomes dos arquivos enviados para uma obra.

### Visão geral

Ao enviar um arquivo, a ObraDoc valida automaticamente se o nome segue o padrão de nomenclatura configurado para a sua operação. O separador entre os campos é sempre o hífen (`-`). A revisão é obrigatória e fica sempre ao final do nome.

### Como funciona

O nome do arquivo é dividido em campos separados por hífen. A plataforma valida cada campo de acordo com os dados cadastrados na obra.

Os campos disponíveis na nomenclatura são:

| Campo | Exemplo | Qtde de caracteres |
|---|---|---|
| Cód. da Obra | OBR | 3 |
| Cód. da Disciplina | ARQ | 3 |
| Cód. da Fase | EP | 2 |
| Núm. Identificador da Folha | 001 | até 5 |
| Cód. do Conteúdo | PB | 3 |
| Cód. da Localização | PAV | 4 |
| Cód. Personalizado *(opcional)* | CUST | 3 |
| Revisão *(sempre último)* | R01 | 3 |

A revisão segue o formato `R` seguido de dois dígitos — R00, R01, R02 e assim por diante — e é sempre o último campo do nome.

### Exemplo prático

Para uma nomenclatura com os campos Obra, Disciplina, Fase, Folha, Conteúdo, Localização e Revisão, um nome válido seria:

```
OBR-ARQ-EP-001-PB-PAV-R01.pdf
```

### O que acontece quando há erro

Se o nome do arquivo não seguir o padrão, a ObraDoc exibe uma mensagem de erro indicando qual campo está incorreto. Os erros mais comuns são:

- Código da obra não encontrado na plataforma.
- Código de disciplina não vinculado à obra.
- Código de fase não vinculado à obra.
- Código de localização não vinculado à obra.
- Revisão ausente ou fora do formato `R00`.
- Quantidade de campos incorreta.

### Artigos relacionados

- [Como configurar os campos da nomenclatura](./03-configuracoes.md#como-configurar-os-campos-da-nomenclatura)
- [Como enviar arquivos](#como-enviar-arquivos)
- [Boas práticas de nomenclatura](./03-configuracoes.md#boas-práticas-de-nomenclatura)

---

## O que acontece com disciplinas sem nomenclatura

Neste artigo, você entende o que ocorre quando uma disciplina não possui código configurado na ObraDoc.

### Visão geral

Para que um arquivo seja corretamente associado a uma disciplina durante o upload, a disciplina precisa ter um código cadastrado que corresponda ao campo de disciplina no nome do arquivo.

### Como funciona

Quando o sistema valida o nome do arquivo, ele busca o código informado no campo de disciplina dentro das disciplinas vinculadas à obra. Se nenhuma disciplina com aquele código for encontrada, o upload é bloqueado e uma mensagem de erro é exibida.

### Pontos importantes

- Disciplinas sem código configurado não são reconhecidas durante a validação da nomenclatura.
- A mensagem de erro informa qual código de disciplina não foi encontrado na obra.
- Para resolver, certifique-se de que a disciplina está cadastrada na obra com o código correto.

### Artigos relacionados

- [Como funcionam as regras de validação da nomenclatura](#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Como criar uma obra](./05-gestao-de-obras.md#como-criar-uma-obra)
- [Boas práticas de nomenclatura](./03-configuracoes.md#boas-práticas-de-nomenclatura)
