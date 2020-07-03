In diesem Ordner können **Bilder** für dieses Projekt abgelegt werden.
  
### Einbinden in die Webseite mit:

     
	 <img src="<PfadZuImagesOrdner>/images/{Dateiname inklusive Endung}"/>
	 
	 

### Erklärung zu \<PfadZuImagesOrdner>:

* deine Markdown-Datei, in die das Bild eingefügt werden soll, befindet sich in einem Unterordner, z.B. Backwaren/leckerBrot.md
* da der Ordner images/ im Verzeichnis auf derselben "Ebene" liegt (beide Ordner liegen im Verzeichnis lets_git_kochbuch/), musst du mit "../" eine Ebene höher navigieren und kannst **dann** den Ordner images/ ansteuern

Beispiel dazu:

	 <img src="../images/leckerBrot.jpg"/>

* befindet sich deine Markdown-Datei in 2 Unterordnern, z.B. Desserts/Kuchen/leckerKuchen.md, dann musst du mit "../../" 2 Ebenen höher navigieren und kannst dann auf images/ zugreifen

Beispiel dazu:

	 <img src="../../images/leckerKuchen.jpg"/>