# PROJETO

## Configurar o PHP.INI para o composer
 > Descomentar o extension=opensslcls

## Criar o arquivo de configuração do composer
```bash
    composer init
```
## No arquivo principal
```php
    <?php
    require 'vendor/autoload.php';
```

## Na classe, colocar o Namespace
```php
    <?php
    namespace Jardel\Projeto;
```
## Para usar no projeto, basta chamar a classe com o namespace
```php
$c = new \Jardel\Projeto\Calc();
```