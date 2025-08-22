# progetto-ai
pregetto per il corso di "introduzione all'apprendimento automatico" presso UNIBO

## Requisiti

Questo progetto ha l'obiettivo di separare un'immagine, ottenuta come somma di due immagini, nelle sue componenti originali.

Le due immagini di origine, img1 e img2, provengono da dataset diversi: MNIST e Fashion-MNIST, rispettivamente.

Non è consentita alcuna pre-elaborazione. La rete neurale riceve in input l'immagine combinata (img1 + img2) e restituisce le predizioni (hat_img1 e hat_img2).

Le prestazioni vengono valutate utilizzando l'errore quadratico medio (MSE) tra le immagini predette e quelle di riferimento.

Entrambi i dataset (MNIST e Fashion-MNIST) sono in scala di grigi. Per semplicità, tutti i campioni vengono adattati alla risoluzione (32,32).

## Sviluppo

Nel file `separazione_immagini_barbieri_diego.ipynb` è presente il processo di sviluppo, addestramento e valutazione del modello.

Nel precedente file, è inoltre possibile trovare una veloce relazione sulle scelte progettuali e le metriche ottenute durante il processo di sviluppo.

## Conclusioni

Al termine del progetto, il modello che ha raggiunto le migliori prestazioni (unet-5) ha ottenuto le seguenti metriche:
- MSE: 0.0003116435293302134
- STD: 1.2811539746640782e-05


