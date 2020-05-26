http://kinomakino.blogspot.com/2020/05/file-integrity-monitor-en-windows-con.html

1.- Montar Active directory de ejemplo:
https://medium.com/@kamran.bilgrami/ethical-hacking-lessons-building-free-active-directory-lab-in-azure-6c67a7eddd7f

2.- Probar ataque Mimikatz:

FICHERO MIMI

2.3.2.- crackear ntlm http://kinomakino.blogspot.com/2017/04/cracking-ntlm-hashes-con-azure-gpu-por.html

Username : administrador2
         * NTLM     : 5074a6992c63485460928c1c9fdad6b5
         * Username : administrador2
         * Password : Patatasfritas2020!!!





2.4.- Auditar cambios en la ramas de registro:
http://kinomakino.blogspot.com/2020/01/auditar-cambios-en-el-registro-sin.html
3.- Instalar BloodHound en Kali linux:
https://stealingthe.network/quick-guide-to-installing-bloodhound-in-kali-rolling/
3.1.- Generar información y analizar.
https://github.com/BloodHoundAD/BloodHound/blob/master/Ingestors/SharpHound.ps1
3.2.- Generar contenido:
https://github.com/davidprowe/BadBlood
3.3.- Volver a generar información y analizar.
3.4.- Comprobar la ejecución de Bloodhound:
http://kinomakino.blogspot.com/2020/01/detectar-enumeracion-de-usuarios-en.html

4.- Instalar y ejecutar Lazagne:
https://github.com/AlessandroZ/LaZagne

4.1.- ¿Cómo detectarías la ejecución de Lazagne? 
http://kinomakino.blogspot.com/2019/03/deteccion-de-lazagne-easy-baby.html

5.- Genera un diccionaro con 5 claves. Genera un usuario en AD con una clave que esté en esa lista. Sigue el siguiente proceso:
http://kinomakino.blogspot.com/2020/01/blue-team-auto-fuerza-bruteate-active.html

6.-  Hardening para Services Hijacking.
http://kinomakino.blogspot.com/2020/01/t1034-enumera-y-soluciona-el-problema.html

7.- Aumento de logs: 

Computer Configuration -> Policies -Windows Settings -> Security Settings -> Advanced Audit Policy Configuration

Account Logon
Ensure ‘Audit Credential Validation’ is set to ‘Success and Failure’

Account Management
Audit ‘Application Group Management’ is set to ‘Success and Failure’
Audit ‘Computer Account Management’ is set to ‘Success and Failure’
Audit ‘Other Account Management Events’ is set to ‘Success and Failure’
Audit ‘Security Group Management’ is set to ‘Success and Failure’
Audit ‘User Account Management’ is set to ‘Success and Failure’

Detailed Tracking
Audit ‘PNP Activity’ is set to ‘Success’
Audit ‘Process Creation’ is set to ‘Success’

Logon/Logoff
Audit ‘Account Lockout’ is set to ‘Success and Failure’
Audit ‘Group Membership’ is set to ‘Success’
Audit ‘Logoff’ is set to ‘Success’
Audit ‘Logon’ is set to ‘Success and Failure’
Audit ‘Other Logon/Logoff Events’ is set to ‘Success and Failure’
Audit ‘Special Logon’ is set to ‘Success’

Object Access
Audit ‘Removable Storage’ is set to ‘Success and Failure’

Policy Change
Audit ‘Audit Policy Change’ is set to ‘Success and Failure’
Audit ‘Authentication Policy Change’ is set to ‘Success’
Audit ‘Authorization Policy Change’ is set to ‘Success’

Privilege Use
Audit ‘Sensitive Privilege Use’ is set to ‘Success and Failure’

System
Audit ‘IPsec Driver’ is set to ‘Success and Failure’
Audit’ Other System Events’ is set to ‘Success and Failure’
Audit ‘Security State Change’ is set to ‘Success’
Audit ‘Security System Extension’ is set to ‘Success and Failure’
Audit ‘System Integrity’ is set to ‘Success and Failure’

8.- CONFIGURAR POWERSHELL TRANSCRIPT CON GPO:

https://sid-500.com/2017/11/07/powershell-enabling-transcription-logging-by-using-group-policy/


10.- EJERCICIOS DEL TOP:


