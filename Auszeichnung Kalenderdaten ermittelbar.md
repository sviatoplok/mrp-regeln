1) Wenn im Text eine Zeitangabe wie etwa "vorgestern" auftaucht, bei der das Kalenderdatum ermittelt werden kann, wird händisch das Datum im ISO-Format in doppelten geschweiften Klammern eingefügt, um es später strukturiert verwenden zu können:
> Der Minister für Kultus und Unterricht stellt fest, dass er dem Ministerpräsidenten schon am Donnerstag`{{1918-10-24}}` seine Demission angemeldet habe.
    
2) Wenn möglich, sollte eine Beschreibung des Ereignisse mit @ beigefügt werden::
>[I.] Der Ministerpräsident gibt einen kurzen Überblick über die gegenwärtige politische Lage, wie sie sich aufgrund des Ah. erlassenen Manifestes vom 16. Oktober und der Antwortnote`{{1918-10-14@Wilsons Erwiderung auf deutsche Mitteilung}}` des Präsidenten Wilson darstellt .
    
3) Wenn nicht das genaue Datum bekannt ist, wird das früheste Datum verwendet, zu dem es eine Erwähnung des Sachverhaltes gibt, in diesem Fall vor das Datum `notAfter` setzen:
>` {{notAfter 1918-06-18@Reduktion der Brotquote}}`

4) in Situationen, in denen eine Erstnennung aber kein konkretes Enddatum bekannt ist, wird `notBefore` eingefügt.
