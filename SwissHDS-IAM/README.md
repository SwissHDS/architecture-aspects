# Worum geht es

Bei der Kommunikation von Personendaten im Datenraum Gesundheit muss die Einwilligung der betroffenen Personen
berücksichtigt werden und die daraus abgeleiteten Zugriffsrechte müssen von den technischen Schnittstellen der
Datenbereitsteller durchgesetzt werden.

Das Identity und Access Management (IAM) zur Authentisierung der Benutzer und zur Autorisierung der Zugriffe durch die
Benutzer auf die Personendaten ist daher ein integraler Bestandteil des Datenraums und soll als zentraler Dienst
bereitgestellt werden.

Das SwissHDS Architekturteam hat dazu ein Konzept sowie die wichtigsten Anforderungen zusammengestellt.
Das Konzept schlägt dazu grundsätzliche Verfahren und Standards für die Umsetzung der Authentisierung von Benutzern und
die Autorisierung von Zugriffen durch die Benutzer vor. Das Konzept zeigt dabei insbesondere auf, wie die Autorisierung
der Zugriffe auf der Basis der Einwilligung von Patientinnen zusammenhängt und leitet daraus die Anforderungen an die
Authentisierung und Autorisierung (Consent Enforcement) ab.

Aktuell sind die gesetzlichen Rahmenbedingungen für die Einwilligung der betroffenen Personen nicht final. Das Konzept
beschreibt daher eine generische Lösung auf der Basis des XACML Frameworks, die genügend Möglichkeiten bietet, um die
zukünftigen Anforderungen abzudecken.

Die Dokumente dazu finden Sie im
Ordner [SwissHDS IAM](https://github.com/SwissHDS/architecture-aspects/tree/main/SwissHDS-IAM) auf dieser Plattform.

Gerne erwarten wir Ihr Feedback und Ihre Anregungen.
