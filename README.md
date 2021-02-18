# Track GPS Satellites

There are currently 30 satellites in the GPS constellation contained in 6 orbital planes. Each GPS satellite orbits twice per 24 hour day around the earth. The goal of the GPS constellation is to make sure that at least 4 GPS satellites are covering every point on the earth at any one time. There also exist much space debris (for various reasons) orbiting the earth. For example, a large pattern of space debris was created in 2007 when the Chinese intentionally destroyed its own satellite. The locations of satellites and space debris are mostly public information. This project proposes to monitor GPS satellite locations and their positions in space relative to space debris, including the Chinese anti-satellite missile test debris. The goal of this project is to determine how close space debris might come to our essential GPS fleet.

The GPS satellite data is presented in CSV format by the URL<br>
"https://celestrak.com/NORAD/elements/gp.php?GROUP=GPS-OPS&FORMAT=CSV"<br>
It can be copied and pasted into an empty .csv file. Similarly, the Chinese debris is available at<br>
"https://celestrak.com/NORAD/elements/gp.php?CATNR=25544&FORMAT=CSV"<br>
