```
      ___          ___          ___          ___          ___                  ___             
     /\__\        /\__\        /\  \        /\__\        /\  \                /\  \            
    /:/ _/_      /:/ _/_       \:\  \      /:/  /       /::\  \       ___    /::\  \   ___     
   /:/ /\  \    /:/ /\__\       \:\  \    /:/  /       /:/\:\__\     /|  |  /:/\:\__\ /\__\    
  /:/ /::\  \  /:/ /:/ _/_  _____\:\  \  /:/  /  ___  /:/ /:/  /    |:|  | /:/ /:/  //:/  /    
 /:/__\/\:\__\/:/_/:/ /\__\/::::::::\__\/:/__/  /\__\/:/_/:/__/___  |:|  |/:/_/:/  //:/__/     
 \:\  \ /:/  /\:\/:/ /:/  /\:\~~\~~\/__/\:\  \ /:/  /\:\/:::::/  /__|:|__|\:\/:/  //::\  \     
  \:\  /:/  /  \::/_/:/  /  \:\  \       \:\  /:/  /  \::/~~/~~~~/::::\  \ \::/__//:/\:\  \    
   \:\/:/  /    \:\/:/  /    \:\  \       \:\/:/  /    \:\~~\    ~~~~\:\  \ \:\  \\/__\:\  \   
    \::/  /      \::/  /      \:\__\       \::/  /      \:\__\        \:\__\ \:\__\    \:\__\  
     \/__/        \/__/        \/__/        \/__/        \/__/         \/__/  \/__/     \/__/ 
```

# About

This is another demoscene project, similar to [Kartina](https://github.com/Sl1mb0);   
music is played in the background, while an image is rendered.  
There is a secret word displayed at the end, that can only be seen by viewing the entire rendering.

# Goals

* Split view `Window` into 4x2 grid; 8 equally sized segments
* Each segment utilizes unique matrix transformation for all vertices within
* Window view rotates, changes positions, zooms in/out, 
  * each view must be different from the last (no loops)
* Apply each transformation continuously from 'A' to 'B'' (instead of discretely)
  * transformation must occur for all values between 'A' and 'B', as opposed to applying the transformation once to 'A' and yielding 'B'
* Highlight the presence of computation in modern music and images. 

# How It Works

TODO: discuss playing music and rendering using mult-threading  
TODO: discuss gpu-shader stuff  
TODO: discuss drawing words with vertices  
TODO: discuss matrix transformations  

# Testing 

# Licensing

# References

Learn WGPU

## Special credit to [Andrey Pushkarev](https://andreypushkarev.com)

