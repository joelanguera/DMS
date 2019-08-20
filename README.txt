Aquest es un projecte per descarregar música d'spotify.

***sp***
Amb sp podem controlar spotify des del terminal


***PulseAudio***
PulseAudio is a networked low-latency sound server for Linux, POSIX and
Windows systems.


Amb PulseAudio creem un combined sink i hi afegim el sink-input d'spotify
i el default_output del nostre ordinador. D'aquesta manera podrem enregistrar
aquest combined-sink i tambe podem escolar el que estem enregistrant. 


-----LINKS-----
Funcionament de l'audio en Linux:
https://opensource.com/article/17/1/linux-plays-sound
Funcionament PulseAudio
https://gavv.github.io/articles/pulseaudio-under-the-hood/
Enviar audio a Android
https://superuser.com/questions/605445/how-to-stream-my-gnu-linux-audio-output-to-android-devices-over-wi-fi
SOLUCIO
https://askubuntu.com/questions/60837/record-a-programs-output-with-pulseaudio
-----LINKS-----

man pulse-cli-syntax

***MILLORES***
Reserva de caracters en els noms de les cançons
Poder escollir si graba en segon pla (no escoltem spotify)
Fe robust el pgrograma
Elminiar Anuncis
Eliminar fitxer si s'apaga el programa abans d'hora
Poder enregistrar de la font que tu vulguis:
	Per ex: dms list
	I apareix tot un llistat de les fonts disponibles de descàrrega


***BUGS***
Bug al començar a enregistrar amb la canço "Safe & Sound":
    lame: excess arg Heaven
    
