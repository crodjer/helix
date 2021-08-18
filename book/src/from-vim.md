# Migrating from Vim

Helix's editing model is strongly inspired from vim and kakoune, and a notable
difference from vim (and the most striking similarity to kakoune) is that Helix
follows the `selection → action` model. This means that the whatever you are
going to act on (a word, a paragraph, a line, etc) is selected first and the
action itself (delete, change, yank, etc) comes second. A cursor is simply a
single width selection.

> TODO: Mention texobjects, surround, registers