# eeg-signal-prototype
Build log of a basic EEG signal acquisition prototype. Raw signals first, refinement later.I’m building a basic EEG signal acquisition setup. I’ve reached the stage where I’m getting raw/noisy signals and plotting them.  Repo + images here: [GitHub link]  Looking for feedback on signal quality / next steps.

## Current status (Jan 27)

- Checked AMS1117 and ESP32 for power-Working.
- All AVDD pins tied together using a perfboard.
- All AVSS pins tied together (common analog ground)
- Stopping here to add VCAP decoupling and reference caps next

Approach: slow, staged hardware bring-up before any SPI or signal work.
