![GitHub release (latest by date)](https://img.shields.io/github/v/release/TheFidax/SusiOverI2c)
![GitHub Release Date](https://img.shields.io/github/release-date/TheFidax/SusiOverI2c?color=blue&label=last%20release)
![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/TheFidax/SusiOverI2c/latest?color=orange)
[![arduino-library-badge](https://www.ardu-badge.com/badge/SusiOverI2c.svg)](https://www.ardu-badge.com/SusiOverI2c)
[![License](https://img.shields.io/github/license/TheFidax/SusiOverI2c)](#)

# Indice
* [Introduzione SUSI Over I2c](#SUSI-Over-I2c)
* [Video di Presentazione](#Video-Presentazione)
* [API Libreria](#API-Libreria)
* [Esempi di Utilizzo](#Esempi-di-Utilizzo)

------------

# SUSI Over I2c
Questa libreria permette di utilizzare il bus [Wire / I2c](https://it.wikipedia.org/wiki/I%C2%B2C) per trasmettere i dati Rcn600 SUSI ad altri dispositivi.</br>
Lo Slave SUSI sara' il Master per il bus I2c; la libreria permette di avere tutti i mesaggi previsti dalla normativa [Rcn600](http://www.normen.railcommunity.de/RCN-600.pdf) compresa, mediante sistema interno, la *Lettura/Scrittura* delle CVs.</br>

------------

# Video Presentazione
[![Video Presentazione](https://img.youtube.com/vi/xxxxx/0.jpg)](http://www.youtube.com/watch?v=xxxxx)

------------

# API Libreria
Le Api per la libreria sono nel file "[readme.md](https://github.com/TheFidax/SusiOverI2c/blob/master/src/readme.md)" disponibile sotto la cartella '[src](https://github.com/TheFidax/SusiOverI2c/tree/master/src)'.</br>

------------

# Esempi di Utilizzo
Sotto la cartella "[examples](https://github.com/TheFidax/SusiOverI2c/tree/main/examples)" sono disponibili esempi sia per i dispositivi [Slave](https://github.com/TheFidax/SusiOverI2c/tree/main/examples/Slave) che [Master](https://github.com/TheFidax/SusiOverI2c/tree/main/examples/Master).</br>
Sotto la cartella *Master* e' disponibile un [esempio](https://github.com/TheFidax/SusiOverI2c/tree/main/examples/Master/LedBuiltin_ReadWriteCVs) su come utilizzare il bus [Rcn600](https://github.com/TheFidax/Rcn600) per pilotare device *SusiOverI2c*.</br>

------------
