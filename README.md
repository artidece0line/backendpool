# Introdução

### Side note

Deixei este detalhe registrado porque me custou tempo para descobrir.


![types of modules](images/tipos-de-modulos.png)

Os módulos padronizados são mais recentes.

![differences between types of modules](images/diferencas-entre-modulos.png)

A aula comentou que veremos mais exemplos do formato padronizado adiante, mas o formato antigo continua importante de aprender, e a diferença de desempenho a favor do padronizado é pequena.

OBS: os testes ficam na pasta de testes do projeto.


# Executando o script principal do manifesto

Expliquei essa questão numa gravação em vídeo.


# Exportando duas funções

Os arquivos ficam na pasta de testes correspondente.


# Exportando constantes

Uma constante é exportada do mesmo jeito que uma função; só muda o que vai do outro lado do sinal de atribuição.


# Formas de exportar

Dá para exportar um único item:

```
const item = "Bola"
module.exports = item
```

Ou vários:

```
const name = "Enzo"
const age = 5
module.exports = {
    name: name,
    age: age
}
```

Quando a chave tem o mesmo nome da variável, a chave pode ser omitida:

```
const name = "Enzo"
const age = 5
module.exports = {
    name,
    age:
}
```


# Funções internas

Uma função interna é aquela que não é exportada. Ela serve para uso dentro do próprio módulo, por exemplo dentro de uma função exportada.


# Exportação padrão

Uma das formas aparece na imagem abaixo.