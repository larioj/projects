# Keyboard Changer
The goal of the program is to make something difficult
easier by dividing up the task of adjusting to a new keyboard layout,
into smaller tasks that are easier to accomplish. Instead of adjusting
to a keyboard wide change, the program makes it so that changes
are gradually performed, so that the user need only adjust to a
couple of keys changing. Once the user has become comfortable
with the changes, more changes are made. This process repeats
until the final layout is the one desired.

## User Problem
I would like to switch to programmer's dvorak but it is
difficult to learn since I am very used to this keyboard.

## Our Solution
Change gradually. Build a program that schedules changes of
the keyboard layout so that it gradually changes a minimum
set of keys at a time.

## Mac Implementation
Mac has files that define the keyboard layout. The easiest
way to implement the changer is to gradually morph the current
file to the new file.

## Considerations
*What would be the most effective policy? What does effective mean?*

### Definitions
Effectiveness can be judged by two things: ease of change and
speed to goal. Ease of change is defined as the perceived difficulty
of adjusting to the key changes. While speed to goal is defined
as how long it will take to adjust to new layout, and ultimately
the final layout. Adjusting to a layout implies being comfortable
and proficient.

### Heuristics
The speed to goal of a particular key is proportional to
its use frequency.

The ease of change of a particular key is inversely proportional
to its use frequency.

### Challenges
There are some challenges associated with this.
The first has to do with policy: Does it matter if we change
widely used keys first, last, or randomly? Changing widely used
keys first would would decrease the ease of change, but increase the
speed to goal, since users would be forced to adjust quicker.

Also how do we deal with infrequently used keys? It would take longer
to get used to changes on these keys, since they aren't used as
much. On the other hand they aren't that important and thus wouldn't
matter much.

The last issue has to do with the reality of the
layout changes. In the best scenario each key will just
be swapped with one other key. This means that changes can be
made pairwise, and the world is rosy. In reality this isn't
the case. At worst in order to change one key to its final
spot, all other keys must also be changed. In order to cope
with this, the program must change some keys to an intermediate
state. However having too many intermediate states is undesirable
since it decreased both the speed to goal and ease of change.

## Algorithm
