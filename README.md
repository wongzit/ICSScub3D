# ICSScub3D

Developed by Zhe Wang.

**Homepage** https://www.wangzhe95.net

ICSScub3D is the 3D version of ICSScsv. It can extract magnetic sheilding tensors from output
files can export them into a .cube file.

First pre-release is v0.6 (2021-06-06).


## Usage
*More detail information, please check the user manual.*
0. [ICSSgen3D](https://github.com/wongzit/ICSSgen3D) is a useful tools for generating the input files 
of 3D-ICSS calculations.
1. Run ICSScub3D.
2. Specify the path to output files. If you input **.../path/azulene_3DICSS_**, the
output files **.../path/azulene_3DICSS_0001.log**, **.../path/azulene_3DICSS_0002.log**,
**.../path/azulene_3DICSS_0003.log**, ... will be loaded to ICSScub3D.
```
Please specify the Gaussian output file path of NMR task:
Assume that you input "/path/ben_", then /path/ben_0001.log, /path/ben_0002.log /path/ben_0003.log, ... will be loaded.
(e.g.: /ICSScub3D/example/methylazulene_3DICSS_)
/Users/tetsu/Desktop/example/methylazulene_3DICSS_  
```
It may take some time to load the files.
3. Choose the component of ICSS plot. User can choose from isotropic, anisotropic, and 9 XYZ components 
of magnetic sheilding tensors from the menu.
4. The .cub file would be generated in the same folder as the output files.
5. Now, you can visualize the .cub using *GaussView*, *VMD*, *ChimeraX*, etc.
