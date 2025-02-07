# Windows Server Automation Repo  

Dette repoet inneholder PowerShell-skript og konfigurasjonsfiler for å sette opp en sekundær domene-kontroller, DHCP-failover og overvåking med Zabbix.  

## 📂 **Innhold**  

### 🔹 `dc2-setup.ps1`  
PowerShell-skript for å konfigurere **DC2** som en sekundær domene-kontroller.  

### 🔹 `dhcp-failover.ps1`  
Konfigurerer DHCP-failover mellom DC1 og DC2 for redundans.  

### 🔹 `zabbix-agent-config.conf`  
Konfigurasjonsfil for **Zabbix-agent** på DC2.  

### 🔹 `Export-DHCPLeases.ps1`  
Skript for å eksportere DHCP-leases til en CSV-fil.  

### 🔹 `README.md`  
Denne filen – en oversikt over repoet og filene.  

## 📌 **Bruk**  
- Kjør `dc2-setup.ps1` for å sette opp DC2.  
- Kjør `dhcp-failover.ps1` for å aktivere DHCP-failover.  
- Installer Zabbix-agenten og bruk `zabbix-agent-config.conf` for riktig konfigurasjon.  
- Kjør `Export-DHCPLeases.ps1` for å hente DHCP-leases.  

For detaljerte instruksjoner, se dokumentasjonen eller kommentarer i skriptene. 🚀  
