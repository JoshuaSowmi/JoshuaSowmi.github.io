# JoshuaSowmi.github.io


# Multiserver

<!-- badges: start -->
<!-- badges: end -->

The goal of the Multiserver is to show a real-life simulation of bank queuing systems.

# Installation

If you would like to download the development version from Github, run:


  #install.packages("devtools")
  
  devtools::install_github("MQ-STAT1378/assignment2-question2-joshuasowmi")


# Example

Multiserver(bank$arrival_time, bank$service_time, 3)

A tibble: 100 × 4
   Arrivals ServiceBegins ChosenServer ServiceEnds
      <dbl>         <dbl>        <dbl>       <dbl>
 1     119.          119.            1        149.
 2     134.          134.            2        289.
 3     326.          326.            3        356.
 4     339.          339.            1        424.
 5     372.          372.            2        652.
 6     396.          396.            3        474.
 7     400.          424.            1        459.
 8     491.          491.            1        650.
 9     531.          531.            3        762.
10     628.          650.            1        756.
… with 90 more rows


Enjoy!!!
