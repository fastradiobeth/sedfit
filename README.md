# sedfit
Bits o' code for an exciting variety of far infrared spectral energy distribution fitting methods
Comes with code for wonderful activities, such as...

## ... smoothing to a common resolution!
Ever wish /all/ of your Hi-GAL data was at 500micron resolution? 

## ... trying to remove the Milky Way!*
Adapted code for removing diffuse Galactic background using a rather modified version of Astropy affiliated higal-sedfitter.
PLUS code for smoothing and removing background by iteratively fitting vertical Gaussians in Galactic latitude.
[* def 'trying': thresholding method based on pixel flux distribution is currently incorrect]

## ... sedfitting!
Code for fitting compact sources of known size and integrated flux is in: (used for CuTEx extractions from Hi-GAL for maser counterparts) 
Has now been extended to run pixel-by-pixel SED fits.
Lots of greybody functions are living in "greybody.py"

