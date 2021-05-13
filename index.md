## About me
My name is Lorenz Lechner. I work as a bicycle-courier and I am a FreeCAD enthusiast. My support for FreeCAD started in 2013 and includes the maintenance of conda-packages. In recent years I packaged a lot of [dependencies for FreeCAD](https://github.com/FreeCAD/FreeCAD_Conda) and started to create [packages of the latest source](https://github.com/looooo/freecad-feedstock) on every sunday.  
Other topics I was involved in are:
- python3 porting
- freecad-namespace-packages
- [openglider / glider-workbench](https://github.com/booya-at/OpenGlider)
- [freecad.gears](https://github.com/looooo/freecad.gears)
- [freecad.airfoil](https://github.com/looooo/freecad.airfoil)
- [pivy-maintainace](https://github.com/coin3d/pivy)

You can support my work via [liberapay](https://de.liberapay.com/looooo/).

## Contributions
<img src="https://grass-graph.moshimo.works/images/looooo.png">

## 2021
* [update occt-feedstock to 7.5.2](https://github.com/conda-forge/occt-feedstock/pull/67)
* [create github-action script to test pivy](https://github.com/coin3d/pivy/pull/83)
* [create feedstock for fcitx](https://github.com/conda-forge/staged-recipes/pull/14131)
* [build libxfoil for windows](https://github.com/conda-forge/libxfoil-feedstock/pull/7)
* update weekly builds to occt7.5 / vtk9 / py3.9
* update gmsh to work with occt7.5
* [conda-based freecad 0.19.1-release-bundles](https://github.com/FreeCAD/FreeCAD/releases/tag/0.19.1)
* release pivy 0.6.6
* use github actions to create freecad-bundles
* update freecad related conda-packages to occt7.5
* update freecad related conda-packages to vtk9


## 2020
* 201111 update opencamlib-feedstock (py3.9 / boost1.74)
* 201020 work on appimage/bundle-scripts: change workflow to use branches for different releases
* 2010xx ongoing migration py3.9 / gcc9 / boost 1.74
* 200930 add [appimage-updater-bridge-feedstock](https://github.com/conda-forge/appimage-updater-bridge-feedstock)
* 200929 rework the matplotlib-integration (use freecad as a matplotlib backend)
* 200920 update ifcopenshell to boost 1.74
* 200910 [work on ifcopenshell feedstock](https://github.com/conda-forge/ifcopenshell-feedstock/pull/11)
* 200910 [update freecad.asm3 feedstock](https://github.com/looooo/solvespace-feedstock/)
* 200910 [update solvespace feedstock](https://github.com/looooo/freecad.asm3-feedstock)
* 200822 [include pythonocc-core in bundles](https://github.com/FreeCAD/FreeCAD-AppImage/commit/41ebeb8681eff9604d0584c3586e95cec78d0711)
* 200821 [fix calculix windows build](https://github.com/conda-forge/calculix-feedstock/commit/73386b5f95c631b356d3f8ac975ad1a8ca1d5f1a)
* 200805 update to libredwg v0.10.1.3776
* 200804 occt-vtk8-pining
* 200728 [work on ccx-2.17 feedstock](https://github.com/conda-forge/calculix-feedstock/pull/15)
* 200717 [add latern gear to freecad.gears](https://github.com/looooo/freecad.gears/commit/ecca07dcad1f51e1bac3bdbf5cf4972999673de3)
* 200715 [add timing gears to freecad.gears](https://github.com/looooo/freecad.gears/commit/9757de0c58a6fec58686aa9d7822e7d7c93383fb)
* 200715 pivy 0.6.6.a0 release (cmake support) 
* 200527 work on appimage-updater-tool
* 200507 work on netgen-feedstock
* 200507 patching smesh for netgen 6.2.2004
* 200504 creating freecad0.19.alpha2 release on conda-forge
* 200502 working on netgen 6.2.2004 support
* 200501 pin smesh to exact version of netgen
* 200424 [move pivy build setup to cmake](https://github.com/coin3d/pivy/pull/69)
* 200407 [freecad.gears: add module to compute 2d profiles](https://github.com/looooo/freecad.gears/issues/38)
* 200402 [add xlutils-feedstock](https://github.com/conda-forge/xlutils-feedstock)
* 200321 [appimage_updater](https://github.com/FreeCAD/FreeCAD_Conda/tree/master/appimage-updater-bridge)
* 200312 [pivy: add SoGeo bindings](https://github.com/coin3d/pivy/commit/3b073f4309bd952f3078088178d9985f1969c556)
* 200310 [add windows support for libredwg](https://github.com/conda-forge/libredwg-feedstock/pull/23)
* 200310 [update coin3d-feedstock](https://github.com/conda-forge/coin3d-feedstock/pull/17)
* 200310 [add suplerglu to windows coin3d-package](https://github.com/coin3d/coin/issues/375)
* 200302 [patch libspnav](https://github.com/conda-forge/libspnav-feedstock/commit/317881d07573ea6a195d5e985dc06328be93e88e)
* 200226 [update occt-feedstock](https://github.com/conda-forge/occt-feedstock/pull/35)
* 200225 [work on pythonocc recipe](https://github.com/conda-forge/staged-recipes/pull/10919)
* 200222 updating several feedstocks to boost 1.72 
* 200212 [Add pycollada to conda-forge](https://github.com/conda-forge/staged-recipes/pull/10837)
* 200210 [Trying to enable osx space-mouse support](https://github.com/looooo/freecad-feedstock/commit/20646baef17a688191a759c4b641487f7a30cbbf)
* 200205 [Add some modification to the gear-workbench](https://github.com/looooo/freecad.gears/compare/f77e2793ef97def9bf7f8c7ceca540714a3e66d4...3eea5eb8ca3870042c17d976972683d691b7a7dd)
* 200201 [start with aarch migration for pivy](https://github.com/conda-forge/conda-forge-pinning-feedstock/pull/388)
* 200128 add conda-package for asm3 to appimage: [freecad.asm3-package](https://github.com/FreeCAD/FreeCAD_Conda/tree/master/freecad.asm3), [diff for asm3](https://github.com/realthunder/FreeCAD_assembly3/pull/283), [appimage-update](https://github.com/FreeCAD/FreeCAD-AppImage/commit/3bc8bb415c1050576d8f9bf2a2d8b46a4fa91bfc)
* 200127 [print dependencies for appimage for debugging](https://github.com/FreeCAD/FreeCAD-AppImage/pull/32)
* 200126 [update libredwg-feedstock to 0.10.1.2729](https://github.com/conda-forge/libredwg-feedstock/pull/14)
* 200123 [work on macOS dmg problem](https://forum.freecadweb.org/viewtopic.php?f=22&t=42644)
* 200121 [update calculix feedstock](https://github.com/conda-forge/calculix-feedstock/pull/13)
* 200120 [update libredwg-feedstock to 0.9.3.2600](https://github.com/conda-forge/libredwg-feedstock/pull/10)
* 200118 [update pivy-feedstock to 0.6.5](https://github.com/conda-forge/pivy-feedstock/pull/22)
* 200117 [update soqt-feedstock to 1.6.0](https://github.com/conda-forge/soqt-feedstock/pull/6)
* 200117 [update coin3d-feedstock](https://github.com/conda-forge/coin3d-feedstock/pull/15)
* 200114 [update simage-feedstock to simage 1.8.0](https://github.com/conda-forge/simage-feedstock/pull/11#partial-pull-merging), [create PR for simage](https://github.com/coin3d/simage/pull/31) to disable cpack by default
* 200114 update weekly builds to py38
* 200114 create [solvespace-feedstock](https://github.com/looooo/solvespace-feedstock) and upload py38 packages
* 200113 upload solvespace linux package for py3.8 to channel freecad  
* 200112 upload pyside2 5.13 package for py3.8 to freecad/label/testing
and create [PR](https://github.com/conda-forge/pyside2-feedstock/pull/62) for pyside-feedstock
* 200107 upload freecad 0.19pre with python3.8 to freecad/label/testing
* 200106 update freecad-feedstock (0.19pre) to use occt7.4
* 200106 upload freecad 0.19pre with occt7.4 to freecad/label/testing
* 200105 [package smesh8.3 for occt7.4](https://github.com/conda-forge/smesh-feedstock/pull/27)  
big thanks to @trelau for making this possible!!!
* 200102 Updating libredwg-feedstock to 0.9.3.
