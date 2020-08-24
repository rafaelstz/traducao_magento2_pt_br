# Como contribuir para a tradução do Magento 2

Nesse tutorial eu vou te mostrar como contribuir e ajudar na tradução do Magento 2.

## Passo 1: Download

Primeiro passo é fazer uma cópia do repositório, para isso você pode clicar no botão **Fork** no topo superior direto.

![fork](https://help.github.com/assets/images/help/repository/fork_button.jpg)

## Passo 2: Atualize o arquivo github_contributions.csv

Esse é o workflow que trabalhamos para gerar essa tradução:

- Obtemos automaticamente as traduções feitas via [Crowdin](https://crowdin.com/project/magento-2).

- No arquivo [github_contributions.csv](https://github.com/rafaelstz/traducao_magento2_pt_br/blob/master/github_contributions.csv) estão as contribuições da nossa comunidade.

- Mergiamos o arquivo `github_contributions.csv` com o arquivo [pt_BR.csv](https://github.com/rafaelstz/traducao_magento2_pt_br/blob/master/pt_BR.csv). Sua loja Magento 2 vai utilizar esse arquivo.

Então você pode contribuir utilizando o arquivo [github_contributions.csv](https://github.com/rafaelstz/traducao_magento2_pt_br/blob/master/github_contributions.csv).

### Como editar o arquivo github_contributions.csv

O arquivo `github_contributions.csv` é separado **linha por linha**, veja:

```
"Create Order","Criar pedido",module,Magento_AdvancedCheckout
```

- "Create Order": Texto original
- "Crear pedido": Tradução
- module: Fala que a tradução é feita em um módulo específico
- Magento_AdvancedCheckout: Aplica a tradução apenas nesse módulo, você utiliza o nome do módulo que você utilizará

## Passo 3: Contribuindo

- Hora de contribuir, **crie seu commit** no seu fork.
- Depois crie seu **pull request**, vamos analisar e aprovar.

Obrigado por contribuir! 😉
