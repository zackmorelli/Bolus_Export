# Bolus_Export

This program is for use with ARIA/Eclipse, which is a commerical radiation treatment planning software suite made by Varian Medical Systems which is used in Radiation Oncology. This is one of several programs which I have made while working in the Radiation Oncology department at Lahey Hospital and Medical Center in Burlington, MA. I have licensed it under GPL V3 so it is open-source and publicly.

There is also a .docx README file in the repo that describes what the program does and how it is organized.

I did NOT make this original program. This was made available to Eclipse users by Varian. I just modified it to export RT plan structures as .stl files so they could be used with 3D Printing software.

This program is capable of exporting 3D Mesh files of structures from an RT plan in Eclipse, as well as dose information. I have modified it to output mesh files as .stl specifically for "BOLUS" structures. I use it to export .stl files that I use to 3D print Bolus for patients. This is done for plans where bolus conformity can be difficult, like nose or ear.

