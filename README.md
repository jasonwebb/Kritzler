 Der Kritzler
==============

 Der Kritzler is a software and hardware platform for developing wall plotters. It consists of a set of Processing sketches (see src/ folder), Arduino firmware (firmware/ folder) and some electronics (some files in the design/ folder). 
 
 src/ 
      Contains Processing/Java sources, ready to use in Eclipse.
      Take a look at http://processing.org/learning/eclipse/
      to see how to set things up.
      
 firmware/
      Contains Arduino firmware for the Kritzler.

 jpg_to_svg_bw.sh
      Script to convert a bitmap into an SVG.
      Needs imagemagick and potrace.
    
 jpg_to_svg.sh
      Starts the processing sketch to make a jittered SVG
      out of a bitmap (JPG).
      
 fill_svg.sh 
      Starts the processing sketch to fill SVG outlines with
      with diagonal lines.
      
 plotter.sh
      Starts the processing sketch that sends SVGs to the Kritzler.

Changelog
=========
+ Real-time pen location tracking added by Jason Webb (5/25/2012)
+ Javadoc comments and consistent formatting added by Jason Webb (5/25/2012)
      
      
