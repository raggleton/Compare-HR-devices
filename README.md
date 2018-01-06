# Compare HR devices

This is a quick n dirty analysis of HR data taken from 2 different devices: a chest strap (Garmin Soft Strap Premium Heart Rate Monitor), and an optical sensor worn on left wrist (Garmin Forerunner 35).

Data was taken from a ~35 minute indoor bike session, with some 30s intervals thrown in for good measure to raise HR.
The chest strap was wettened beforehand, although I was sweating loads by half time anyway. Data was recorded by Elite Intera indoor trainer.
The optical sensor watch was done up tight enough so no gap between strap and wrist, but without constricting the wrist.

Strap TCX file take directly from myETraining app. Wrist TCX file taken from Garmin Connect site.

## Quick Conclusion

Mostly agrees well, apart from hard, short efforts especially above ~ 150 BPM, where the optical sensor cannot keep up. The large difference at ~ 25 minutes is surprising. This interval was definitely harder than all others, even though the watch reports a lower/similar HR to other intervals.

## Running the notebook

Designed to run in python3. Only needs `pandas` and `matplotlib`, which are both `pip`-installable.
