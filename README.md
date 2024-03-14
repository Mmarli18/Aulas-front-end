# Anotações sobre front-end

Atividades de estudo de HTML e CSS

## HTML
- Estruturação
- Semântica
- Padrões Web

## CSS
Linguagem de estilização que "casa" com elementos HTML.

```css
Seletor {propriedade: valor;}

Seletor {
    propriedade1: valor;
    propriedade2: valor;
    propriedade3: valor;
}
```


Em geral CSS serve para:

1. Estilos de vários tipos (cores, sombras. borda etc...)
2. Alinhamentos e espaçamentos
3. Design Responsivo
4. Anotações e efeitos especiais de interação

### Formas de implementação

#### Inline
O CSS é aplicado diretamente em cada tag HTML.

#### Interna/Onpage
O CSS é criado usando mais regras (com seletores, propriedades, valores) dentro da própria página que queremos formatar.

As regras vão valer para todos os elementos/tags desta página.

#### Externa (mais usada)
É criado um arquivo de extensão CSS dedicado às regras de formatação. Esse arquivo é então "conectado" as páginas HTML.

---

### Tipos de seletor
- Tag: Seletor mais abrangente/generalista, casa com elementos HTML de acordo com a tag especificada.

- Descendente: Seletor mais especifico, casa com elementos que são filhos (descendentes) de outro elemento. Usa-se espaço para separar o filho/pai.

- Agrupado: Grupo de seletores que compartilham uma mesma formatação. Usa-se vírgula para separar os seletores;

- Pseudo-Classe: Classes pré prontas/nativas da linguagem pode ser aplicadas em diversas situações. Ex. passar o mouse, reconhecer foco, selecionar determinados elementos etc, Começam com dois pontos (:)

- Classe: Seletor versátil, permite a aplicação de estilos de diversos elementos, possibilitando também a combinação de diferentes classes. No CSS usa-se ponto (.nome-da-classe) para criar. No HTML usa se o atributo class="nome-da-classe" para aplicar a classe.

- Identificado: Seletor bastante restrito (o mesmo ID só pode ser usado apenas uma vez por pagina) permite criar uma estelização específica. No CSS usa-se #nome-do-id para criar, e no HTML usa-se o atributo id="nome-do-id" para aplicar.

