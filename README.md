# Note-by-schorschii---word-wrap
Modification of Cinnamon desklet Note by schorschii. Added word-wrap + parameter for better word-wrap fit (word-wrap font scale factor)
Replace desklet.js and settings-schema.json in ~/.local/share/cinnamon/desklets/notes@schorschii and restart Cinnamon or log-out + log-in.

Note: technically the text of a note is just a label on background image so no automatic word-wrapping is possible. Probably no scroll as well. 
The word-wrapping functionaly implemented just estimates the number of characters for each line and breaks lines at this length. For better results
you can modify the parameter "word-wrap font scale factor".
