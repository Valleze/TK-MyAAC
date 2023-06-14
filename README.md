# ttk-my-aac
Um Criador Automático de Contas (AAC) gratuito e de código aberto escrito em PHP

Este site foi desenvolvido por [Slawkens - OTSOFT](https://github.com/otsoft/myaac) e editado pela comunidade.
Esta fork é baseada neste [commit](https://github.com/otsoft/myaac/commit/f24fc75b12bb6a44a5f99c7b98da03223ad9f8bf).

## Novidades
- 


### Requisitos
- PHP 7.4 ou superior
- Banco de dados MySQL
- Composer
- Extensão PDO PHP
- Extensão XML PHP
- Extensão ZIP PHP
- (opcional) mod_rewrite para usar URLs amigáveis

### Instalação
## Ubuntu
### Na pasta raiz do ttk-my-aac rode ./install-ttk-my-aac.sh siga os passos.

Basta descompactar e desempacotar o código-fonte (o que você já deveria ter feito até agora, se estiver lendo isso) no diretório raiz do seu servidor web.

O MyAAC precisa de permissões adequadas para manipular os arquivos corretamente.
Se você estiver usando o Apache2, então o diretório precisa ter o proprietário definido como: www-data. Você pode fazer isso usando o seguinte comando:
```
chown -R www-data.www-data /var/www/*

```

perl

(ou qualquer outro caminho onde sua instalação do MyAAC esteja localizada)

Observação: Somente Linux
Se você estiver no Linux, use esses comandos para definir as permissões corretas:
```

chmod 660 config.local.php
chmod 660 images/guilds
chmod 660 images/houses
chmod 660 images/gallery
chmod -R 770 system/cache


```


Visite http://your_domain/install (http://127.0.0.1/install) e siga as instruções no navegador.

### CRÉDITOS:
Slawkens, Equipe TibiaKing
