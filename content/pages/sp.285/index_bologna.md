---
content_type: page
parent_title: SP.285
parent_uid: 3ac1aa36-8b07-38f8-f202-a90f68c5443e
title: Guidance by IR Beacon
uid: 71bf2a2a-5a80-abb9-6b63-accb8c525add
---

[SP.285]({{< baseurl >}}/pages/sp.285)

Chad Keever, [Projectile Launcher]({{< baseurl >}}/pages/sp.285/keever_index)  
Kendall McConnel, [Control of a Plotter]({{< baseurl >}}/pages/sp.285/index_kendallm)  
Jonah Elgart, Guidance by IR Beacon  
Miki Havlickova, [IR Remote Control]({{< baseurl >}}/pages/sp.285/index_mikihavl)  
Jessica Bowles-Martinez, [Guidance by Light]({{< baseurl >}}/pages/sp.285/index_jnbm)  
Matt Seegmiller, [Master/Slave IR Control]({{< baseurl >}}/pages/sp.285/index_xaco)  
Jitin Asnaani, [Invertible Robot]({{< baseurl >}}/pages/sp.285/index_jitin)

* * *

Hi, I'm Jonah Elgart and for my final project in [SP.285]({{< baseurl >}}/pages/sp.285), a robotics and mechatronics class taught in [ESG](http://esg.mit.edu/) (Experimental Study Group), I created a Lego robot that chases or flees an infrared beacon.

My robot car is very simple. It has two wheels, each connected to its own motor. The two motors are driven at different speeds to steer the car. The back wheel is mounted on a really cool caster that I built with Eric (one of the instructor dudes).

|  {{< br >}}{{< br >}} ![Student Lego Project.]({{< resource_file 509414d7-3f51-a549-2ca7-1d004033ae32 >}}) {{< br >}}{{< br >}} My robot. {{< br >}}{{< br >}}  |  {{< br >}}{{< br >}} ![Student Lego Project.]({{< resource_file eeb16f95-2249-7425-247a-4c719c3e8e01 >}}) {{< br >}}{{< br >}} The car. {{< br >}}{{< br >}}  |  {{< br >}}{{< br >}} ![Student Lego Project.]({{< resource_file 6486d339-3749-f245-1fac-559c8233334d >}}) {{< br >}}{{< br >}} The car's rear side. {{< br >}}{{< br >}}  

|  {{< br >}}{{< br >}} ![Student Lego Project.]({{< resource_file ea38ec08-f85f-9d7f-fe75-47077661707c >}}) {{< br >}}{{< br >}} Infrared transmitter. {{< br >}}{{< br >}}  | An infrared signal is broadcasted from a transmitter hooked up to a handyboard (one of those circuity things which is a minicomputer). |
|  {{< br >}}{{< br >}} ![Student Lego Project.]({{< resource_file 131a2a83-629e-8edb-0af8-719b986fdfac >}}) {{< br >}}{{< br >}} Infrared receiver. {{< br >}}{{< br >}}  | The signal is detected by the tower, which consists of three directional infrared receiver doohickeys, oriented in three quadrants. 

Click "code" ([C](./resolveuid/a5282be50ae5c190eb88b1d978c7bf9d)) to see the IC code I wrote to make the robot flee or chase the signal. To change from flee to chase you simply reverse the polarity of the motors.