

![VeraGrid_banner.png](pics/VeraGrid_banner.png)

# Dynamic simulations and Small-Signal analysis tutorial

Here you will find all the information and related files for the hands-on tutorial on Dynamic Simulations using VeraGrid, our open-source Software.

In this tutorial we will learn how to use VeraGrid to perform dynamic simulations (RMS and EMT) and Small-Signal stability analysis.
- [Practical session](./RMS_HVDC_practical_session.md)

Complete documentation: [here](https://veragrid.readthedocs.io/en/latest/)

---

## How to Run VeraGrid

### Option A — Run VeraGrid on *your machine*

**Requirements**

* [Download Python](https://www.python.org/downloads/) 3.10-3.14 (3.14 recomended)
* Alternativelly, get a python distribution + all packages installed from [eroots.tech/software](https://www.eroots.tech/veragrid-download)

**Software installation**

```shell
pip3 install veragrid
```

**Execution with user interface**

From the terminal run `veragrid` to launch the graphical user interface.

For scripting, run as you normally would.

To launch the user interface from a script:

```python
from VeraGrid.ExecuteVeraGrid import runVeraGrid

runVeraGrid()
```

or in a single line

```bash
python3`` -c "from VeraGrid.ExecuteVeraGrid import runVeraGrid;runVeraGrid()"
```

---

### Option B — Run VeraGrid in your *browser* (no installs)

On the workshop day we’ll provide:

* a link like `https://35.233.62.237.sslip.io/seat1/`
* a seat number

**Steps**
1. Open the link we provide (e.g., `https://<WORKSHOP URL>/seatX/`) in Chrome/Firefox, doubleclick in the seat number provided in Veragrid Workshop Room Selection. Enter your name to register.
![noVNC](pics/VMVeragrid.png)

   ```bash
   veragrid
   ```
6. That’s it—VeraGrid will start inside the browser desktop. You can also run your Python scripts as usual from this terminal.

**Notes**

* We’ll share your exact seat at the start of the session.
* If the browser page looks idle/blank, refresh the page. If you need to restart, ask the speakers to reset your room.
* All you need is a modern browser; no local Python install required.
