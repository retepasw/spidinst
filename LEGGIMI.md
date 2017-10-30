SPIDINST
--------
Author: P. Bozzo
Version: 0.1 alpha
Date: 2017/10/30
License: GPL 2.1

Installatore del pacchetto simplespidphp-pasw, per avere una libreria derivata da
SimpleSAMLPhp che supporti il protocollo SPID per i service provider basati su PHP
(per esempio che utilizzino CMS come Drupal e Joomla).

Come si procede
---------------
1) si scarica il presente pacchetto e si decomprime
2) si carica via FTP il file install.php in una cartella della root del sito dedicato
   al service provider. Si consiglia di creare una cartella di nome "spidinst" e caricare
   lì il file. Il sito deve essere sicuro (HTTPS).
3) ammettendo che il dominio del sito sia www.miodominio.it , si lancia così lo script:
   https://www.miodominio.it/spidinst/install.php
4) si procede seguendo con cura le indicazioni a video
5) completata la procedura si cancella via FTP il file install.php e si accede alla
   interfaccia della libreria
   https://www.miodominio.it/spid
6) verificato il buon funzionamento del pacchetto installato, seguire le indicazioni
   presenti nel tutorial per procedure tecniche e amministrative da espletare sul sito
   www.spid.gov.it .
   
   
Dettagli tecnici
----------------
- Lo script è alla versione alpha, quindi ci possono essere delle difficoltà con alcuni
  provider di siti web, non se ne garantisce il funzionamento nel 100% dei casi.
- Per ora lo script funziona correttamente solo su siti che utilizzano sistemi UNIX/LINUX
- L'installazione per ora prevede una unica fonte di autenticazione, generata automaticamente
  e denominata "default-sp"
- La versione di PHP da utilizzare deve essere da 5.4 a 5.6.x

