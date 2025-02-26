---
layout: default
---

  Este projeto foi criado para documentar experiências hands-on. Com base nos conhecimentos adquiridos durante os estudos para as certificações CompTIA A+ e CompTIA Security+, desenvolvi um Home Lab para este projeto, que será detalhado ao longo desta página. Outros projetos estão em planejamento e serão adicionados futuramente.

Podes também me acompanhar no [LinkedIn!](https://www.linkedin.com/in/julio-nunes-b97331205/).

# Infraestrutura

O projeto consiste em ter um infraestrutura simples, que simula um ambiente AD em uma organização, onde hosts se conectam em um servidor centralizado e partir disto, conectam-se a internet.
A ideia era fazer com os CLIENTs automaticamente recebessem configurações de rede através do DHCP, e fazer com que o AD agisse como um servidor DNS também.

A segurança não é uma prioridade para este projeto, pois se trata de um Home Lab, e nenhuma das informações utilizadas são reais.
(O ideal seria não deixar o AD exposto à internet, mas sim, dedicar um firewall e outras ferramentas de segurança)

![Branching](Infraestrutura.png)

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)



### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
