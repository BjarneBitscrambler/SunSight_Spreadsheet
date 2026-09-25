This spreadsheet aids in calculating a Sun-sight line-of-position (LOP) from a sextant reading. Traditional celestial navigation uses
printed almanacs, tables, and hand calculations to reduce a sextant reading to a distance and direction from an assumed position. The spreadsheet
automates the process, so the user only needs to make the sextant reading, note the time, and input an assumed position.  

The Sun's GHA and Declination, which usually are produced from an almanac together with some hand calculations, are produced in the spreadsheet
using three different methods:
- Using a perpetual table, as shown in the book *Commonsense Celestial Navigation* Hewitt Schlereth, 1975
- Using The Nautical Almanac [https://thenauticalalmanac.com] tables, valid to 2036
- Using the formulae of the US Naval Observatory [https://aa.usno.navy.mil/faq/sun_approx]
The user can instead enter their own values for GHA and Declination, obtained from whichever source they wish

Intermediate steps in the calculations are shown, and tables used are in associated tabs within the spreadsheet, so the user can 
follow along with the process. The output from the calculations gives an Azimuth and Distance from the Assumed Position, from which the LOP can be
plotted.

The spreadsheet is in ODS (OpenDocument Spreadsheet) format, and has been tested using LibreOffice Calc v24.2.7.2.  It should also work fine in OpenOffice,
as well as MS Excel, though it is possible that some of the formulae syntax need to be adjusted for the latter.  Test your setup with known-good
data before relying on it. Always verify positions with an independent second source when possible. Use at your own risk.
