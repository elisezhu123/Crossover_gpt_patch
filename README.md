# Crossover_gpt_patch
add game porting tools 1.02beta patch into crossover 

 Extract the zip package of "metal-framework" and place them in the following directory:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib
Copy the "libmotenvk" and replace them with the following file:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib64/libMoltenVK.dylib
 Copy the "x86_64-unix" and "x86-64_windows" replace them with the following file:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib/wine
 Copy the "wine64 preloader" and replace them with the following directory:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/CrossOver-Hosted Application/wine64-preloader
Make sure to follow these steps carefully to ensure that the files are extracted and replaced in the correct directories.
