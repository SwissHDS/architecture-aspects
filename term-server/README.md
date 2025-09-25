# Worum geht es

Für Projekte des BAG, im Datenraum Gesundheit und im EPD wird ein Value Set Provider Service für verschiedene Aufgaben
benötigt, insbesondere:

Implementierung von Standardschnittstellen mit Standard Austauschformaten (z.B. FHIR Implementation Guide).
Spezifikation von Standardschnittstellen (z.B. FHIR Implementation Guide).
Validierung von Austauschformaten bei Speicherung und Übermittlung.
Für diese Aufgaben sollen Value Sets über Standardschnittstellen aus einem zentralen Va-lue Set Provider abgerufen
werden können.
Die Value Sets werden von Fachspezialisten bzw. Fachgremien mit Fachspezialisten erstellt. Die Fachspezialisten
benötigen eine Plattform welche die Prozesse zur Pflege der Value Sets unterstützt, insbesondere:

- Erstellung und Bearbeitung von Value Sets.
- Validierung der Codes gegenüber Code Systemen (Terminologien, usw.).
- Freitextsuche in Code Systemen.
- Versionsmanagement.

Zur effizienten Umsetzung der Anforderungen sollen die, in den Value Sets referenzierten Code Systeme 
(Terminologien, usw.) im Terminologie Provider vorgehalten werden. Da-zu sollen Administratoren die Code Systeme 
(Terminologien) aus den verschiedenen Quellen und unterschiedlichen Formaten importieren und verwalten können.

Verschiedene Code Systeme können Codes mit gleicher medizinischer Bedeutung enthalten. Die Abbildung zwischen Codes mit
gleicher medizinischer Bedeutung wird in Kontext Maps gepflegt. Fachexperten sollen die Konzept Maps aus den
verschiedenen Quellen mit unterschiedlichen Formaten importieren und verwalten können.

Über die o.g. Kernfunktionen hinaus können einzelne Funktionen auch im klinischen Kon-text genutzt werden, dabei
insbesondere die Funktion zur Freitextsuche in Value Sets und Terminologien sowie die Nutzung der Konzept Maps um Codes
aus verschiedenen Code Systemen mit gleicher medizinischer Bedeutung identifizieren zu können.

Die Einführung eines Terminologie-Servers für die o.g. Benutzerfälle ist eine notwendige Bedingung für die Etablierung
von Standards im Gesundheitswesen in der Schweiz.

Das SwissHDS Architekturteam hat dazu ein Konzept sowie die wichtigsten Anforderungen zusammengestellt. Die
Dokumente dazu finden Sie im Ordner [Terminologie Server](https://github.com/SwissHDS/architecture-aspects/tree/main/term-server) auf dieser Plattform.

Gerne erwarten wir Ihr Feedback und Ihre Anregungen.
