# [bash raspi docker monitor](https://github.com/MathiasStadler/bash_raspi_docker_monitor.git)

## motivation
    monitoring the raspi docker host via bash shells

## start lx terminals /w geometry and /w position

```bash
export XDG_DATA_DIRS=/var/lib/flatpak/exports/share:/home/pi/.local/share/flatpak/exports/share
lxterminal --geometry=40x24+10+10 -e echo "HERE"
```