Author: Hadis Fayz, BSc

# 1. Reinforcement Learning
Reinforcement Learning ist ein Lernverfahren, bei dem ein Agent durch Belohnungen und Bestrafungen lernt, optimale Entscheidungen zu treffen.

Ein Reward ist die Belohnung, die ein Agent für eine Aktion erhält.

Die Learning Rate bestimmt, wie stark neue Erfahrungen das bestehende Wissen beeinflussen.

Eine Policy beschreibt die Strategie des Agenten und legt fest, welche Aktion in welchem Zustand gewählt wird.

Exploration bedeutet das Ausprobieren neuer Aktionen, während Exploitation bekannte erfolgreiche Aktionen nutzt.

Zu den Herausforderungen zählen große Zustandsräume, hoher Rechenaufwand und Sparse Rewards.

# 2. Historische Aufgabe: Flugzeuge im Zweiten Weltkrieg
Die Flugzeuge sollten nicht an den Stellen mit den meisten Einschlägen gepanzert werden. Stattdessen sollten die Bereiche mit wenigen Einschlägen verstärkt werden, da Treffer dort häufiger zum Absturz führten.

Der Grund ist, dass nur zurückgekehrte Flugzeuge untersucht wurden. Dieses Phänomen wird als Survivorship Bias bezeichnet.

# 3. Korrelation und Kausalität
Korrelation bedeutet, dass zwei Variablen gemeinsam auftreten oder sich gemeinsam verändern.

Kausalität bedeutet, dass eine Variable die Ursache einer anderen Variable ist.

Der Zusammenhang zwischen Eisverkäufen und Badetoten ist eine Korrelation, aber keine Kausalität. Die eigentliche Ursache für beide Entwicklungen ist das warme Wetter.

Für Data Science ist dieser Unterschied wichtig, da Modelle häufig Korrelationen erkennen, ohne tatsächliche Ursache-Wirkungs-Beziehungen nachweisen zu können.

# 4. Train-Test-Split:
Siehe Abgabe im Repository unter train test split.ipynb

# 5. Kognitive Verzerrungen

Kognitive Verzerrungen bzw. mit dem entsprechenden Fachbegriff Confirmation Bias beschreibt die Tendenz, Informationen bevorzugt wahrzunehmen, die bestehende Überzeugungen bestätigen.

Dadurch können Daten falsch interpretiert und Entscheidungen verzerrt werden.

Ein Beispiel ist die selektive Betrachtung von Ergebnissen, die eine bereits bestehende Annahme unterstützen.

Wir haben das an der FH CAMPUS02 in der Vorlesung "Grundlagen Maschinelles Lernen und Künstliche Intelligenz" aber auch in "Statistik und Data Mining" (5 ECTS) betrachtet im Rahmen größerer Data Science / Data Mining / ML Projekte.

# One-Hot-Encoding und Dummy-Encoding
One-Hot-Encoding erstellt für jede Kategorie eine eigene Spalte.

Dummy-Encoding verwendet eine Referenzkategorie und benötigt daher nur k−1 Spalten.

Dummy-Encoding reduziert die Anzahl der Variablen und hilft, Multikollinearität zu vermeiden.

Der wesentliche Unterschied besteht darin, dass One-Hot-Encoding alle Kategorien abbildet, während Dummy-Encoding eine Kategorie als Referenz weglässt.
