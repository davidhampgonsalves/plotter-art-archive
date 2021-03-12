# Plotter "Art" Archive
Archive of various things I've made / printed with my plotter(https://github.com/bdring/midTbot_esp32).

## Typical processing
```
source ~/repos/vpype_venv/bin/activate
vpype read input.svg linemerge -t 0.5mm filter -m 0.5mm linesimplify linesort scaleto 440mm 210mm write --page-size 440x210mm --center out.svg

juicy-gcode out.svg -f juicy-gcode.config > out.gcode
```
