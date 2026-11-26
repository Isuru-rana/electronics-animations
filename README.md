# Electronics Animations

Interactive browser animations for teaching basic electronics. Single HTML files, no install, work offline.

Live: https://isuru-rana.github.io/electronics-animations/

| File | What it shows |
|---|---|
| `semiconductor-sim.html` | Conductor vs insulator, silicon, doping, PN junction, forward and reverse bias (6 scenes) |
| `fullwave-ct-sim.html` | Centre tap full wave rectifier: current path per half cycle, input and output graphs, open D2 fault |
| `bridge-sim.html` | Bridge rectifier: diode pairs per half cycle, input and output graphs, open D3 fault |
| `transistor-tap-sim.html` | NPN transistor next to a water tap: cut-off, active, saturation |
| `zener-regulator-sim.html` | Zener regulator: V_in sweep, loads, current split, Zener reverse characteristic with live operating point, worksheet table; backwards and burn-out faults |
| `amp-stages-sim.html` | Amplifier stages: mic straight to a power amp, power amp turned up, pre-amp first; level diagram, signal and noise |
| `opamp-sim.html` | Op-amp: open and closed loop, inverting, non inverting, gain control, noise cancelling headphones, differential amplifier |
| `diode-meter-sim.html` | Diode knee voltage circuit; how a voltmeter reads the difference between red and COM |

## Controls

**Semiconductor sim:** Right / Space: next scene. Left: back. 1 to 6: jump. P: pause. F: fullscreen. R: reset.

**Diode meter sim:** Left / Right: pot. R: record point. C: voltage colours. F: fullscreen. Drag any probe tip to a node dot.

**Full wave and bridge sims:** Space: pause. Right: step. F: fullscreen. Speed slider slows or speeds the 50 Hz cycle.

**Zener sim:** Left / Right: V_in (Shift: 1 V steps). 1, 2, 3: no load, 1 kΩ, 470 Ω. R: record. S: sweep. F: fullscreen. "R_S 22 Ω" overheats and burns the Zener; "Replace Zener" resets it.

**Amplifier stages sim:** 1 to 3: modes. Space: pause. F: fullscreen.

**Op-amp sim:** 1 to 6: scenes. Space: pause. F: fullscreen. Scene 4: drag the knob to change the gain.

**Transistor tap sim:** Left / Right: base voltage. 1, 2, 3: cut-off, active, saturation. F: fullscreen.

## Offline use

Download the repo (Code > Download ZIP) and open any `.html` file in a browser.
