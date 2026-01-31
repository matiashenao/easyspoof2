# ⚡ EasySpoof by Hacknet ⚡
```text
███████╗ █████╗ ███████╗██╗   ██╗███████╗██████╗  ██████╗  ██████╗ ███████╗
  ██╔════╝██╔══██╗██╔════╝╚██╗ ██╔╝██╔════╝██╔══██╗██╔═══██╗██╔═══██╗██╔════╝
  █████╗  ███████║███████╗ ╚████╔╝ ███████╗██████╔╝██║   ██║██║   ██║█████╗  
  ██╔══╝  ██╔══██║╚════██║  ╚██╔╝  ╚════██║██╔═══╝ ██║   ██║██║   ██║██╔══╝  
  ███████╗██║  ██║███████║   ██║   ███████║██║     ╚██████╔╝╚██████╔╝██║     
  ╚══════╝╚═╝  ╚═╝╚══════╝   ╚═╝   ╚══════╝╚═╝      ╚═════╝  ╚═════╝ ╚═╝      
        [ By: Hacknet | V1.0 ]
-----------------------------------------------------------------------------
```

EasySpoof es una herramienta de automatización para ataques de Man-In-The-Middle (MITM) y denegación de servicio local (ARP Banning), diseñada para entornos de auditoría de red en Kali Linux. Esta utilidad simplifica el uso de bettercap y arp-scan en una interfaz limpia y rápida.

---

## 🛠 Características Técnicas
- **Auto-Discovery:** Mapeo inteligente de nodos y vendors mediante ARP.
- **Dependency Manager:** El script configura automáticamente su propio entorno de trabajo.
- **Advanced Spoofing:** Algoritmo optimizado para interceptar tráfico sin pérdida de paquetes.
- **Seamless Exit:** Restauración automática de la integridad de la red al finalizar.

## 🚀 Despliegue Rápido

```bash
# Descargar repositorio
git clone https://github.com/matiashenao/easyspoof.git
cd easyspoof

# Permisos, dependencias y ejecución
chmod +x easyspoof
sudo apt install dsniff -y
sudo ./easyspoof
```
⚖️ Aviso Legal
Este software ha sido desarrollado con fines de investigación y seguridad ofensiva ética. Hacknet no se responsabiliza por el uso indebido de esta herramienta fuera de entornos controlados o sin autorización explícita.
