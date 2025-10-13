# elegoo_neptune_4_plus
This is my config for elegoo neptune 4 plus printer

# Changelog
**13-10-2025**
- Increase idle timeout
- Change idle timeout logic: don't change bed temperature while timeout
- Change probe matrix from 6x6 to 7x7
- Increase probe sample counts from 2 to 3
- remove hard-coded input shaper (EI). Printed will use recommended shaper (usually ZV for X and MZV for Y)