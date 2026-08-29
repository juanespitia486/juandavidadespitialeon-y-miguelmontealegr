# juandavidadespitialeon-y-miguelmontealegr
<img width="701" height="102" alt="image" src="https://github.com/user-attachments/assets/6b2bf0ec-2e9b-4a9f-9b26-6ac6f38a299b" />

La ciberseguridad es el conjunto de medidas y prácticas que se usan para proteger computadores, celulares, redes e información de ataques, virus, robos de datos o accesos no autorizados.

 Características principales
 
 Confidencialidad**: Solo las personas autorizadas pueden ver la información.
 
 Integridad**: Los datos no se pueden modificar ni dañar sin permiso.
 
 Disponibilidad**: La información y los sistemas deben estar disponibles cuando se necesiten.
 
 Autenticación**: Verificar que la persona o el dispositivo es quien dice ser.
 
 No repudio**: Que nadie pueda negar que realizó una acción.
 
 <img width="367" height="542" alt="image" src="https://github.com/user-attachments/assets/229bab4e-885f-4f50-9ab7-14999d425213" />
 

 

 <img width="596" height="66" alt="image" src="https://github.com/user-attachments/assets/3dbea24e-7790-48d7-8a99-9128d0d3f10f" />
La triada de seguridad se llama CIA y tiene como objetivo proteger la información en tres cosas importantes:

Confidencialidad: que solo las personas que deben ver la información la puedan ver.
Integridad: que los datos no se cambien ni se dañen.
Disponibilidad: que se pueda usar la información cuando se necesite.

Esas tres cosas son las más importantes para que todo esté seguro.

paso a paso
Uno mete o acerca la tarjeta al datáfono.

El chip de la tarjeta crea un código especial solo para esa compra (ese código es diferente cada vez).

El datáfono revisa que el código esté bien y que la tarjeta no esté clonada.

Después pide el PIN o la firma para confirmar que uno es el dueño de la tarjeta.

La información se manda al banco de forma cifrada (para que nadie la pueda leer fácil).

El banco responde si acepta o rechaza la compra.

<img width="542" height="358" alt="image" src="https://github.com/user-attachments/assets/87b50b7f-debd-4d2b-879b-47c38b6fd687" />

<img width="569" height="65" alt="image" src="https://github.com/user-attachments/assets/6942e345-0c23-44d9-95c4-f0d5fa792582" />

Cuando un computador de la empresa empieza a funcionar mal justo después de descargar un archivo X, hay que sospechar que puede ser un virus, un gusano o un troyano

Desconectar el computador de la red
Lo primero es quitarle el internet y desconectarlo de la red de la empresa para que no contagie a los demás equipos.
Pasar un antivirus actualizado
Ejecutar Windows Defender o un antivirus profesional y hacer un análisis completo del disco duro, especialmente del archivo X.
Revisar el Administrador de tareas
Ver qué programas están corriendo. Si hay procesos raros que consumen mucha memoria o CPU, puede ser malware.
Analizar el comportamiento del archivo X para saber qué tipo de malware es:
Si infecta otros archivos → probablemente es un virus.
Si se replica solo por la red sin que nadie lo abra → probablemente es un gusano.
Si abre puertas traseras o permite que alguien controle el computador desde afuera → probablemente es un troyano.

Revisar los programas que inician con Windows
Ver si el archivo X se agregó a la lista de inicio automático.
Eliminar el malware
Si el antivirus lo detecta, eliminarlo. Si no se puede quitar fácilmente, formatear el computador y restaurar desde una copia de seguridad limpia.
Investigar de dónde vino el archivo X
Para evitar que vuelva a pasar (por ejemplo, si alguien lo descargó de un correo o página no segura).

<img width="573" height="53" alt="image" src="https://github.com/user-attachments/assets/a21283b5-d820-4f8c-b6e5-af3a6c45d25d" />

Sombrero blanco → El “bueno” lo contratan para averiguar fallas en la seguridad
Sombrero gris → Está en el medio, se dedica por curiosidad a ver en que sistemas puede entrar
Sombrero negro → El “malo”, se dedica a entrar en este tipo de sistemas unicamente para conseguir algun beneficio propio
cracker → 

<img width="768" height="420" alt="image" src="https://github.com/user-attachments/assets/7d3c648e-00fe-4c54-878a-f1ba821ceda1" />



<img width="537" height="42" alt="image" src="https://github.com/user-attachments/assets/dcc65f05-f729-4a3d-96e8-42c2d97193f6" />

***Leyes de Habeas Data (Leyes 1266 de 2008 y 1581 de 2012)***
Le dan a las personas el poder de controlar su información personal. Obligan a las empresas y al gobierno a pedir permiso antes de usar datos personales y permiten exigir que los borren o corrijan.


***Ley de Delitos Informáticos (Ley 1273 de 2009):***
Castiga con cárcel o multas a quienes hackeen sistemas, roben información, metan virus o estafen por internet.A Nivel InternacionalLey / EstándarExplicación SencillaRGPD (Unión Europea)La regla de privacidad más estricta del mundo.
Protege los datos de las personas y sanciona duramente a las empresas que los usen mal.

