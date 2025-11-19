# OBIETTIVO
Creare un QR code che, se scannerizzato, reindirizza ad un PDF o ad un file qualsiasi usando Github.

In questo caso io uso un PDF di prrova, ma questa cosa funziona con tutti i tipi di file (.jpg, .png, .zip, ...)

# COME FARE
1. Prepara il PDF e rinominalo con qualcosa di breve (menu.pdf o simili)
2. Crea una nuova repository (+ in alto a dx)
3. Aggiungi il PDF
4. Crea un link:
   - Settings
   - pages
   - “Deploy from a branch”
   - branch: main
   - folder: /(root)
   - salva
5. Copia il link che ti ha dato (es. https://albalbero.github.io/pdf_sample/)
6. Aggiungi il nome del file (es. https://albalbero.github.io/pdf_sample/sample.pdf)
7. Finito
