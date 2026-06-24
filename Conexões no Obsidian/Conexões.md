
# __Conexões Diretas__

1. Link Direto

É o comando principal. Ao colocar isso na Nota A apontando para a Nota B, o gráfico criará imediatamente uma linha conectando as duas.

```
[[Nome da Nota]]
```

2. Link para Seção

Conecta à nota específica. No gráfico, a conexão vai para a nota principal, mas ajuda a estruturar seu pensamento.

```
[[Nome da Nota#Título]]
```

3. Link para Bloco

Conecta a um parágrafo específico. No gráfico, também conta como uma conexão com a nota-mãe.

```
[[Nome da Nota^bloco]]
```


# __Notas Órfãs e Notas Inexistentes__

1. Links Fantasmas

Se você criar um link para uma nota que ainda não foi escrita, o Obsidian criará um nó no gráfico para ela, mas ele aparecerá **cinza claro ou translúcido**. Isso é ótimo para ver o que você ainda precisa estudar ou escrever.

```
[[Nota Que Não Existe Ainda]]
```

2. Notas Orfãs

Notas que não têm nenhum `[[link]]` dentro delas e nenhuma outra nota aponta para elas. Elas ficam flutuando sozinhas no gráfico.

```
[[link]]
```

# __Manipulação de Tags__

Se você digitar `#estudos` ou `#matematica` dentro de várias notas, você pode ir nas configurações do Graph View (o ícone de engrenagem no gráfico) $\rightarrow$ **Groups (Grupos)** $\rightarrow$ **New Group** e digitar `tag:#matematica`.

#manipulaçãodetags

