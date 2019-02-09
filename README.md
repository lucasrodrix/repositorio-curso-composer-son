#Meu Pacote

Exemplo de um Curso

##Exemplo de Utilização

---

use LucasRodrix\CursoSON\Hello;

// create a log channel
$log = new Monolog\Logger('name');
$log->pushHandler(new Monolog\Handler\StreamHandler('app.log', Monolog\Logger::WARNING));

// add records to the log
$log->warning((new Hello)->say('Renata'));

---
