# EDA

# file description.ipynb
this file contains the eda on the files 

# exp.ipynb
now since the data is in form of points , so we make a buffer or dem patch around it .

How to decide the amount of area to be taken as buffer?

As we are using the TanDEM-X DEM — a high-quality global DEM , which is 0.4 arcsec resolution
• 0.4 arcsec, corresponding to 12 m at equator

i,e, 0.4 arcseconds ≈ 12 m × 12 m pixels (depends slightly on latitude)

    That means:

    A 50 m × 50 m patch ≈ 4 × 4 pixels 

    A 100 m × 100 m patch ≈ 8 × 8 pixels

    A 150 m × 150 m patch ≈ 12 × 12 pixels

    A 200 m × 200 m patch ≈ 16 × 16 pixels

    so for persistent homology to work reliably , we can take a 200 m × 200 m patch.

    i have extracted a  50 m × 50 m patch ,  100 m × 100 m patch and a  200 m × 200 m patch.



    
