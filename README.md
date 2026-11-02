# FlowFit

**Know exactly when to go to the gym.**

FlowFit reads a live camera feed of the gym (only counts, no images), shows which machines are free, tells you whether to go now or leave a bit later, and rebuilds your workout around free machines when you can't wait.

- **App:** https://hadrienotero.github.io/flowfit/
- **Camera script:** `flowfit_live.py` (runs on the Mac next to the camera, sends machine status to the app through ntfy.sh)

## The three features
1. **My Machines / Live gym:** live status of every machine, favorites first.
2. **Best Time to Go:** one answer, "Go now" or "Leave at HH:MM", trip time included and adjustable.
3. **Plan B:** reorders tonight's workout around free machines, with same-muscle swaps and exercise locks.

When the camera is offline, the app says so and offers clearly labelled demo data.
