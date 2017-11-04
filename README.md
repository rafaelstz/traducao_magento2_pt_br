# Tradução para Magento 2 em Português do Brasil (pt_BR)

Esse pacote de linguagem foi gerado com base na [Tradução Oficial do Magento 2](https://crowdin.com/project/magento-2/pt-BR), transformado em repositório GIT para facilitar a intalação e atualizações.

# Instalação

> **Antes de instalar é necessário verificar sua versão do Magento 2 para instalar a tradução correta usando as branches desse repositório.**

## Via Composer

Para instalar essa tradução via [Composer](https://getcomposer.org) você precisa usar o terminal do seu servidor.

```
composer require rafaelstz/traducao_magento2_pt_br:dev-master
php bin/magento cache:clean
```

## Manualmente

Para instalar a tradução manualmente você irá precisar acessar seu servidor.

* Faça o dowload  [desse arquivo](https://github.com/rafaelstz/traducao_magento2_pt_br/archive/master.zip).
* Crie essas pastas e cole o conteúdo baixado nessa pasta `app/i18n/rafaelcg/language_pt_br`.
* Deve estar dessa maneira `app/i18n/magento2translations/pt_BR/pt_BR.csv`.
* Em seu painel Admin do Magento limpe o cache.

# Como Usar

Para começar a usar a tradução instalada vá em `Stores -> Configuration -> General > General -> Locale options` e selecione em **Locale** a opção **Brazilian Portuguese (Brazil)**.

# Ajude

Ajude a melhorar a tradução oficial do Magento 2 para Português Brasil usando [esse link da página Crowdin](https://crowdin.com/project/magento-2/pt-BR).

# Autores
Essa tradução foi criada oficialmente para o Magento 2 usando o [Crowdin](https://crowdin.com/project/magento-2).
Esse repositório do Github foi criado por mim para facilitar a instalação.

[Rafael Corrêa Gomes](https://github.com/rafaelstz)
