
# Colibrí
Colibri esta basado en latino 0.8.5 y consiste en quedarse con lo más básico
que se necesita para programar y con el que seas tu que creas tus propias 
herramientas si deseas algo más completo, listo para usar, sin romperse la
cabeza, la sopa lista, usa Latino, con Colibri vas a tener que 
pelar cebollas para la sopa y vas a llorar.

### Instalar en Linux

Cualquier versión/distribución de linux

```bash
 git clone --recursive https://github.com/robincoello/colibri
 cd colibri
 git submodule update --init --recursive
 cmake .
 make
 sudo make install
```



### Instalar en Windows
1. Descargue el instalador http://lenguaje-latino.org/descargas/
2. Descompima el archivo zip
3. Ejecute el instalador

#### Nota:
Puede requerir el framework de C++, descarguelo desde la pagina oficial de Microsoft:
https://www.microsoft.com/es-ES/download/details.aspx?id=48145

### COMPILAR

---

|Requiere | Versión | SO |
| :---    |    ---: |:---|
| bison   |    3.04 |Linux|
| flex    |  2.5.39 |Linux|
| cmake   |   3.3.1 |Linux|
| gcc     |   4.9.3 |Linux|
| g++     |   4.9.3 |Linux|
| libjansson-dev |   2.9   |Linux|
| libcurl4-openssl-dev |  |Linux|
| curl    | 7.47.0 |Linux|
| kernel-devel| |Solo Fedora|
| jsoncpp| |Solo Fedora|
--

### DESINSTALAR

#### 1- Opción
```bash
# Si instalaste con `sudo make install`:
sudo ./desinstalar.sh
```

#### 2- Opción

Puedes ver un video de como proceder aca https://youtu.be/Q5xGm_Bp22k

Pirmero debes saber donde esta instalado

 ```bash
 whereis latino
 ```

 te dara algo parecido a esto

 ```bash
 latino: /usr/local/bin/latino

 ```

 ahora que sabemos donde esta solamente lo borramos
 ```bash
 sudo rm /usr/local/bin/latino

 ```
####Cualquier aportación o sugerencia es bienvenida.
# colibri
