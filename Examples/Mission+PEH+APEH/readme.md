Mission+PEH+APEH Example
=======

Matt Luckcuck <ml881@york.ac.uk> 2014
-----------------------------------

### Features:
	* Mission with Multiple Schedulable Objects
	* Schedulable Object calilng `requestTermination` on its `Mission`
	* An `AperiodicEventHandler` being released by a fellow Schedulable Object
	* Use of `PeriodicEventHandler`
	* Use of `AperiodicEventHandler`

This example program has a single `Mission` that contains a `PeriodicEventHandler` and an `AperiodicEventHandler`. The `PeriodicEventHandler` waits for its start time offset, releases the `AperiodicEventHandler`, then terminates. When released, the `AperiodicEventHandler` calls `requestTermination` on its mission.

