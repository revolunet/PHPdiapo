PHPdiapo : un script PHP pour générer des diaporamas



PHPdiapo est un petit script PHP (PHP4) qui permet de faire de simples diaporamas d'images dans une page web PHP. Il scanne automatiquement un repertoire fourni et genere dans votre page le javascript necessaire à l'execution du diaporama. 

exemple :
    
    include_once("PHPdiapo.php");
    // *** Placez cette partie ou le diaporama doit apparaitre 
    // repertoire de vos images (relatif a la page en cours) 
    $path="images/diapo1";
    // id du diapo (sera utilisé pour le dom) sans caracteres speciaux 
    $iddiapo="exemple_1";
    $d=new PHPdiapo($path,$iddiapo);
    

  