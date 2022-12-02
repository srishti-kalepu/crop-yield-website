# crop-yield-website
## Imports
### Chloropleth
The altair library may not always be installed in the systems. So, I had to run the following code to import the libraries. 
import sys
print(sys.executable)
!{sys.executable} -m pip install altair 
I also needed to download the jupyter_bokeh library which can be done with the following command:
pip install jupyter_bokeh