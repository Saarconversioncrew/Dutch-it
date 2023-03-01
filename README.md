get module, including fields, created in Design manager:

cd modules 
hs fetch --overwrite /cms-quotes-theme-dutch-it/modules/minimal_top_total.module/ minimal_top_total.module/

automatically update files to HubSpot:

cd . 
hs watch --remove cms-quotes-theme-dutch-it \cms-quotes-theme-dutch-it
