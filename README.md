# Wort Meister

Ist eine deutsche Version von [Word Master](https://github.com/octokatherine/word-master). Das ist wiederum ein Klon von [Wordle](https://www.powerlanguage.co.uk/wordle/).

🔗 https://octokatherine.github.io/word-master/

## Regeln

Du hast 6 Versuche um das korrekte Wort zu erraten.
Jeder Versuch kann irgendein gültiges Wort sein.

Nachdem ein Versuch abgeschickt wurde, färben sich die Buchstaben grau, grün oder gelb.

- Grün: Der Buchstabe ist korrekt, in der korrekten Position.
- Gelb: Der Buchstabe ist korrekt, aber in der falschen Position.
- Grau: Der Buchstabe ist nicht korrekt.

## Bauen

Um diese Website von einer Ubuntu Live CD zu bauen sind folgende Schritte nötig:

sudo apt-get install node.js npm
npm cache clean -f
sudo npm install -g n
sudo n stable
npm install
npm run predeploy
