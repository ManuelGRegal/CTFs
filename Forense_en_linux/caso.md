### Análise forense en Linux
	 
Sobre as 17:07 UTC do día 26 de xuño salta unha alarma no noso sistema de monitorización sobre unha das máquinas que temos na nosa rede interna. Crese que podería estar comprometida e que os atacantes terían conseguido algunha sesión que aínda está aberta. O ataque parece que podería estar realizado desde unha máquina da nosa rede interna.
Inmediatamente realízase un envorcado da memoria RAM do equipo comprometido e envíase mediante netcat a outra máquina da rede (10.2.0.9). Despois apágase a máquina e realízase unha imaxe completa do disco duro en formato EnCase.
Efectúase, ademais, un interrogatorio entre os  usuarios “autorizados” do devandito equipo e ninguén entre as 16:15 e a hora en que se realizou a adquisición conectouse a el, nin de forma local nin remota.
Pídeseche que realices unha análise de evidencias, detectes os vectores de entrada ao sistema e as accións realizadas polos atacantes e xeres unha liña temporal das accións detectadas. 
Nota: Para simplificar á análise podemos descartar calquera evidencia anterior ás 16:15 UTC.

Evidencias aportadas:
- Captura de memoria RAM.
- Perfil de memoria do equipo para o seu traballo con volatility (Ubuntu_3.13.0-24-generic_profile.zip).
- Imaxe do disco duro en formato EnCase.

Descarga de evidencias:
- <a href="https://drive.google.com/file/d/1jTDBAopaXcUZb551nkdHHSExZ1zI8_vB/view?usp=share_link" target="_blank">mirror1</a>
- <a href="https://drive.google.com/file/d/1D5CGbl7QRXA1XRZ_XvlbYZHPf0eTJX1W/view?usp=sharing" target="_blank">mirror2</a>
- <a href="https://drive.google.com/file/d/1o3KVb7U4iONfHtJrUMjmU-_9U8UQYs6x/view?usp=sharing" target="_blank">mirror3</a>

---
### Análisis forense en Linux

Sobre las 17:07 UTC del día 26 de junio salta una alarma en nuestro sistema de monitorización sobre una de las máquinas que tenemos en nuestra red interna. Se cree que podría estar comprometida y que los atacantes habrán conseguido alguna sesión que todavía está abierta. El ataque parece que podría estar realizado desde una máquina de nuestra red interna.

De inmediato se realiza un volcado de la memoria RAM del equipo comprometido y se envía mediante netcat a otra máquina de la red (10.2.0.9). Después se apaga la máquina y se realiza una imagen completa del disco duro en formato EnCase.

Se efectua, además, un interrogatorio entre los  usuarios “autorizados” del dicho equipo; y ninguno entre las 16:15 y la hora en que se realizó la adquisición se conectó a el, ni de forma local ni remota.

Se te pide que realices un análisis de evidencias, detectes los vectores de entrada al sistema y las acciones realizadas por los atacantes y generes una línea temporal de las acciones detectadas. 

Nota: Para simplificar el análisis podemos descartar cualquier evidencia anterior a las 16:15 UTC.

Evidencias aportadas:
- Captura de memoria RAM.
- Perfil de memoria do equipo para su trabajo con volatility (Ubuntu_3.13.0-24-generic_profile.zip).
- Imagen del disco duro en formato EnCase.

Descarga de evidencias:
- <a href="https://drive.google.com/file/d/1jTDBAopaXcUZb551nkdHHSExZ1zI8_vB/view?usp=share_link" target="_blank">mirror1</a>
- <a href="https://drive.google.com/file/d/1D5CGbl7QRXA1XRZ_XvlbYZHPf0eTJX1W/view?usp=sharing" target="_blank">mirror2</a>
- <a href="https://drive.google.com/file/d/1o3KVb7U4iONfHtJrUMjmU-_9U8UQYs6x/view?usp=sharing" target="_blank">mirror3</a>

<br>
<h2 class="text-center">
  <p> </p>
    <p><a href="https://www.iessanclemente.net/" target="_blank">IES San Clemente</a> - <a href="https://www.cifprodolfoucha.es/"  target="_blank">CIFP Rodolfo Ucha Piñeiro</a></p>
</h2>
<br>
<table align="center" cellspacing="50">
<tr>
   <td><h1 align=center><a href="https://www.iessanclemente.net/" target="_blank">IES San Clemente</a></h1></td>
   <td><h1 align=center><a href="https://www.cifprodolfoucha.es/"  target="_blank">CIFP Rodolfo Ucha Piñeiro</a></h1></td>
</tr>
<tr>
    <td><a href="https://www.edu.xunta.gal/" target="_blank"><img class="w-100 mx-auto d-block" style="max-width: 250px;padding: 5px;" src="../imagenes/logo_xunta_positivo.png" /></a></td>
    <td><a href="https://www.edu.xunta.gal/fp/convocatoria-innovacion-2022" target="_blank"><img class="w-100 mx-auto d-block" style="max-width: 250px;padding: 5px;" src="../imagenes/composicion_formacion_profesional_innova.png" /></a></td>
</tr>
</table>
      <p> </p>
      <h6>Actividade desenvolvida dentro do proxecto "Plataforma de retos de ciberseguridade. A gamificación no proceso de adquisición de competencias no ámbito da ciberseguridade", financiado na convocatoria de premios para o desenvolvemento de proxectos de innovación na FP do ano 2022.</h6>
