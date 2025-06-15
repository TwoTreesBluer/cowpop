# 🖥️ ManuLab Terminal

Transforme seu terminal gelado em um centro de comando galáctico!  
Este pacote `.deb` instala uma experiência personalizada de boas-vindas no terminal do Pop!_OS (ou qualquer Debian-based), com:

- Figuras ASCII aleatórias via `cowsay` (incluindo Tux, Shrek, Darth Vader e mais)
- Mensagem fixa de entrada: **"Bem-vindo ao Laboratório ManuLab!"**
- Informações do sistema coloridas e úteis:
  - IP local
  - Memória RAM usada
  - Carga da CPU
  - Temperatura da CPU
  - Status da bateria
  - Data e hora
  - Nome da máquina
- Estilo `lolcat` 🌈 + fonts monoespaçadas elegantes

---

## 📦 O que está incluído

- Script: `/opt/manulab-terminal/boasvindas.sh`
- Cowfiles extras: `shrek.cow`, `bender.cow`, `megaman.cow`, etc.
- Entrada automática no `.bashrc` para rodar o script a cada novo terminal
- Dependências: `cowsay`, `lolcat`, `fortune`, `acpi`, `lm-sensors`

---

## 🚀 Instalação

```bash
sudo dpkg -i manulab-terminal_1.0.deb
sudo apt install -f
sudo sensors-detect
 _________________________________
< Bem-vindo ao Laboratório ManuLab! >
 ---------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

🛸 Nome da máquina:   pop-os
📅 Data e hora:       domingo, 16 junho 2025 - 21:08:45
📡 IP Local:          192.168.15.42
🔋 Bateria:           Discharging, 76%, 02:10:00 remaining
🌡️ Temperatura CPU:   52.0°C
💾 Memória usada:     1.4G / 7.7G
🧠 Carga da CPU:      0.21, 0.18, 0.19
