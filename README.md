# Parcial-2-

# Parte Conceptual
1.
# En el hacking ético en el campo del footprinting ¿Qué es el reconocimiento activo y cuál es el reconocimiento pasivo?
Respuesta: En el footprinting existen dos tipos de reconocimiento:
# Pasivo: 
consiste en obtener información sin interactuar directamente con el objetivo. No genera tráfico y es difícil de detectar. Ejemplo: búsquedas en Google, redes sociales o WHOIS.
# Activo: 
implica interactuar directamente con el sistema objetivo. Genera tráfico y puede ser detectado. Ejemplo: ping, escaneo de puertos con Nmap.

# ¿Qué son los exploits, payloads y post-exploits?, por favor dar dos ejemplos de los conceptos expuestos.
Respuesta: 
# Exploits: 
son códigos o técnicas que aprovechan una vulnerabilidad en un sistema para acceder o ejecutar acciones no autorizadas. Podemos verlo como exploit de desbordamiento de buffer, exploit de vulnerabilidad en un software desactualizado.
# Payloads: 
es la carga útil que se ejecuta después de explotar la vulnerabilidad. Define qué acción se realiza en el sistema. Aqui es podemos poner como ejemplo abrir una shell remota, instalar un backdoor
# Post-explotación: 
son las acciones que se realizan después de obtener acceso al sistema para mantener control o extraer información.(extraccion de contraseñas)

# ¿Para que sirve metasploit y cómo lo puedo usar en entornos reales para la visualización de diferentes eventos anormales?
Respuesta: 
# Metasploit: 
Es utilizado en el hacking etico para identificar, explotar y validar vulnerabilidades en sistemas.
# Sirve para:
- Realizar pruebas de penetración (pentesting)
- Detectar vulnerabilidades en sistemas
- Simular ataques reales para evaluar la seguridad
- Probar exploits y payloads de forma controlada
# ¿Cómo usarlo en entornos reales para visualizar eventos anormales?
suele  usarse en laboratorios o redes autorizadas para generar tráfico malicioso controlado y así analizar cómo reaccionan los sistemas de seguridad.

# ¿Cúales son las diferencias entre la criptografía clásica, cuántica y post-cuántica?
Respuesta: Las diferencias entre criptografía clásica, cuántica y post-cuántica se basan en la tecnología y el tipo de seguridad que ofrecen.
# Criptografía clásica:
Utiliza algoritmos matemáticos tradicionales para proteger la información. Esta es la más usada actualmente.
# Criptografía cuántica: 
Se basa en principios de la mecánica cuántica para asegurar la comunicación y permite detectar si alguien intercepta los datos.
# Criptografía post-cuántica: 
Son algoritmos diseñados para ser seguros incluso frente a computadoras cuánticas. No usa física cuántica, sino matemáticas resistentes a estos ataques.

# ¿Qué es el blockchain?, ¿Para qué se utiliza actualmente en las criptomonedas? La cuántica usa física cuántica para seguridad, y la post-cuántica busca resistir ataques de computadoras cuánticas con nuevos algoritmos
Respuesta:
# Blockchain:
Cuando hablamos de blockchain hablamos de una tecnologia de resgitro distribuido que almacena información en bloques enlazados y protegidos mediante criptografía. Estos bloques forman una cadena que no se puede modificar fácilmente, lo que garantiza seguridad y transparencia.
# ¿Para qué se utiliza actualmente en las criptomonedas?
Respuesta:
En las criptomonedas, el blockchain se utiliza para:
- Registrar todas las transacciones de forma segura
- Evitar el doble gasto (que una moneda se use dos veces)
- Eliminar la necesidad de intermediarios como bancos
- Garantizar transparencia y confianza entre usuarios
El blockchain es la base que permite que las criptomonedas funcionen de forma segura, descentralizada y confiable.

# ¿Qué protocolos y mecanismos de seguridad se usan en los sistemas biométricos de autenticación?
Respuesta:
Se utilizan diferentes protocolos y mecanismos de seguridad para proteger los datos sensibles (como huellas o reconocimiento facial).
Entre los mas principales tenemos:
# Cifrado (Encryption): 
Protege los datos biométricos durante su almacenamiento y transmisión.
# Hashing: 
Convierte los datos biométricos en valores irreversibles para evitar su reconstrucción.
# Autenticación multifactor (MFA):
Combina biometría con otros factores (contraseña, token). Aquí se usa huella y pin
# Sistemas de detección de vida (Liveness detection): 
Evitan ataques con fotos o réplicas, para ello se utiliza detección de parpadeo o temperatura.
# Control de acceso: 
limita quién puede usar o consultar los datos biométricos.
En biometría se basa en proteger los datos, verificar que el usuario es real y evitar accesos no autorizados.

# Parte de Diseño
2