Convenio de BudapestUn acuerdo entre países para perseguir cibercriminales y colaborar entre policías cuando un delito ocurre en internet desde otro país.Normas ISO 27001Una especie de "manual de buenas prácticas" que siguen las empresas para demostrar que sus sistemas informáticos son seguros.

<img width="717" height="400" alt="image" src="https://github.com/user-attachments/assets/d6c3e625-889d-447d-9b21-e4887343b833" />







<img width="552" height="283" alt="image" src="https://github.com/user-attachments/assets/ddeaffd5-4d00-4995-9e3d-ddcb03abd652" />

el paso a paso es el siguiente:
primero tenemos que subir el archivo original a la nube 

despues abrimos la terminal o consola de comando donde crearemos una carpeta: mkdir (mi proyecto) o el nombre que queramos 

luego de eso tenemos que iniciar el repositorio local git init

Entra a la carpeta de tu proyecto:cd ruta/de/tu/carpeta.


Ejecuta el comando de inicio: git init.


Revisa que todo esté bien con: git status


despues de eso creamos un archivo de prueba desde la terminal 
codigo:"mkdir documentos
echo "Código inicial del proyecto" > index.html
mv index.html documentos/"


Guardar los cambios localmente y subirlos a la nube (GitHub):
codigo:git add .
git commit -m "Estructura inicial del proyecto y archivos"
git push -u origin main"

El Usuario 2 abre la terminal en su equipo y clona el repositorio desde la nube:
codigo: "git clone https://github.com/usuario1/proyecto-compartido.git"

Accede a la carpeta clonada para empezar a trabajar con los archivos actualizados:
codigo:"cd proyecto-compartido"

<img width="585" height="33" alt="image" src="https://github.com/user-attachments/assets/abcba221-f4ab-4c97-a80f-35a1cf96cc36" />
<div></div>


<img width="298" height="52" alt="image" src="https://github.com/user-attachments/assets/d5698592-0617-4034-887b-06e550c7efe7" />

tenemos que poner que poner:ping 8.8.8.8


<img width="276" height="33" alt="image" src="https://github.com/user-attachments/assets/d8443df5-a41a-435c-9309-0756b8667082" />
<div></div>
comparar los codigos ip del otro computador 
<div></div>

<img width="294" height="44" alt="image" src="https://github.com/user-attachments/assets/c7a1c950-3066-4dc7-834a-e9067db23656" />

<div></div>

hay una variedad de codigos pero el principal es tasklist

<div></div>

<img width="312" height="71" alt="image" src="https://github.com/user-attachments/assets/98162e34-2937-456b-b20f-c5565b3a1ff1" />

<div></div>


el codigo principal para el almacenamiento de disco es: wmic logicaldisk get caption, freespace, size
y para la ram es:systeminfo | findstr /C:"Total Physical Memory" /C:"Available Physical Memory"

<div></div>

<img width="294" height="58" alt="image" src="https://github.com/user-attachments/assets/b9dcff04-de7d-4bc9-abfe-f96dc1384819" />
una de las funciones o de los mejores codigos es:dism /online /export-driver /destination:"C:\RutaDeDestino"

<img width="700" height="452" alt="image" src="https://github.com/user-attachments/assets/2052b986-7f08-47b3-a0da-3c5a3fd56cca" />
<img width="700" height="428" alt="image" src="https://github.com/user-attachments/assets/2c08d508-99ed-4b63-bcce-c15fe4832b5a" />

RT 1:TecnologíaInformación que debe cifrarseia y control del espacio aéreoDatos de trayectoria de aeronaves, telemetría en tiempo real, identificadores de vuelo, datos de radar, información de control de tráfico aéreo y cualquier dato personal de tripulación/pasajeros.NanosatélitesDatos de telemetría, imágenes satelitales (especialmente de seguridad o militares), comandos de control, datos de posición y cualquier payload sensible.IoT en logísticaUbicación GPS de mercancías, datos de sensores (temperatura, humedad, apertura de contenedores), información de inventarios, datos de clientes y rutas de transporte.Interacción humano-máquinaCredenciales de acceso, biometría, comandos de control, datos de sesión, historial de interacciones y cualquier dato personal del operador.

<img width="568" height="484" alt="image" src="https://github.com/user-attachments/assets/3ade0528-f259-486c-8a73-95f9be261715" />


RT 2:IA y control del espacio aéreoTLS 1.3 + mTLS, IPsec, protocolos aeronáuticos seguros (CPDLC, ADS-B con cifrado), autenticación fuerte (PKI), Zero Trust.NanosatélitesCCSDS (Consultative Committee for Space Data Systems) con cifrado, Space Data Link Security (SDLS), TLS o DTLS para enlaces, autenticación de comandos con firmas digitales.IoT en logísticaMQTT sobre TLS, CoAP + DTLS, HTTPS, OPC UA Security, autenticación por certificados o tokens (OAuth 2.0 / JWT), segmentación de red.Interacción humano-máquinaOAuth 2.0 / OpenID Connect, SAML, MFA (multi-factor), FIDO2 / WebAuthn, TLS 1.3, gestión de sesiones seguras.

