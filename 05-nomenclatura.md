# 5. Nomenclatura

← [Índice](./index.md)

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

- [Como configurar os campos da nomenclatura](#como-configurar-os-campos-da-nomenclatura)
- [Como enviar arquivos](./04-arquivos.md#como-enviar-arquivos)
- [Boas práticas de nomenclatura](#boas-práticas-de-nomenclatura)

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

- [Como funcionam as regras de validação da nomenclatura](#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Boas práticas de nomenclatura](#boas-práticas-de-nomenclatura)
- [Como enviar arquivos](./04-arquivos.md#como-enviar-arquivos)

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
- [Como criar uma obra](./03-gestao-de-obras.md#como-criar-uma-obra)
- [Boas práticas de nomenclatura](#boas-práticas-de-nomenclatura)

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

- [Como funcionam as regras de validação da nomenclatura](#como-funcionam-as-regras-de-validação-da-nomenclatura)
- [Como configurar os campos da nomenclatura](#como-configurar-os-campos-da-nomenclatura)
- [Como enviar arquivos](./04-arquivos.md#como-enviar-arquivos)
