## ✨ 42 Libft

📚 **Libft** è un progetto della scuola 42 che consiste nell'implementazione di una libreria personale in linguaggio C. L'obiettivo è ricreare alcune delle funzioni standard della libreria C, oltre ad aggiungere funzionalità personalizzate.

---

### 🎯 Obiettivi

- ✅ Comprendere e implementare funzioni di base della libreria standard C.
- 🧠 Migliorare la padronanza della gestione della memoria.
- 🛠️ Sviluppare codice pulito, modulare e ben documentato.

---

### 🔑 Funzionalità principali

- ✂️ Funzioni di manipolazione di stringhe (`ft_strlen`, `ft_strcpy`, `ft_strdup`, ecc.)
- 📦 Funzioni di gestione della memoria (`ft_memset`, `ft_memcpy`, `ft_calloc`, ecc.)
- 🔤 Funzioni di manipolazione di caratteri (`ft_isalpha`, `ft_isdigit`, `ft_toupper`, ecc.)
- 🔗 Funzioni per liste collegate (`ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, ecc.)

---

### ⚙️ Come compilare

Per compilare la libreria:

```bash
make
```

🏗️ Questo comando genererà il file libft.a che potrà essere linkato ad altri progetti.

---

### 🚀 Utilizzo

Per utilizzare la libreria nel tuo progetto, includi il file header:

```c
#include "libft.h"
```

E aggiungi `libft.a` durante la compilazione:

```bash
gcc main.c -L. -lft
```

---

### 👤 Autore

💻 Progetto realizzato da ncortigi per la scuola 42
