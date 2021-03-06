tzid-from-geo
=============

Get the timezone ID from latitude, longitude coordinates

Demo at http://tzid.kambli.net/?lng=-71.063611&lat=42.358056. This may go down because it's a free Google App Engine webapp.

I developed this during a few hours long hackathon, which means that it's quickly put together and can be optimized a lot. It has two scripts - construct_data.py and find_timezone.py. They are fairly self-explanatory. Read comments inline. Feel free to fork and use in any way that you see fit. The data was sourced from http://efele.net/maps/tz/world/. And then converted to GeoJSON at http://converter.mygeodata.eu/. Run construct_data.py on the GeoJSON file to generate internal representation of the data. Use find_timezone.py to verify if it works.

If you'd like to say thanks, please consider donating to one or more of my favorite charities - St. Jude Children's Research Hospital (http://www.stjude.org/), American Cancer Society (http://www.cancer.org/), Doctors Without Borders (http://www.doctorswithoutborders.org/), Engineers Without Borders (http://www.ewb-usa.org/) or support my Movember 2012 campaign (http://mobro.co/uddhav). Thanks.