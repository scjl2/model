FlatBuffer example
==================

Matt Luckcuck <ml881@york.ac.uk> 2014
-----------------------------------

### Classes: 6

### Features:
	* One `Mission`
	* Two `ManagedThreads`
	* Uses `Object.wait()` and `Object.notify()`

The Flatbuffer program has one mission and two managed threads, which communicate using a one-place buffer in the mission in the familiar Readers-Writers style. This program uses `Object.wait()` and `Object.notify()`, which is only available at SCJ Level 2. This program only has one tier, hence the name "Flatbuffer".
