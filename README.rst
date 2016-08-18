Brightness Menulet
==================

Allows you to control monitor brigthness via menu in status bar.

This tool works on OSX 10.8+. In 10.8+, I2C tools are not able to detect monitor buses for communication.
The main API calls for DDC communication is deprecated so this project could be obselete if Apple
completely removes CGDisplayIOServicePort. If you have tested your monitor(s) with this tool, please
let me know wether it worked or not so I can add monitor models here. Preference's Debug button logs to the
console VCP codes and their values on the selected monitor.

Download app build: `Brightness_Menulet.zip`_.

.. _Brightness_Menulet.zip:
    https://raw.github.com/florianbeck/BrightnessMenulet/master/BrightnessMenulet/Brightness_Menulet.zip

.. image:: https://raw.github.com/florianbeck/BrightnessMenulet/master/BrightnessMenulet/screenshot.png

.. image:: https://raw.github.com/florianbeck/BrightnessMenulet/master/BrightnessMenulet/screenshot2.png

Monitors:
.......................
+------------------+---------------+
| Working          | Non-Working   |
+==================+===============+
| Dell U2014h      | Dell P2715Q   |
+------------------+---------------+
| Dell U2414h      | Philips 4065UC|
+------------------+---------------+
| Dell U2415h      | Dell P2412H   |
+------------------+---------------+
| Dell U2515h      | Dell U2412M   |
+------------------+---------------+
| Dell U2715h      |               |
+------------------+---------------+
| Dell U2713HM     |               |
+------------------+---------------+
| Dell P2415Q      |               |
+------------------+---------------+
| Dell S2216M      |               |
+------------------+---------------+
| Samsung SA 350   |               |
+------------------+---------------+
| BenQ G2410HD     |               | 
+------------------+---------------+
| Viseo 230Ws      |               | 
+------------------+---------------+
| Samsung SMT27A300|               | 
+------------------+---------------+

If you have tested your monitor(s) with this tool, please let me know whether or not it work and I will update this table.


Features:
............

- Following the internal Display's Brightness and if activated the automatic brightness (built in light sensor)
- Multi-Monitor support
- Compatible with OSX 10.8+
- Shortcuts for Darker, Brighter and toggle the Follow-Main-Screen option

Roadmap:
........

- Support for other monitor makes (Currently only tested on Dell and certian HP displays)
- Time based settings

Credits:
........

- `Kalvin126`_ & `superduper`_ – `BrightnessMenulet`_ creators
- `Alec Jacobson`_ - first version of `Brightness Menulet app`_
- Jon Taylor - `DDC/CI bindings`_
- Victor Miroshnikov - copy&paste&debug job
- `Joey Korkames`_: EDID Reading

.. _Kalvin126:
    https://github.com/Kalvin126

.. _superduper:
    https://github.com/superduper
    
.. _BrightnessMenulet:
    https://github.com/Kalvin126/BrightnessMenulet

.. _DDC/CI bindings:
    https://github.com/jontaylor/DDC-CI-Tools-for-OS-X

.. _Alec Jacobson:
    http://www.alecjacobson.com/weblog/

.. _Joey Korkames:
    https://github.com/kfix/ddcctl

.. _Brightness Menulet app:
    http://www.alecjacobson.com/weblog/?p=1127
