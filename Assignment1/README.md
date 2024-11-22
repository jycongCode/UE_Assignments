**Tips for Comiling UE5.4**

- Link your github account to Epic games organization

- `git clone -b 5.4 ...` gets the targeted version

- Set up visual studio according to the official site

![](img\img1.png)

![](img\img2.png)

> - .Net framework: third-party & plugins backend services/tooling
> 
> - C++ tool chain: Mainly MSVC & MSBuild, UnrealBuildTools work somewhat like CMake
> 
> - C++ game development: C++ tool chain, Game specific functionalities , plugins

- Bigger DRAM makes the process much easier: 
  
  - AMD Ryzen 7 8845H + Crucial DDR5-5600 MHz 64(2x32)GB
  
  - Time : at least 40 min

**Tips for packaging**

- Windows platform:
  
  - Tried packaging the Unlua Demo project: TPShooting
  
  - Relativly simple, as long as you get the visual studio setup correcly
  
  - TODO: Unlua AI module dies after packaging
