![>>> Abra esse README.md no modo de 'Preview' para melhor visualização <<<](assets/20220719_104823_CodeIgualUmKenzie.png)

# Instruções

Esse teste tem como objetivo **fixar seus conhecimentos sobre o assunto abordado nessa última semana**.

Esse projeto possui todos os arquivos necessários para desenvolver a solução esperada, então **NÃO SERÁ NECESSÁRIO CRIAR OUTROS ARQUIVOS**.

### ⏱️ Duração do teste

> `15 minutos para todo o desenvolvimento`

### ✅ Console.log

> `Será permitido usar o console.log() para testar o seu código`

# Problema

Você terá um **array de objetos** chamado `timeDeInstrutores` **já predefinido** no arquivo `script.js`.

Dentro dele terão objetos contendo as seguintes chaves:

- `nome` - Tipo **String** | Nome do instrutor
- `modulo` - Tipo **Number** | Módulo do instrutor
- `numeroAlunos` - Tipo **Number** | Número de alunos daquele módulo
- `imagem` - Tipo **String** | URL com a imagem do instrutor

Além disso, você também terá uma **lista não ordenada** (ul) com a classe `container` **já predefinida no body** do arquivo `index.html` além de um **list item** (li) que contém um parágrafo (p) com a classe `card--instrutor missing`

### 🎲 Desafio

Dadas essas informações, será necessário desenvolver uma função chamada `renderizarInstrutoresEspecificos` que fará o seguinte ao ser chamada:

1. **Selecionar e remover** o li predefinido na ul do `index.html`
2. **Iterar** (percorrer) o array `timeDeInstrutores` e **fazer a seguinte validação** para cada item:
   - Caso o nome do instrutor seja `Victor` ou o número de alunos seja maior que `450`, a função deverá:
     1. **Criar** um list item (li), um image (img) e um paragraph (p)
     2. **Adicionar a classe** `card--instrutor` ao li criado
     3. **Inserir o texto** no parágrafo criado: `👋 Olá, eu me chamo [NOME DO INSTRUTOR] e serei seu instrutor no módulo [NÚMERO DO MÓDULO]`
     4. **Associar** corretamente o caminho da imagem ao source (src) da image criada
     4. **Adicionar** o paragraph e image criados anteriormente como filhos do list item
     5. **Adicionar** o li construído via DOM à ul predefinida do arquivo HTML
3. Por fim, **execute** a sua função

#### 🚨 Atenção

As **estilizações já estão todas feitas** no arquivo `styles.css`, ou seja, não precisa se preocupar com isso nesse teste, mas fique a vontade para olhar se quiser.

Além disso, **as modificações mencionadas acima deverão ser feitas via DOM**, ou seja, o `index.html` não pode ser modificado diretamente.

---

> **Bom desenvolvimento**, e qualquer dúvida só perguntar ao seu aplicador 😉!

---