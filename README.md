# Herramientas de Diagnóstico y Evaluación para Windows

Este repositorio recopila una serie de herramientas útiles para diagnosticar y evaluar el rendimiento de hardware y software en sistemas Windows. A continuación, se describen brevemente las herramientas y se proporcionan enlaces para su descarga o uso.

![imagen](foto.jpeg)

## Índice
1. [Herramientas de Diagnóstico](#herramientas-de-diagnóstico)
2. [Herramientas de Evaluación](#herramientas-de-evaluación)
3. [Otras Herramientas Útiles](#otras-herramientas-útiles)
4. [Sitios y Recursos en Línea](#sitios-y-recursos-en-línea)
5. [Diagnóstico completo desde Windowsa](#diagnóstico-completo-desde-windows)
6. [Comandos MSD para Mejorar el Rendimiento y la Confiabilidad](#comandos-msd-para-mejorar-el-rendimiento-y-la-confiabilidad)
---

## Herramientas de Diagnóstico:

1. **CPU-Z**
   - **Descripción:** Proporciona información detallada sobre la CPU, la memoria y la placa base.
   - **Enlace:** [Descargar CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)

2. **CrystalDiskInfo**
   - **Descripción:** Monitorea la salud y el rendimiento de tus discos duros y unidades SSD.
   - **Enlace:** [Descargar CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/)

3. **GPU-Z**
   - **Descripción:** Ofrece información detallada sobre la tarjeta gráfica, incluyendo especificaciones y sensores de rendimiento.
   - **Enlace:** [Descargar GPU-Z](https://www.techpowerup.com/gpuz/)

4. **HWMonitor**
   - **Descripción:** Supervisa temperaturas, voltajes y velocidades de ventiladores para prevenir sobrecalentamientos.
   - **Enlace:** [Descargar HWMonitor](https://www.cpuid.com/softwares/hwmonitor.html)

5. **HDD Regenerator**
   - **Descripción:** HDD Regenerator es una potente herramienta diseñada para regenerar sectores defectuosos en discos duros, mejorando la integridad de tus datos y la salud de tu disco.
   - **Enlace:** [Descargar HDD Regenerator](http://www.dposoft.net/)

6. **MSI Afterburner**
   - **Descripción:** MSI Afterburner es una aplicación avanzada de ajuste de tarjeta gráfica que te permite controlar y optimizar el rendimiento de tu tarjeta gráfica, supervisar la temperatura y crear perfiles personalizados.
   - **Enlace:** [Descargar MSI Afterburner](https://www.msi.com/page/afterburner)

---

## Herramientas de Evaluación:

7. **CrystalDiskMark**
   - **Descripción:** Realiza pruebas de velocidad de lectura y escritura en tus unidades de almacenamiento.
   - **Enlace:** [Descargar CrystalDiskMark](https://crystalmark.info/en/software/crystaldiskmark/)

8. **MemTest86**
   - **Descripción:** Diagnostica la memoria RAM para detectar posibles problemas.
   - **Enlace:** [Sitio oficial de MemTest86](https://www.memtest86.com/)

9. **FurMark**
   - **Descripción:** FurMark es un software de prueba de estrés que genera una imagen fija de un patrón de puntos en movimiento. Este patrón es muy exigente para el monitor y puede ayudar a identificar problemas de estabilidad.
   - **Enlace:** [Descargar FurMark](https://www.geeks3d.com/furmark/)
  
10. **OCCT**
   - **Descripción:** OCCT es un software de prueba de estrés que puede generar imágenes fijas o en movimiento. OCCT también puede realizar pruebas de estrés de otros componentes del sistema, como la CPU y la GPU.
   - **Enlace:** [Descargar FurMark](https://www.ocbase.com/)

11. **Cinebench**
   - **Descripción:** Realiza pruebas de benchmarking para medir el rendimiento de la CPU y la GPU.
   - **Enlace:** [Descargar Cinebench](https://www.maxon.net/en/cinebench)
  
## Otras Herramientas Útiles:

12. **Hiren's BootCD PE**
   - **Descripción:** Una suite de herramientas de rescate para reparar sistemas y recuperar datos.
   - **Enlace:** [Sitio oficial de Hiren's BootCD PE](https://www.hirensbootcd.org/)

---

## Diagnóstico completo desde Windows

13. **SFC /scannow**: Escanea tu PC en busca de archivos de sistema corruptos.
   ```
   sfc /scannow
   ```

14. **DISM /Online /Cleanup-Image /CheckHealth**: Este comando le permitirá saber si la imagen de Windows está dañada o no.
   ```
   DISM /Online /Cleanup-Image /CheckHealth
   ```
15. **DISM /Online /Cleanup-Image /ScanHealth**: Este comando le permitirá obtener más información sobre la corrupción que se ha encontrado en la imagen de Windows.
   ```
   DISM /Online /Cleanup-Image /ScanHealth
   ```
16. **DISM /Online /Cleanup-Image /RestoreHealth**: Este comando reparará la corrupción que se ha encontrado en la imagen de Windows.
   ```
   DISM /Online /Cleanup-Image /RestoreHealth
   ```

17. **CHKDSK /f /r**: Comprueba y repara los errores del disco duro.
   ```
   chkdsk /f /r
   ```

---

## Diagnóstico de red

18. **Ping**: Envía paquetes de datos a un servidor remoto para comprobar su disponibilidad.
   ```
   ping www.google.com
   ```

19. **Netstat**: Muestra las conexiones de red activas en tu PC.
   ```
   netstat -a
   ```

20. **Ipconfig**: Muestra la configuración de red de tu PC.
   ```
   ipconfig /all
   ```
---

## Otros diagnósticos

21. **Windows Performance Recorder**: Registra datos de rendimiento de tu PC.
   ```
   perfmon /record
   ```

22. **Windows Performance Analyzer**: Analiza los datos de rendimiento registrados por Windows Performance Recorder.
   ```
   perfmon /analyzer
   ```

23. **Verificar el estado de BitLocker**: Muestra el estado de cifrado de las unidades BitLocker.
   ```
   manage-bde -status
   ```

24. **Windows Memory Diagnostic**: Ejecuta la herramienta de diagnóstico de memoria de Windows.
   ```
   mdsched
   ```

## Desfragmentar tu PC desde la línea de comandos
- Abre el desfragmentador de disco integrado de Windows.
```
dfrgui
```
- Desfragmenta la unidad C:.
```
defrag c:
```
- Desfragmenta la unidad C: sin mover los archivos.
```
defrag c: /u
```
- Desfragmenta la unidad C: en segundo plano.
```
defrag c: /t
```

---

## Diagnosticar el procesador

- [**Intel Processor Diagnostic Tool**](https://downloadcenter.intel.com/download/19792/Intel-Processor-Diagnostic-Tool): Esta herramienta te permite realizar pruebas exhaustivas en tu procesador Intel para detectar posibles errores.

- [**AMD Ryzen Master**](https://www.amd.com/en/technologies/ryzen-master): Si tienes un procesador AMD Ryzen, puedes utilizar AMD Ryzen Master para realizar pruebas y verificar el estado de tu procesador.

---

## Comandos MSD para Mejorar el Rendimiento y la Confiabilidad 
El comando MSD es una herramienta poderosa que puede utilizarse para mejorar el rendimiento y la confiabilidad de los sistemas Windows. Sin embargo, es crucial usar el comando con precaución, ya que su uso incorrecto puede dañar o corromper los sistemas.

### Identificación de Problemas de Hardware
Para identificar problemas de hardware, ejecuta el siguiente comando:
```
msd -d maintenancediagnost
```
Este comando escaneará el sistema en busca de problemas de hardware e informará sobre cualquier problema que se encuentre.

### Recopilación de Información del Sistema
Para recopilar información del sistema, ejecuta el siguiente comando:
```
msd -d collectinfo
```
Este comando recopilará información sobre el sistema, como la versión del sistema operativo, la configuración de hardware y el software instalado. La información se guardará en un archivo que se puede utilizar para solucionar problemas o para crear imágenes del sistema.

### Creación de una Imagen del Sistema
Para crear una imagen del sistema, ejecuta el siguiente comando:
```
msd -d createimage
```
Este comando creará una imagen del sistema. La imagen se puede utilizar para restaurar el sistema a un estado anterior o para implementar el sistema en otras computadoras.

### Tareas de Mantenimiento Automatizadas
Para realizar tareas de mantenimiento automatizadas, ejecuta el siguiente comando:
```
msd -d automaint
```
Este comando ejecutará una serie de tareas de mantenimiento automatizadas, como la búsqueda de virus y spyware, y la comprobación de actualizaciones de software.

### Configuración del servicio MSDdiag para el comando msd

```
rem Configuración del inicio automático
sc config msddiag start= auto

rem Consulta del estado del servicio MSDdiag
sc query msddiag

rem Inicio del servicio MSDdiag
sc start msddiag
```

---

## Sitios y Recursos en Línea:
- [Gamepad Tester](https://hardwaretester.com/gamepad) 
- [Bottleneck Calculator](https://pc-builds.com/es/bottleneck-calculator/) - Calculadora de cuellos de botella.
- [System Requirements Lab](https://www.systemrequirementslab.com/cyri)
- [Power Supply Calculator - Cooler Master](https://www.coolermaster.com/power-supply-calculator/)
- [Can I Run It](https://technical.city/es/can-i-run-it) - Verifica si tu sistema cumple con los requisitos de juegos y software.
- [Prueba de Mouse](https://www.onlinemictest.com/es/prueba-de-mouse/)
- [Prueba de Sonido](https://www.onlinemictest.com/es/prueba-de-sonido/)
- [Keyboard Test](https://keyboard-test.space/es/) - Prueba tu teclado en línea.
- [WebcamTests.com](https://es.webcamtests.com/) - Prueba tu cámara web en línea.
- [EIZO Monitor Test](https://www.eizo.be/monitor-test/) - Prueba la calidad de tu monitor.
- [QuickCPU](https://coderbag.com/product/quickcpu) - Herramienta para ajustar la afinidad de núcleo de CPU en Windows.
- [BleachBit](https://www.bleachbit.org/) - Limpia y optimiza tu sistema.
- [Disable CPU Core Parking Utility](https://coderbag.com/product/quickcpu) - Controla el apagado de núcleos de CPU en sistemas multiprocesador.

Utiliza estas herramientas y recursos para mejorar el rendimiento y la gestión de tu sistema Windows.

---

## Licencia
Este proyecto está bajo la licencia [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Puedes compartir, adaptar y utilizar estos archivos siempre que des el crédito correspondiente al autor original.

## Nota importante
Se recomienda encarecidamente hacer una copia de seguridad de los datos importantes antes de continuar. El autor no se hace responsable de ningún daño o problema causado por el mal uso de estas tecnicas.
