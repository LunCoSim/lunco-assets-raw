# LunCo: Assets

This repository containts raw blender models and other assetes not adapted to LunCo.
The models in this repo to be converted into Godot-compatible file format
Models used in this repo are based on MIT-compatible source.

This repo uses **git lfs**. Check below how to use it

In general the following structure
[Pack name]/
    materials/
    parts/
    assemblies/
    environment/
    shared/
    textures/
    README.MD
    info.json

Suggestion to use [Building topology](https://w3c-lbd-cg.github.io/bot/)
For robots/vehicles?


## Tips & Tricks

### Missing files in Blender

File -> External data -> Find missing files

### How to use **git lfs**
<details>
    <summary>
        How to install git lfs (click to expand)
    </summary>

   1. Install git lfs:

   1.1 MacOS: 

    brew install git-lfs

   1.2 Other OS:

    [git lfs](https://git-lfs.github.com)

   1. Activate **git lfs** (once on computer):

            git lfs install
</details>

<details>
    <summary>
        How to clone and use this repo with git lfs (click to expand)
    </summary>
1. Clone repo:

    git lfs clone git@github.com:LunCoSim/lunco-vision-video.git

2. If repo cloned without lfs:
   a. Goto to directory

        cd lunco-vision-video
   b. type 

        git lfs pull

3. Now all the Blender models will be downloaded to your computer. Start using them!

4. Push & pull binary files as reqular
</details>

<details>
    <summary>
        How to commit binary files (click to expand)
    </summary>

1. Start tracking files
   
   git lfs track  "*.blend", "*.png", "*.jpg", "*.jpeg", "*.tif", "*.gif", "*.bmp", "*.svg", "*.hdr"

2. With with files as usual

</details>