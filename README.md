# EyeLoop Playground [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/simonarvin/eyeloop_playground/issues) ![lab](https://img.shields.io/badge/yonehara-lab-blue) 

<p align="center">
<img src="https://github.com/simonarvin/eyeloop_playground/blob/master/misc/logo.svg?raw=true">
</p>

*EyeLoop Playground* is a supplementary test space for [EyeLoop](https://github.com/simonarvin/eyeloop), a Python 3-based eye-tracker tailored specifically to dynamic, closed-loop experiments on consumer-grade hardware.

## Overview ##
- [Contents](#contents)
- [How to](#how-to)
- [Contribute](#contribute)

## Contents ##
- [x] Sample footage (videos)
- [x] Sample data (json)
- [x] Blink calibration files.
- [x] Binarization parameter files.

[Click here](https://github.com/simonarvin/eyeloop_playground/tree/master/examples) to access the data.

## How to ##

### Load blink calibration file ###
To load a blink calibration file, pass it to EyeLoop via command line argument ```--blink```, specifically:
```
eyeloop --blink [path-to-calibration-file]
```

### Load parameter file ###
To load a parameter file, pass it to EyeLoop via command line argument ```--params```, specifically:
```
eyeloop --params [path-to-parameter-file]
```

## Contribute ##
Any eye-tracking footage (preferably raw video material) are welcome.

> Contact Simon Arvin at sarv@dandrite.au.dk to contribute.

**Researchers:**

- Simon Arvin, sarv@dandrite.au.dk
- Rune Rasmussen, runerasmussen@biomed.au.dk
- Keisuke Yonehara, keisuke.yonehara@dandrite.au.dk

---
<p align="center">
    <img src="https://github.com/simonarvin/eyeloop/blob/master/misc/imgs/aarhusuniversity.svg?raw=true" align="center" height="40">&nbsp;&nbsp;&nbsp;&nbsp;
    <img src="https://github.com/simonarvin/eyeloop/blob/master/misc/imgs/dandrite.svg?raw=true" align="center" height="40">&nbsp;&nbsp;&nbsp;&nbsp;
    <img src="https://github.com/simonarvin/eyeloop/blob/master/misc/imgs/nordicembl.svg?raw=true" align="center" height="40">
</p>
<p align="center">
    <a href="http://www.yoneharalab.com">
    <img src="https://github.com/simonarvin/eyeloop/blob/master/misc/imgs/yoneharalab.svg?raw=true" align="center" height="18">&nbsp;&nbsp;&nbsp;&nbsp;
    </a>
    </p>
