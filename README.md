# Herramientas de Diagnóstico y Evaluación para Windows

Este repositorio recopila una serie de herramientas útiles para diagnosticar y evaluar el rendimiento de hardware y software en sistemas Windows. A continuación, se describen brevemente las herramientas y se proporcionan enlaces para su descarga o uso.

## Índice
1. [Herramientas de Diagnóstico](#herramientas-de-diagnóstico)
2. [Herramientas de Evaluación](#herramientas-de-evaluación)
3. [Otras Herramientas Útiles](#otras-herramientas-útiles)
4. [Sitios y Recursos en Línea](#sitios-y-recursos-en-línea)
5. [Diagnóstico completo desde Windowsa](#diagnóstico-completo-desde-windows)

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

## Herramientas de Evaluación:

7. **CrystalDiskMark**
   - **Descripción:** Realiza pruebas de velocidad de lectura y escritura en tus unidades de almacenamiento.
   - **Enlace:** [Descargar CrystalDiskMark](https://crystalmark.info/en/software/crystaldiskmark/)

8. **MemTest86**
   - **Descripción:** Diagnostica la memoria RAM para detectar posibles problemas.
   - **Enlace:** [Sitio oficial de MemTest86](https://www.memtest86.com/)

9. **FurMark**
   - **Descripción:** Realiza pruebas de estrés en tu tarjeta gráfica para evaluar su rendimiento y estabilidad.
   - **Enlace:** [Descargar FurMark](https://www.geeks3d.com/furmark/)

## Otras Herramientas Útiles:

10. **Hiren's BootCD PE**
   - **Descripción:** Una suite de herramientas de rescate para reparar sistemas y recuperar datos.
   - **Enlace:** [Sitio oficial de Hiren's BootCD PE](https://www.hirensbootcd.org/)

11. **Cinebench**
   - **Descripción:** Realiza pruebas de benchmarking para medir el rendimiento de la CPU y la GPU.
   - **Enlace:** [Descargar Cinebench](https://www.maxon.net/en/cinebench)


## Diagnóstico completo desde Windows

4. **SFC /scannow**: Escanea tu PC en busca de archivos de sistema corruptos.
   - `sfc /scannow`

5. **DISM /Online /Cleanup-Image /RestoreHealth**: Repara los componentes dañados del sistema operativo Windows.
   - `DISM /Online /Cleanup-Image /RestoreHealth`

6. **CHKDSK /f /r**: Comprueba y repara los errores del disco duro.
   - `chkdsk /f /r`

7. **Windows Memory Diagnostic**: Herramienta integrada de Windows que prueba la memoria de tu PC en busca de errores.
   - `Windows Memory Diagnostic`

## Diagnóstico de red

8. **Ping**: Envía paquetes de datos a un servidor remoto para comprobar su disponibilidad.
   - `ping www.google.com`

9. **Netstat**: Muestra las conexiones de red activas en tu PC.
   - `netstat -a`

10. **Ipconfig**: Muestra la configuración de red de tu PC.
   - `ipconfig /all`

## Otros diagnósticos

11. **Windows Performance Recorder**: Registra datos de rendimiento de tu PC.
   - `perfmon /record`

12. **Windows Performance Analyzer**: Analiza los datos de rendimiento registrados por Windows Performance Recorder.
   - `perfmon /analyzer`

## Desfragmentar tu PC desde la línea de comandos
- **`dfrgui`**: Abre el desfragmentador de disco integrado de Windows.
- **`defrag c:`**: Desfragmenta la unidad C:.
- **`defrag c: /u`**: Desfragmenta la unidad C: sin mover los archivos.
- **`'defrag c: /t'`**: Desfragmenta la unidad C: en segundo plano.

## Diagnosticar el procesador

- [**Intel Processor Diagnostic Tool**](https://downloadcenter.intel.com/download/19792/Intel-Processor-Diagnostic-Tool): Esta herramienta te permite realizar pruebas exhaustivas en tu procesador Intel para detectar posibles errores.

- [**AMD Ryzen Master**](https://www.amd.com/en/technologies/ryzen-master): Si tienes un procesador AMD Ryzen, puedes utilizar AMD Ryzen Master para realizar pruebas y verificar el estado de tu procesador.

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

## Licencia
Este proyecto está bajo la licencia [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Puedes compartir, adaptar y utilizar estos archivos siempre que des el crédito correspondiente al autor original.

