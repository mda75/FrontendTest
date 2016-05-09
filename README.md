#Less is more.
Less is more è il principio che ha guidato lo sviluppo di questa demo. Ho scelto questo approccio perchè meglio può esprimere le capacità tecniche di chi lo pratica.

- incredibile pulizia ed essenzialità del codice,
- scrivere solo ciò che serve,
- no javascript perchè non necessario (lo sarebbe solo per caricare il video, ma ho inteso che non fosse oggetto di questo test)

Tecncologie essenziali e poco codice significano minore e più veloce manutenzione.

Questo è possibile grazie allo sviluppo dal foglio bianco, praticabile solo con ottime conoscenze tecniche. Agli antipodi c'è lo sviluppo basato su un frontend framework come bootstrap, che farcisce di classi i tag html rendendo difficoltoso ottenere il risultato desiderato e contravvenendo al principio cardine della separazione tra markup e layout.

Motivo alcune delle scelte più significative:
- ho optato per un design elastico senza compromessi, le media query sono utilizzate puntualmente solo dove necessario e non in maniera indiscriminata e preventiva;
- il menu è subito visibile anche in versione mobile evitando di utilizzare l'abusata icona per richamarlo;
- in mobile il layout cambia tra landscape e portrait utilizzando la proprietà orientation a mio avviso spesso sottovalutata;
- gli stati hover sono gradevoli, ma non urlati;
- i logo delle testate giornalistiche sono visualizzati in scala di grigi, a colori, ed in total white pur utilizzando un'unica source grazie all'uso dei filtri css.

La messa in produzione della pagina necessiterebbe di compressione del codice che non è stata eseguita per favorirne la leggibilità.

La pagina supera con zero errori i test di validazione di html e css del w3c.
