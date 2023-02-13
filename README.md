# Barra semplice
[crates.io](crates.io/crates/simple_barhttps://crates.io/crates/simple_bar)

Una barra di avanzamento del terminale estremamente minimale per Rust.  

## Esempio

```Rust
use std::{thread::sleep, time::Duration};
use simple_bar::ProgressBar;

let num_iterations = 500;
let length = 100;
let eta = false
let mut bar = ProgressBar::default(num_iterazioni, lunghezza, eta);

per _ in 0..num_iterazioni {
    bar.update();
    sleep(Duration::from_millis(200));
}
```

Questo esempio genera il seguente output:
![il codice precedente genera](https://mie-res.netlify.app/simple_bar_example.png)

Tradotto con www.DeepL.com/Translator (versione gratuita)
