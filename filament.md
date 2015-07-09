A filament, in principal, needs to be little more than a
network-attached hard drive. Practical considerations dictate that the
unit should be:

- compact
- low-power
- quiet
- inexpensive
- performant

The requirement of compact dictates that the motherboard be of an ultra-
small form factor. The Raspberry Pi springs to mind and fulfills the
cost requirement very well, but the lack of a SATA connector obviates 
the fastest means of accessing a HDD. The Pi's USB ports provide an 
alternative for connecting a HDD, but the bandwidth limitations of USB
2.0 introduce a bottleneck for storage acces. 

# Intel NUC

Intel's Next Unit of Computing (NUC) series of ultra-small computers
provides a more featureful alternative to the Pi, but at a higher cost.
At the very least, their cases extol the same aesthetic principals that 
the filament should achieve:

![NUC Cases](https://www-ssl.intel.com//content/dam/www/public/us/en/images/photography-consumer/16x9/rc-family-nuc-frontangle-blue-16x9.png.rendition.intel.web.720.405.png)

As full-featured computers, they appear to meet the technical
requirements of the project as well. The Intel® NUC Board DE3815TYBE,
with an MSRP of $99, is only candidate NUC that satisfies the cost
requirements.

# Obstacles

## Power & Storage
An immediate obstacle is that Intel does not offer any NUC kit with a
3.5" HDD bay, nor do any other vendors. This necessitates manufacturing
a bespoke chassis.

Unfortunately, the issue of a 3.5" bay goes beyond the chassis. The NUC
boards offer only a slimline SATA connector, which carries 5V to a 2.5"
HDD. Standard SATA power connects deliver both 5V and 12V to a 3.5"
drive.

Intel's [technical specifications](http://downloadmirror.intel.com/23745/eng/DE3815TYBE_TechProdSpec08.pdf)
provide useful information regarding the DE3815TYBE's power supply.
