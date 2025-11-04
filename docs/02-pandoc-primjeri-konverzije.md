# Pandoc
Pandoc je alat koji omogućuje pretvaranje Markdown datoteka u druge formate kao što su HTML, PDF, DOCX i mnogi drugi.

### Konverzija iz .md u .html format
pandoc dokument.md -o dokument.html

Ova naredba pretvara Markdown datoteku u HTML web stranicu koja se može otvoriti u pregledniku.

### Konverzija iz .md u .pdf format
pandoc dokument.md -o dokument.pdf --pdf-engine=xelatex

Ova naredba generira PDF dokument uz podršku za hrvatska slova pomoću XeLaTeX enginea.

### Konverzija iz .md u .docx format
pandoc dokument.md -o dokument.docx

Ova naredba pretvara Markdown u Word dokument, idealno za dijeljenje ili daljnje uređivanje.
