<h1 align="center">
  <br>
    <img src="https://i.imgur.com/d8QEHRb.png" alt="Tradução Magento 2 pt_BR" width="128" height="128" title="Tradução Magento 2 pt_BR"/> 
  <br>
  Tradução para Magento 2 em Português do Brasil (pt_BR)
  <br>
</h1>

<p align="center">  
  <a href="https://packagist.org/packages/rafaelstz/traducao_magento2_pt_br"><img src="https://img.shields.io/packagist/dt/rafaelstz/traducao_magento2_pt_br.svg" alt="Total Downloads"></a>
</p>

Inclui a tradução mais atualizada para todas as versões do Magento 2.
Esse pacote de linguagem foi gerado com base na [Tradução Oficial do Magento 2](https://crowdin.com/project/magento-2/pt-BR), transformado em repositório GIT para facilitar a intalação e atualizações.

# Compatível

- Magento 2 Open Source
- Magento 2 Commerce
- Magento 2 B2B

# Instalação

## Via Composer 

Para instalar essa tradução via [Composer](https://getcomposer.org) você precisa usar o terminal do seu servidor.

```
composer require rafaelstz/traducao_magento2_pt_br:dev-master
php bin/magento setup:static-content:deploy pt_BR -f
php bin/magento cache:clean
```

## ou manualmente

Para instalar a tradução manualmente você irá precisar acessar seu servidor.

* Crie o diretório **app/i18n/rafaelcg/language_pt_br**
* Efetue o [download do zip](https://github.com/rafaelstz/traducao_magento2_pt_br/archive/master.zip)
* Mova o conteúdo do repositório para a pasta e habilite a tradução

# Como Usar

Para começar a usar a tradução instalada na loja e no painel administrativo da loja siga esses passos:

## Loja em Português
Acesse no painel administrativo da sua loja `Stores -> Configuration -> General -> General -> Locale options` e selecione em **Locale** a opção **Brazilian Portuguese (Brazil)**.

## Painel admin em Português
Acesse no painel administrativo da sua loja clique no icone do seu usuário no canto superior direito e então clique em `Account Setting` e selecione em **Interface Locale** a opção **Brazilian Portuguese (Brazil)**.

# Ajude

Ajude a melhorar a tradução oficial do Magento 2 para Português Brasil usando [esse link da página Crowdin](https://crowdin.com/project/magento-2/pt-BR).

# Autores
Essa tradução foi criada oficialmente para o Magento 2 no [Crowdin](https://crowdin.com/project/magento-2).
Esse repositório do Github foi criado para facilitar a instalação e atualização via Composer.

[Rafael Corrêa Gomes](https://github.com/rafaelstz)
