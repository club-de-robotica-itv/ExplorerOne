Mapa del proyecto-|
                  |-Software-|
                  |          |-Embedido-|
                  |          |          |-Sistema de arranque-|
                  |          |          |                     |-Test-|
                  |          |          |                     |      |-Energia
                  |          |          |                     |      |-Temperatura
                  |          |          |                     |      |-Signos vitales
                  |          |          |                     |      |-Interrupciones
                  |          |          |                     |      |-Errores
                  |          |          |                     |      |-Dispositivos
                  |          |          |                     |      |-Comunicacion
                  |          |          |                     |-Boot-|
                  |          |          |                            |-Inicio de Logs
                  |          |          |                            |-Inicio de LCD-I2C
                  |          |          |                            |-Inicio de Teclado
                  |          |          |                            |-Menu de arranque
                  |          |          |                            |-Carga del sistema operativo
                  |          |          |-Sistema operativo-|
                  |          |                              |-Kernel-|
                  |          |                              |        |-Sistema de archivos
                  |          |                              |        |-Sistema de usuarios
                  |          |                              |        |-Sistema de permisos
                  |          |                              |        |-API de Control de hardware
                  |          |                              |-Daemons-|
                  |          |                              |         |-Sistema de emergencia-|
                  |          |                              |         |                       |-Fallo de energia
                  |          |                              |         |                       |-Exceso de temperatura
                  |          |                              |         |                       |-Signos vitales
                  |          |                              |         |                       |-Interrupciones
                  |          |                              |         |                       |-Codigos de error
                  |          |                              |         |                       |-Bloqueo de actuadores
                  |          |                              |         |                       |-Sistemas de comunicacion
                  |          |                              |         |-Gestion de dispositivos-|
                  |          |                              |         |                         |-Comunicacion serial
                  |          |                              |         |                         |-Comunicacion I2C
                  |          |                              |         |                         |-Comunicacion USB
                  |          |                              |         |-Gestion de red-|
                  |          |                              |         |                |-Protocolos de comunicacion y transporte
                  |          |                              |         |                |-Conexion a WiFi
                  |          |                              |         |                |-Sistema de cifrado
                  |          |                              |         |-Conexion al servidor central-|
                  |          |                              |         |                              |-HTTP/MQTT User-Agent
                  |          |                              |         |                              |-WebSocket Client
                  |          |                              |         |-Sistema de actualizaciones remotas
                  |          |                              |-Aplicaciones-|
                  |          |                                             |-Menu principal
                  |          |                                             |-Terminal
                  |          |                                             |-Control manual
                  |          |                                             |-REPL API Client
                  |          |                                             |-Configuraciones-|
                  |          |                                             |                 |-WiFi
                  |          |                                             |                 |-Host
                  |          |                                             |-Troubleshooting
                  |          |-Remoto-|
                  |                   |-Kernel-|
                  |                   |        |-Path planning
                  |                   |        |-Vision artificial
                  |                   |-API website
                  |                   |-API robots
                  |                   |-Dase de datos-|
                  |                   |               |-Panel de administracion
                  |                   |               |-Configuraciones
                  |                   |               |-Usuarios-|
                  |                   |               |          |-Datos del sistema-|
                  |                   |               |          |                   |-ID
                  |                   |               |          |                   |-Nivel de acceso
                  |                   |               |          |                   |-Permisos
                  |                   |               |          |-Datos publicos-|
                  |                   |               |          |                |-Nombre de usuario
                  |                   |               |          |                |-Estado de conexion
                  |                   |               |          |-Datos privados-|
                  |                   |               |                           |-Correo
                  |                   |               |                           |-Contraseña
                  |                   |               |                           |-Token
                  |                   |               |-Robots-|
                  |                   |               |        |-Historial de signos vitales-|
                  |                   |               |        |                             |-Standby
                  |                   |               |        |                             |-Carga-|
                  |                   |               |        |                             |       |-Estado de la fuente
                  |                   |               |        |                             |       |-Nivel
                  |                   |               |        |                             |       |-Tiempo de carga o descarga
                  |                   |               |        |                             |-Temperatura interna
                  |                   |               |        |                             |-Tiempo de autonomia
                  |                   |               |        |                             |-Estado de conexion
                  |                   |               |        |                             |-Transferencia de datos
                  |                   |               |        |                             |-Robot Status Code
                  |                   |               |        |-Historial de actividades-|
                  |                   |               |                                   |-Sensores-|
                  |                   |               |                                   |          |-Ubicacion
                  |                   |               |                                   |-Actuadores
                  |                   |               |                                   |-Logs del sistema
                  |                   |               |-Datos-|
                  |                   |                       |-Mapas-|
                  |                   |                       |       |-Estereolitografico
                  |                   |                       |       |-Por vision artificial
                  |                   |                       |-Objetos
                  |                   |-Control y comando-|
                  |                                       |-Acceso publico-|
                  |                                       |                |-Login
                  |                                       |                |-Live Stream
                  |                                       |                |-Creditos
                  |                                       |-Acceso privado-|
                  |                                                        |-Mapa Interactivo-|
                  |                                                        |                  |-Mapa global
                  |                                                        |                  |-Rutas y posiciones
                  |                                                        |                  |-Informacion basica
                  |                                                        |                  |-Historia del mapa
                  |                                                        |-Robots-|
                  |                                                        |        |-Historial de ubicaciones
                  |                                                        |        |-Historial de signos vitales
                  |                                                        |        |-Historial de actividades
                  |                                                        |        |-Control remoto-|
                  |                                                        |                         |-Automatico-|
                  |                                                        |                         |            |-Path planning
                  |                                                        |                         |-Manual-|
                  |                                                        |                                  |-Via HUD
                  |                                                        |                                  |-Via panel
                  |                                                        |-Monitor global-|
                  |                                                        |                |-Camaras
                  |                                                        |                |-Mapas
                  |                                                        |                |-Sensores
                  |                                                        |                |-Informacion del sistema
                  |                                                        |                |-Signos vitales
                  |                                                        |-Configuraciones-|
                  |                                                        |                 |-Cambio de usuario
                  |                                                        |                 |-Cambio de correo
                  |                                                        |                 |-Cambio de contraseña
                  |                                                        |-Logout
                  |-Hardware-|
                             |-Fuente-|
                             |        |-Cargador DC
                             |        |-Panel solar
                             |        |-Cargador inalambrico
                             |-Almacenamiento-|
                             |                |-Sensores-|
                             |                |          |-Carga
                             |                |          |-Voltimetro
                             |                |          |-Amperimetro
                             |                |-Bateria-|
                             |                          |-Conexion de celdas
                             |                          |-Sistema de carga
                             |                          |-Sistema de descargas
                             |-Digital-|
                             |         |-Comunicacion-|
                             |         |              |-Serial
                             |         |              |-I2C
                             |         |              |-USB
                             |         |              |-WiFi
                             |         |-Control-|
                             |                   |-Motherboard
                             |                   |-Entrada / Salida-|
                             |                                      |-Panel de control a bordo-|
                             |                                      |                          |-LCD-I2C
                             |                                      |                          |-Teclado
                             |                                      |-Sensores-|
                             |                                      |          |-Temperatura interna
                             |                                      |-Actuadores-|
                             |                                                   |-Ventilador
                             |-Potencia-|
                                        |-Actuadores-|
                                        |            |-Digitales
                                        |            |-Analogicos
                                        |-Transferencia inalambrica