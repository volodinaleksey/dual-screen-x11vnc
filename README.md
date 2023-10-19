# dual-screen-x11vnc

x11vnc -bg -loop -forever -shared -repeat -noxdamage -xrandr -display :0 -rfbport 5900 -clip xinerama0

x11vnc -bg -loop -forever -shared -repeat -noxdamage -xrandr -display :0 -rfbport 5901 -clip xinerama1
