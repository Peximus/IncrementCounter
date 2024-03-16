# IncrementCounter

An custom GUI IncrementCounter for JUCE Framework
Try Demo.

add
#include "IncrementCounter.h"

add a member variable

IncrementCounter increment;

add to Constructor

// number of digits 1-3
// inital value

 increment.setup(3, 12);

 addAndMakeVisible(increment);

 set bounts in resized()

 increment.setBounds(16, 0, 48, 96);
