# BBS 1 Mainz BSFI24D Projekt

## Simon Says Raspi Edition
Wir haben uns dazu entschieden ein Spiel zu programmieren was Simon Says nachempfunden ist. Das Programm ist simpel mit Python programmiert. Die Knöpfe und die LED's werden in der `config.py` Konfiguriert.

### Installation

```bash
git clone https://github.com/kruemmel2704/SimonSays1.git
cd SimonSays
```

#### Programm automatisiert starten
Damit das Programm im Hintergrund läuft muss `screen` installiert sein.

```bash
sudo apt update && sudo apt install screen -y
```

danach mit `cronjob` bei neustart das Programm ausführen lassen

```bash
@reboot -dmS SimonSays python /dein/pfad/SimonSays.py
```

dann einmal mit `sudo reboot` neustarten

### Konfiguration