<img width="568" height="484" alt="image" src="https://github.com/user-attachments/assets/ed427c49-e8e4-42d6-8a2d-e29d4a02f161" />


RT 3:


1. ¿Qué información de la que manejan esas tecnologías debe estar cifrada?
Toda información sensible, personal, crítica o confidencial debe cifrarse, tanto en tránsito como en reposo. Específicamente:

Tecnología	Información que debe cifrarse
IA y control del espacio aéreo	Datos de trayectoria de aeronaves, telemetría en tiempo real, identificadores de vuelo, datos de radar, información de control de tráfico aéreo y cualquier dato personal de tripulación/pasajeros.
Nanosatélites	Datos de telemetría, imágenes satelitales (especialmente de seguridad o militares), comandos de control, datos de posición y cualquier payload sensible.
IoT en logística	Ubicación GPS de mercancías, datos de sensores (temperatura, humedad, apertura de contenedores), información de inventarios, datos de clientes y rutas de transporte.
Interacción humano-máquina	Credenciales de acceso, biometría, comandos de control, datos de sesión, historial de interacciones y cualquier dato personal del operador.
Regla general: cifrar siempre datos personales (GDPR/LGPD), datos de infraestructura crítica y cualquier información cuya divulgación pueda afectar seguridad o privacidad.

2. ¿Cómo sería el tema de manejo de contraseñas, usuarios y autenticación en la interacción humano-máquina?
En sistemas de interacción humano-máquina (HMI) se recomienda un enfoque de Zero Trust + autenticación fuerte:

Usuarios: cuentas individuales (nunca compartidas), con roles y permisos mínimos necesarios (principio de menor privilegio).
Contraseñas:
Longitud mínima 12-16 caracteres, complejidad alta.
Prohibir reutilización.
Almacenamiento solo como hash (Argon2, bcrypt o scrypt).
Idealmente eliminar contraseñas y usar autenticación sin contraseña.
Autenticación preferida:
MFA obligatorio (algo que sabes + algo que tienes + algo que eres).
Biometría (huella, facial, iris) + dispositivo de confianza.
FIDO2 / WebAuthn o certificados digitales.
Tokens de corta duración (JWT con expiración corta) + refresh tokens rotativos.
Gestión de sesiones: cierre automático por inactividad, detección de anomalías (comportamiento inusual del operador), registro de auditoría completo.
Adicional: cifrado de extremo a extremo de la sesión HMI y aislamiento de la interfaz de control de las redes de datos.
<img width="568" height="484" alt="image" src="https://github.com/user-attachments/assets/527c331c-c77a-4158-9742-70126bec8db6" />


RT 4:Sí, blockchain puede ser muy útil en varios de estos escenarios:

IoT en logística: trazabilidad inmutable de la cadena de suministro, prueba de temperatura/ubicación de mercancía, contratos inteligentes para pagos automáticos.
Nanosatélites: registro inmutable de telemetría y comandos (auditoría), gestión de identidades de satélites.
IA y control aéreo / HMI: registro de decisiones críticas de IA y acciones de operadores (no repudiación), identidades descentralizadas.

<img width="687" height="684" alt="image" src="https://github.com/user-attachments/assets/34b54189-75a2-4afd-a23e-ee013049795b" />

RT 5:Aspecto,Recomendación
Frecuencia,"Datos críticos (telemetría, comandos, logs de control): backup continuo o cada pocos minutos. Datos menos críticos: diario."
Ubicaciones,3 copias mínimo → 2 en medios diferentes → 1 fuera de sitio (offsite / nube) → 1 offline / air-gapped.
Cifrado,Todas las copias cifradas (AES-256 o superior) con gestión de claves separada (HSM o KMS).
Pruebas,Restauración periódica automática + pruebas manuales (al menos trimestral). Objetivo: cero errores de restauración.
Particularidades por tecnología,
Nanosatélites,Backup de telemetría en estaciones terrenas + nube; comandos críticos con firma digital y versionado.
IoT logística,Edge computing con buffer local + sincronización segura a la nube; versionado de firmwares.
IA / control aéreo,Snapshots de modelos de IA + datos de entrenamiento + logs de decisiones; redundancia geográfica.
HMI,"Backup de configuraciones de usuario, perfiles y logs de auditoría; posibilidad de rollback rápido."
<img width="768" height="684" alt="image" src="https://github.com/user-attachments/assets/342914df-44e0-4677-821b-39ff369f653a" />

6
<img width="1168" height="784" alt="image" src="https://github.com/user-attachments/assets/8ff3026d-364c-4d8b-8321-d304477c0132" />
profe la otra parte no la puede hacer, ya q mi computador no prende 



