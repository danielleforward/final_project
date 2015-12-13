#### Balance Scale Debug Log

11/24


- Behavior expected: Calibration of scale would be .5 volts to 5 volts
- Observed behavior: Incorrect voltage displayed on multimeter
- Hypothesis for mismatch: Something wrong with batteries
- Test hypothesis: Checked batteries
- Result: We were missing a battery! D'oh.

- Behavior expected: Calibration of scale would be .5 volts to 5 volts
- Observed behavior: Incorrect voltage displayed on multimeter
- Hypothesis for mismatch: Something wrong with multimeter
- Test hypothesis: Checked schematic
- Result: I was supplying the incorrect supply voltage, I was at 5 volts and the circuit needed 9! Worked after applying 9 volts


- Behavior expected: Calibration of scale would be .5 volts to 5 volts
- Observed behavior: Incorrect voltage displayed on multimeter
- Hypothesis for mismatch: Checked schematic, I used wrong supply voltage given, I used 5 volts instead of 9 volts shown in schematic
- Test hypothesis: Used 9 volts for scale circuit
- Result: Scale came out to mostly correct voltage, 0.617 to 5 volts!
- 

12/2

- Behavior expected: Calibration of scale would be .5 volts to 5 volts
- Observed behavior: Incorrect voltage displayed
- Hypothesis for mismatch: Weak connection of scale wires to breadboard (wires too tiny)
- Test hypothesis: Used terminal blocks to connect scale wires to breadboard
- Result: Voltage still not reacting

- Behavior expected: Calibration of scale would be .5 volts to 5 volts
- Observed behavior: Incorrect voltage displayed on multim7er
- Hypothesis for mismatch: Checked voltage of batteries (someone must have used them?)
- Test hypothesis: Switched out the batteries for good ones, checked on multimeter
- Result: Scale working again at correct voltage!

12/7

- Behavior expected: Scale would show 0.00 in serial monitor with no weight on it
- Observed behavior: Scale shows weight on it even though nothing's on it
- Hypothesis for mismatch: Incorrect calibration
- Test hypothesis: Recalibrated scale
- Result: Scale calibration altered, but still not quite exact

- Behavior expected: Scale would show 0.00 in serial monitor with no weight on it
- Observed behavior: Scale shows weight on it even though nothing's on it
- Hypothesis for mismatch: Something's wrong with the weighing platform
- Test hypothesis: Checked weighing platform with fingertip, when tilted it reaches 0.00, has natural slant due to construction that makes the load cell think it has 1.1 grams on it
- Result: Scale is naturally off due to platform defect in manufacturing

- Behavior expected: Scale would show correct output of fiber and sugar for strawberries
- Observed behavior: Scale shows 0.00
- Hypothesis for mismatch: Something's wrong with the fiber/sugar code
- Test hypothesis: Checked code equation to calculate fiber/sugar in serial monitor, it turned out I was using an 'int' when my input and output was a float. Changed variables to floats.
- Result: The equation works!


- Behavior expected: Scale would show correct output of fiber and sugar for strawberries
- Observed behavior: Scale shows higher output than expected
- Hypothesis for mismatch: Something's wrong with the fiber/sugar code
- Test hypothesis: Checked code variables, numbers I had input before were far too high, I'd forgotten to divide per gram. I input the correct fiber/sugar per gram.
- Result: The equation is accurate!


