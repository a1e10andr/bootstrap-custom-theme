# bootstrap-custom-theme
Create bootstrap theme using 5 colors: brand, light-accent, light-shades, dark-shades, dark-accent
The colors can be generated using http://colormind.io/bootstrap/ web service

# Update color variables
The Initial colors must be set in the assets/scss/_variables.scss like:

* $light-shades : #F7F7F5;
* $light-accent : #ABAA86;
* $brand-color  : #5285BC;
* $dark-accent  : #45A5BB;
* $dark-shades  : #21334A;

All other colors will be calculated according to the brand color
