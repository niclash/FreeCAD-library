## Overview

This is a library of cylinders for making non-threaded (clearance) bolt holes. In use, one would add the appropriate cylinder, position and scale it relative to the part requiring the bolt hole, then use the Boolean difference operation to remove the cylinder from the base part, producing a Cut of the proper form.

Both metric and Unified (U.S.) cylinders are provided. Each cylinder is available in three fit classes (loose, normal, and close), and each fit class is available in minimum, mean, and maximum radii. Which one you use will vary depending on your application and the nature of your material and production process -- for example, if you're 3D printing with a material that swells somewhat after deposition, the "close" "min" cylinder might be too tight.

The default height (Z axis) of the cylinders is 15 mm, but obviously the cylinder can (and should) be lengthened or shortened, translated, rotated, etc. to provide the correct penetration of the part from which it will be subtracted.

## Nomenclature

Metric cylinders use the standard MX names (for example, a minimum close fit for an M5 bolt would be named M5CloseMin.FCStd). 

Unified size names can contain characters that may be troublesome in some file systems, so the following convention is adopted:

Unified sizes are prefixed with U_, followed by the size, followed by the fit class and tolerance (just as with metric).

"#" in a size name is replaced with "Number" (just as it is commonly pronounced in this context), and followed by an underscore. For example, the #6 loose fit maximum cylinder is named U_Number_6LooseMax.FCStd.

Fractional sizes have the "/"" character replaced with "s", and any spaces replaced with underscores. For example, the 1 3/8" loose fit minimum cylinder is named U_1_3s8LooseMin.FCStd.

## License

These files are made available under a license identical to that of FreeCAD itself (any past, current, or future version, at your option). See the FreeCAD license for details.

## No Warranty

These files are provided "as is", without warranty of any kind. There are no express or implied warranties. There are no warranties of merchantability or fitness for a particular purpose. Please report errors and omissions to pulpgrinder@protonmail.com.

## Credits

The FreeCAD files were generated by Anthony W. Hursh from the following data sources:

https://amesweb.info/Screws/Clearance-Hole-Chart.aspx
https://amesweb.info/Screws/Metric-Clearance-Hole-Chart.aspx

These, in turn, reference:

Oberg, E., Jones, F.D., Horton H.L., Ryffel H.H., (2016). Machinery's Handbook. 30th edition. Industrial Press Inc.
Oberg, E., Jones ,F.D., Horton H.L., Ryffel H.H., (2012). Machinery's Handbook. 29th edition. Industrial Press Inc.
ASME B18.2.8-1999, Clearance holes for bolts, screws and studs



  