Este script en Bash automatiza la explotación de vulnerabilidades Local File Inclusion (LFI) en aplicaciones web. Prueba múltiples rutas críticas del sistema (como /etc/passwd, /etc/shadow, archivos de configuración y claves SSH)

Uso:

    ./EnumCode.sh "http://victim.com/download?ticket="

Instalación:

    git clone https://github.com/tu-usuario/lfi-scanner.git
    cd lfi-scanner
    chmod +x lfi_scanner.sh
