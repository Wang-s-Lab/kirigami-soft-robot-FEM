1) This the FEM simulation procedure for"Untethered Kirigami Soft Robots with Programmable Locomotion"Applied Physics Reviews(2023).
2) The file inlcues the kirisoro.inp and uMag.for.
3) The smaple program demonstrates the deformation of a single-module kirigami soft robot with Y-axis symmetric magnetization pattern and applied Y-axis magnetic field with a magnitude of 15 mT.
4) The input file describes the modeling precress and defines the user-defined element.
5) The input file should be implemented with the UEL subroutine uMag.for developed by Zhao et al. Please refer to papers "Printing ferromagnetic domains for untethered fast-transforming soft materials, Nature(2018)" and "Mechanics of hard-magnetic soft materials, JMPS(2019)".
6) To run the ABAQUS/Standard code type in the terminal "abaqus job=<jobname> input=kirisoro.inp user=uMag.for interactive".
