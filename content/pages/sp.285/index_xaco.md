---
content_type: page
parent_title: SP.285
parent_uid: 3ac1aa36-8b07-38f8-f202-a90f68c5443e
title: Master/Slave IR Control
uid: 59180ea3-56a1-8194-eb69-1117c8fae4ea
---

[SP.285]({{< baseurl >}}/pages/sp.285)

Chad Keever, [Projectile Launcher]({{< baseurl >}}/pages/sp.285/keever_index)  
Kendall McConnel, [Control of a Plotter]({{< baseurl >}}/pages/sp.285/index_kendallm)  
Jonah Elgart, [Guidance by IR Beacon]({{< baseurl >}}/pages/sp.285/index_bologna)  
Miki Havlickova, [IR Remote Control]({{< baseurl >}}/pages/sp.285/index_mikihavl)  
Jessica Bowles-Martinez, [Guidance by Light]({{< baseurl >}}/pages/sp.285/index_jnbm)  
Matt Seegmiller, Master/Slave IR Control  
Jitin Asnaani, [Invertible Robot]({{< baseurl >}}/pages/sp.285/index_jitin)

* * *

**Matt's IR Controlled Tank**

|  {{< br >}}{{< br >}} ![side.jpg]({{< resource_file 21b3b479-653d-272b-6e45-bc968e7b8438 >}}) {{< br >}}{{< br >}} This is a side view of the tank. {{< br >}}{{< br >}}  | For my final project in [SP.285]({{< baseurl >}}/pages/sp.285), I built an infrared controlled tank out of Legos. The basic idea is that one board acts as a slave and takes commands from another board, which acts as master, through IR signals. These signals are sent in 32 bit bursts along some carrier frequency from the master board to the slave board. |
|  {{< br >}}{{< br >}} ![bottom.jpg]({{< resource_file 23aa6334-f495-cc1f-3afb-482c2892b653 >}}) {{< br >}}{{< br >}} The differentials of the tank as seen from below. {{< br >}}{{< br >}}  | This tank is driven by two motors, one to control forward and reverse motion and the other to control turning. This is accomplished by connecting two differentials so that on one side, the outputs go in the same direction and on the other they go in opposite directions. This is a little hard to understand, unless you know something about differentials already. To help illustrate what is meant by this, there is a picture of the two differentials on my tank below. |
|  {{< br >}}{{< br >}} ![remote_1.jpg]({{< resource_file 99b14c3d-e3e7-4259-3eb2-e1d92bd12760 >}}) {{< br >}}{{< br >}} This is the remote. {{< br >}}{{< br >}}  | The other component of this project is the remote. It is basically an old remote from an RC car that has been taken apart and wired so that its sensors can be plugged into a board. The program that runs on this board checks the values of the sensors corresponding to the forward/backward and side-to-side motors. Based on these values, it sends signals to the board on the tank instructing it as to how fast to drive the motors at.