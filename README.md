# Epicode M5W1D1 - Pratica React

Questo repository contiene le risposte all'esercizio teorico sui fondamenti di ReactJS.

### 1. Cos'è ReactJS?

React è una libreria JavaScript open source sviluppata da Meta per creare interfacce utente (UI) dinamiche e veloci, specialmente per applicazioni web a pagina singola (SPA). Si basa sulla creazione di componenti riutilizzabili e sull'uso del Virtual DOM per aggiornare le pagine in modo efficiente senza ricaricarle

React ha un **Virtual DOM** che aggiorna dinamicamente ogni componente di pagina che lo richiede, senza la necessità di refreshare tutta la pagina. L'esperienza utente rimane dinamica, come se cambiassimo pagina, ma in realtà lavoriamo su una **Single Page Application (SPA)**, avendo un codice più organizzato e pulito.

### 2. ReactJS è un framework, non una libreria.

**Falso**: è una libreria.

### 3. Il file package.json contiene...

- Molte informazioni utili, come ad esempio l’elenco di tutte le dipendenze richieste dall’applicazione.

### 4. create-react-app è l'unico modo possibile per creare un'applicazione React.

**Falso**: `create-react-app` è un comando dismesso. È consigliato l'utilizzo di Vite tramite il comando:
`npm create vite@latest <my-app-name>`
_(Sostituire `<my-app-name>` con il nome da dare alla cartella dell'app oppure con `.` per creare il progetto direttamente nella cartella corrente)._

### 5. Qual è il comando da lanciare nel terminale per creare una nuova create-react-app con nome "test"?

- `npx create-react-app test`

### 6. Cos'è un componente React?

- Un blocco di logica/contenuto riutilizzabile all’interno dell’applicazione.

### 7. Un componente React può venire creato in tre modi: come funzione, classe o interfaccia.

**Falso**: può essere creato come funzione o come classe.

### 8. Le props sono frammenti di informazione assegnati all’invocazione di un componente React, utili al fine di rendere il componente dinamico e più riutilizzabile.

**Vero**

### 9. Le props possono essere passate solamente da un componente genitore ad un componente figlio, non è possibile fare il contrario

**Vero**

### 10. Da dove possono venire recuperate le props in un componente creato come classe?

- Possono essere recuperate all’interno dell'oggetto `this`, dentro un sotto-oggetto chiamato `props`.
