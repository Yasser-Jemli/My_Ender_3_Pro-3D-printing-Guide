# My_Ender_3_Pro & 3D printing Guide

so this a repository that will reduce your time and your efforts in order to make 3D modeles came to Life 
in this Repository i will help you make your 3D printing more Effective and share some problems that i have 
i will share here all the problem that i face ,, how i figure it out and how you sould work with your 3D printer the Ender-3-pro 

https://user-images.githubusercontent.com/92098387/174289375-d6a9af0a-9206-4e45-8190-49c29b157bed.mp4


![impresora_creality3d_ender_3_pro_001_l](https://user-images.githubusercontent.com/92098387/174154033-aa8afdad-d58f-4c1d-b97c-4457a4dc9f65.jpg)

![3d](https://user-images.githubusercontent.com/92098387/174154051-cd27ecc0-6ab9-470f-9e42-712e59261171.jpg)



# General introduction 

https://user-images.githubusercontent.com/92098387/174294693-611de60c-07ed-428f-bda5-bfd42ed3401e.mp4

3D printing is a so-called additive manufacturing technique which proceeds by adding material, unlike techniques proceeding by removing material,
such as machining. 3D printing makes it possible to produce everyday objects, spare parts or even prototypes intended for testing. 
The starting point is a computer file representing the object in three dimensions, broken down into slices. 
This information is sent to a 3D printer which will carry out the manufacturing by adding successive layers.

# 3D Printer History

It was on July 16, 1984 that the first patent on 3D printing (known as “additive manufacturing”) was issued.
deposit. The agents are French: Jean-Claude André, Olivier de Witte, and Alain le
Méhaute on behalf of CILAS ALCATEL. The same year, in the United States,
on August 1, 1984, the American Chuck Hull filed the patent on the technique
stereolithography 3D printing (SLA for StereoLithography Apparatus) 

# Steps for 3D Printing

![image](https://user-images.githubusercontent.com/92098387/174151881-1df5ab15-83a4-4ac8-a19c-f8b8d7cfe973.png)

# Modeling and file export

The first step in 3d printing is to model a 3d object and export it to one of the
Stl specific files. obs. or amf. For this we must choose one of the many software
computer-aided design (CAD), such as SolidWorks, Catia, Autodesk Fusion
360...

# Slice the 3D object

After having a finished 3D model, you must then slice the file or cut the file into several
layers using one of the slicing software, Ultimaker Cura for example.
This software not only allows us to slice the 3d object but it must generate the g code as well
than controlling the different parameters of the machine.
G code is a machine tool command language that includes instructions for
piloting , is the language known by the majority of CNC machines.

# The impression

Once the g code is ready, you can print by sending the g code to the printer
usually by an SD card, a connection cable to the computer , by internet through
a local network or by OCTOPRINT for anywhere in the World . 

# Material deposition (FDM)

FDM (Fused Deposition Modeling) or molten filament deposition. This is the type of printers
3D most common among individuals , This technique is the one  that we're focusing on because this technique is used for Our Ender-3-pro. 
This technique consists in depositing layer by layer
a filament of thermoplastic material melted on average at 200°C. Thus, by superimposing
layers which can have different contours and therefore by accumulation of material, we end up
to get the desired object. The print head moves in the three directions of space
identified by the three coordinates X, Y and Z (length, width and height). These coordinates
are transmitted from the computer by a 3D file which corresponds to the 3D model of the object to be
to print. ==> this is the technique for the Ender-3-pro

![fdm-printing](https://user-images.githubusercontent.com/92098387/174153837-7c2286a7-cf8f-40a3-bc2c-c76957e41e3a.jpg)

the other techniques, I will talk about the theme a little bit  here and you will find them in the future in other repositories

# Stereolithography (SLA)

This is the first 3D printing technology, which appeared in 1986. In this case the point of
nozzle is an ultraviolet laser and a tray of liquid photopolymer. As the deposit system of
filament, this process prints layer by layer. The laser strikes the liquid which solidifies under
the effect of ultraviolet light. A plate immersed in the tank supports the material thus solidified and
descends, as for the FDM, to pass from one layer to the next.
Once the printing is finished, the object must be rinsed to get rid of the remains of
photopolymer with a solvent. The object is then put in the oven to solidify it. A
constraint which is added to the relative slowness of the process.
The usable materials remain quite few and despite the great precision offered by
ALS, this technique delivers relatively fragile objects. It is therefore limited to
prototyping rather than the production of objects.


![schema-impression-3D-SLA-A3DM-Magazine](https://user-images.githubusercontent.com/92098387/174293813-c1884f08-ebf8-44f9-83af-d5af3b4d7052.jpg)

# The DLP process

DLP (Digital Light Processing) developed for work requiring high precision,
such as jewelry or the manufacture of prostheses, the DLP process is based on the same
technology than that which is embedded in many video projectors.
The principle is similar to ALS, in that light is used to solidify a
liquid polymer. A chip made up of a matrix of orientable mirrors, sometimes several
million reflects a UV light and projects a kind of image corresponding to the shape of the
layer to be printed. This light therefore strikes the polymer which is in a tank to
solidify it. The processing is done layer by layer, as in the case of SLA

![DLP-Process](https://user-images.githubusercontent.com/92098387/174294054-8df257e4-c01d-4daf-9166-0d0befaccd29.png)



# First - adding OCTOPI 

will this is a great tool to have , so let's say you want to print something and you wanna to recored a video for the printing operation 
or you wnat just to launch a printing without going  next to your printer or you have some concern about your printing process and you want to supervised 
from another place , well OCTOPI make it easy to you 
