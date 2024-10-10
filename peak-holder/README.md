# peak-holder
---

This was intended to be a peak holding circuit with integrated, configurable reset logic.
It works to an extent but has several flaws as is:
- The peak hold works, but only with input pulses above threshold (some hundred or so millivolt)
- The reset logic is a bit finnicky; the internal delays for processing the logic signals is not quite calibrated and could use some work.
