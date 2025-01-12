Questa GitHub Action ottimizza automaticamente ad ogni commit le immagini PNG e SVG presenti in una repo usando [cwebp](https://developers.google.com/speed/webp/docs/cwebp?hl=it) e [svgo](https://github.com/svg/svgo).

È stata creata per Zappr, nello specifico per ottimizzare i loghi nella repo [ZapprTV/channels](https://github.com/ZapprTV/channels). Di default, prende tutte le immagini nel root di una repo come input per poi restituire le versioni ottimizzate nella cartella `optimized/`, ma se vuoi usare una cartella diversa puoi specificarla nell'input `directory`.
