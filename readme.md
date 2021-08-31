# Magnolia with Scala 3 and Magnolia 1.0.0-M5 
At Optrak we've got about 10 different Magnolia sub-projects running on scala 2, with codecs for xml, csv, xls, json (yeah we did our own for various reasons), 
sql (ddl and querying) and typesafe config.

So since Jon Pretty created the original magnolia (as a macro-based faster alternative to shapeless) it's more recently been taken over and maintained by softwaremill.
This is great, but the version is currently on M5 so possibly not final and not yet documented properly. So as I work through our scala 3 upgrade I thought I might as well
take one of these as an example and blog it, hopefully helping others along the way.

Watch this space!
