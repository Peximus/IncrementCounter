# IncrementCounter

An custom GUI IncrementCounter for JUCE Framework
Try Demo.

Use Projucer to add the .PNG files, as a Binary Resource

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

 to retrieve
 
 int inc = increment.getinc();

Greet me at pingsocket@gmail.com
