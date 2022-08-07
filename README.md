# Plotter "Art" Archive
Archive of various things I've made / printed with my plotter(https://github.com/bdring/midTbot_esp32).

## Typical processing
```
vpype read blender-freestyle/arrow-head-outlined.svg linemerge -t 0.25mm filter -m 1mm linesimplify deduplicate reloop linesort -t scaleto 440mm 210mm linemerge -t 0.1mm  write --page-size 440x210mm --center out.svg
```
