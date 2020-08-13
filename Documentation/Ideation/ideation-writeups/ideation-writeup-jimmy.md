# Justifications and ideas from the ideation

For use when comparing different ideas and part design

## Initial Twist-Lock idea

**Description**

Like the gearbox project, the twist-lock is the idea that an attachment could be added between the bearing housing and the plate to one main purposes: aligning the plate to the correct orientation. This would involve guide rails that would rotate the disk as it moved along a path and have the locking fixture "fall" into place once the disk is in the right orientation. This model can be found in `Model-Stepped.SLDASM`

**Pros**

* Really simple overall design, with a plastic injection-moulded locking mechanism
* Does not require any orientation beforehand, and can essentially guarantee the orientation afterwards

**Cons**

* Janky.
* The locking mechanism may not be secure
* Requires additional complex part to otherwise simple structure
* Would require some unique feeding mechanism to put the lock fixture in the right place



## Geneva Mechanism

A Geneva mechanism would help in converting continuous motion to stepped motion, which would be useful for controlling jig motion.

**Pros**

* Mechanical method of converting continuous motion into stepped motion
* Somewhat continuous, though susceptible to jerk

**Cons**

* Loud!
* There are probably others, but a Google Search will reveal them

## Alignment Towers

The basic idea is to place the disks with a special cut-out in the top and entry of the tower. The spinning tower would eventually align all the disks into a known orientation.

This tower is then used as an input into the system, and acts as a crucial first step for the alignment of the disks.

**Pros**

* High density input
* Guarantees position
* Mechanically super-reliable
* Uses robotic arm

**Cons**

* Requires a robotic arm, or some sort of rotating mechanism to release the disks
* Would require a jig or some special output that retains the position of the disks/plate



## Aligned-Jig

The goal is to have a jig that has insets already designed for the plate. The jig would have the nuts and bolts pre-loaded along with the washers. The plate is then dropped on top, then screwed in. A hole at the bottom would allow for some sort of press to push the plate out.

**Pros**

* Simple enough
* Uses a Geneva drive to push the jig to the right place

**Cons**

* Requires a Geneva drive to push the jig into the right place
* Requires the bolts and washers to be put in beforehand, which is a challenge in itself



