Dépendances sur htmldoc, téléchargeable ici :
http://www.htmldoc.org/software.php?VERSION=1.9.x-r1629&FILE=htmldoc/1.8.27/htmldoc-1.8.27-source.tar.gz

ensuite configure, make, sudo make install classiques.

Changer ligne 156 dans eggs/aws.pdfbook-XXX-py2.6.egg/aws/pdfbook/conversions.py

  >> if item.meta_type in ('Portal Image', 'Image', 'ATBlob'):
