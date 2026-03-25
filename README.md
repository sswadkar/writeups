# Writeups

This repository collects short technical writeups and their source files. The intent is to keep the authored material in version control while avoiding generated LaTeX artifacts, so the repo mostly contains PDFs, images, and `.tex` source.

## Current Writeups

### Voltage vs Current Control

Files: [`voltage_vs_current_control/voltage_vs_current_control.pdf`](./voltage_vs_current_control/voltage_vs_current_control.pdf), [`voltage_vs_current_control/voltage_vs_current_control.tex`](./voltage_vs_current_control/voltage_vs_current_control.tex)

This writeup explains why current control is usually a better abstraction than raw voltage control when you want predictable motor torque. It starts from the motor equation, shows how back-EMF changes the amount of current a fixed voltage can actually produce, and contrasts the two important operating cases: stall and motion. The core argument is that because torque is proportional to current, current control gives a more direct and bounded way to command mechanism effort, especially for something like an intake that may alternate between moving freely and getting stuck.
