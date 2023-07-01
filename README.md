# Crossover23_gpt_patch-
add game porting tools 1.02beta patch into crossover 

It only works with Crossover 23 nightly build, please not use crossover 22.1 to try 

!!!! you need to create a new bottle in crossover23 first after you patch it, you can no longer create bottle. 
1. Extract the zip package of "dxvk_metal" and replace them with the following directory:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib64/wine/dxvk
2. Extract the zip package  of "dxvk_metal" and replace them with the following directory:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib/wine/dxvk
3. Extract the zip package of "metal-framework" and place them in the following directory:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib
4. Copy the "libmotenvk" and replace them with the following file:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib64/libMoltenVK.dylib
5. Copy the "dxgi" and replace them with the following file:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/lib/wine/x86_64-windows/dxgi.dll
6. Copy the "wine64 preloader" and replace them with the following directory:
/Applications/CrossOver.app/Contents/SharedSupport/CrossOver/CrossOver-Hosted Application/wine64-preloader
Make sure to follow these steps carefully to ensure that the files are extracted and replaced in the correct directories.
