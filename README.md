# Practica-1

Aquesta pràctica m'ha servit sobretot per inicialitzar-me amb l'ESP32 i el Platformio ja que ambdues coses són novetat per a mi.

En aquesta pràctica hem vist com, amb ajuda del codi trobat, encenem i apaguem un led assignat a un pin (el qual hem hagut de definir al principi del nostre codi relacionat al pin de sortida) amb intervals de 500 mil·lisegons, i que a la vegada ens surti el seu respectiu mode (ON/OFF) a la pantalla que tenim a l'ordinador.
Aquest interval l'aconseguirem creant un bucle infinit ja que sino el led nomñes canviaria 1 cop o els que se li assignés, és a dir, l'alternació ON/OFF tindria una duració finita però gràcies al loop farem que la duració pugui ser infinita, això si, sempre respectant el delay el qual li hem establert, que en aquest cas són 500 mil·lisegons com ja he esmentat abans.
