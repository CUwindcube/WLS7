This readme gives a brief description of the codes stored in the cuwindcube/WLS7 github repository.

MULTIPURPOSE CODES:<br>

      load_WLS7: takes STA or converted RTD files in a directory and converts them to a .mat file for use in other codes

      importFile/importDir: convert the windcube files to matlab variables


EXAMPLE CODES:<br>

      LUMEX_calc: calculates TKE, I, shear, etc. for the LUMEX campaign using output from load_WLS7
  
      LUMEX_intercomparison: reads in data and plots wind speed & direction for 2 or more windcube systems
  
      LUMEX_daily_pcolor: creates daily raster plots of WC variables for quick analysis
