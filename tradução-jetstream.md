## 1 - Instalar o pacote de tradução:
composer require lucascudo/laravel-pt-br-localization --dev

## 2- Publicar as traduções:
php artisan vendor:publish --tag=laravel-pt-br-localization

## 3 - Configurar o idioma padrão:
No arquivo config/app.php, altere a linha que define o idioma padrão para 'locale' => 'pt_BR'.
Verificar e ajustar traduções específicas do Jetstream:

## 4 - Certifique-se de que os arquivos de tradução específicos do Jetstream estejam na pasta resources/lang/pt_BR. 
Você pode precisar criar ou ajustar traduções específicas para os componentes do Jetstream.
