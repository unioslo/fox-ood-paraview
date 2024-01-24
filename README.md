# Fox Desktop for Open OnDemand

ParaView app for Open Ondemand, as used on the Fox HPC cluster at University of Oslo.
Supports GPU via VirtualGL

## Notes:

<<<<<<< HEAD
This is a fork of the Fox Desktop app, found here:
https://github.com/unioslo/fox-ood-desktop
=======
### Apptainer image

We build an apptainer sif file based on Rocky 9 with Xfce, VirtualGL and the packages required from OOD.
An example definition file can be found here: https://github.com/buzh/fox-vgl-desktop

### ec_alacarte in form.yml

To avoid duplicate code in every app, we create a class containing the resource selection details in an initializer. This is rendered into the yaml via ERB.

### Running apps automatically

To add specific desktop apps like MATLAB, RStudio, ParaView and so on we use this app with a few modifications. See the forks of this repo to view them.
>>>>>>> upstream/main

## Authors:

Based on the Ohio Supercomputing Center reference desktop implementation.

UiO/Fox implementation and VirtualGL support added by Andreas Skau <buzh@uio.no> @buzh


