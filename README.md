# NFePHP-CodeIgniter
Classe e Procedimento para usar a biblioteca NFePHP no Framework CodeIgniter
## Instalação com Composer
No arquivo composer.json do seu CodeIgniter adicione as seguintes linha:
```
"config":
        {
            "vendor-dir": "application/libraries"
        }
```

Depois abra um terminal no diretório deste arquivo e execute o comando abaixo:
```
composer require nfephp-org/nfephp:dev-develop
```
Salve a classe NFePHP.php dentro application/libraries

## Uso
```
 $this->load->library('nFePHP');
```
Ou
```
 $config = array();
 
 $this->load->library('nFePHP', $config);
```

## Referências
[1]:https://groups.google.com/forum/#!topic/nfephp/7LJWZp2-TWE
[2]:http://andredourado.com.br/gerar-pdf-de-um-danfe-a-partir-do-xml-em-php/
[3]:https://groups.google.com/forum/#!topic/nfephp/cSYYcuOQoYo
[4]:https://github.com/nfephp-org/nfephp/blob/master/exemplos/NFe/4.00testaDanfe.php
[5]:https://github.com/nfephp-org/nfephp/blob/master/exemplos/NFe/4.00testaDanfce.php
