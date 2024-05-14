
# polCAs

**Polarized cortical assembloids (polCAs)**

Here the code used to analyse polCAs Single Cell data

![plot](./figures/FigureGithub.png)


base docker image can be retrieved via docker pull testalab/downstream:polaroid-0.1.3

list of additional libraries installed locally can be found in data/env/python3_libs.txt and data/env/R_libs.txt

Data should be placed as follows:<br>   
Anndata of Badhuri et. al (10.1038/s41586-021-03910-8)    ./data/Badhuri_atlas.h5ad<br>   
Ppoliudakis et. al(10.1016/j.neuron.2019.06.011):    ./data/Geschwind_atlas.h5ad<br>   
Raw data of experiments (control1_piece1, control1_piece2 ... polaroid3_distal):    ./data<br>   
or pre-processed polCAs (optional):    ./outdir/02C_Preprocess_final.h5ad


An html version of the notebooks is accessible [here](https://GiuseppeTestaLab.github.io/polCAs/).




## Badhuri0.Preprocess

Links: [jupyter notebook](Badhuri0.Preprocess.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri0.Preprocess.html).





## Badhuri01B.ProgenitorsReanalysis

Links: [jupyter notebook](Badhuri01B.ProgenitorsReanalysis.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri01B.ProgenitorsReanalysis.html).





## Badhuri01C.CyclingReanalysis

Links: [jupyter notebook](Badhuri01C.CyclingReanalysis.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri01C.CyclingReanalysis.html).





## Badhuri02.preBulk

Links: [jupyter notebook](Badhuri02.preBulk.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri02.preBulk.html).





## Badhuri02B.pseudoBulking

Links: [jupyter notebook](Badhuri02B.pseudoBulking.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri02B.pseudoBulking.html).





## Badhuri03A_Neurons.3pointsModel

Links: [jupyter notebook](Badhuri03A_Neurons.3pointsModel.pBulk_byArea_scaling.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri03A_Neurons.3pointsModel.pBulk_byArea_scaling.html).





## Badhuri03B_Progenitors.3pointsModel

Links: [jupyter notebook](Badhuri03B_Progenitors.3pointsModel.pBulk_byArea_scaling.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri03B_Progenitors.3pointsModel.pBulk_byArea_scaling.html).





## Badhuri03C_Cycling.3pointsModel

Links: [jupyter notebook](Badhuri03C_Cycling.3pointsModel.pBulk_byArea_scaling.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/Badhuri03C_Cycling.3pointsModel.pBulk_byArea_scaling.html).





## polCAs01_RawImport

Links: [jupyter notebook](polCAs01_RawImport.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs01_RawImport.html).





## polCAs02_Preprocess_Gruffi

Links: [jupyter notebook](polCAs02_Preprocess_Gruffi.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs02_Preprocess_Gruffi.html).





## polCAs03_Dimreduct_exploration

Links: [jupyter notebook](polCAs03_Dimreduct_exploration.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs03_Dimreduct_exploration.html).





## polCAs04_Dimreduct_inDepthMarkers

Links: [jupyter notebook](polCAs04_Dimreduct_inDepthMarkers.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs04_Dimreduct_inDepthMarkers.html).





## polCAs04.2_Differential_abundance

Links: [jupyter notebook](polCAs04.2_Differential_abundance.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs04.2_Differential_abundance.html).





## polCAs05_RG_and_Neurons_Focus

Links: [jupyter notebook](polCAs05_RG_and_Neurons_Focus.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs05_RG_and_Neurons_Focus.html).





## polCAs06_Dimreduct_inDepthCompositions

Links: [jupyter notebook](polCAs06_Dimreduct_inDepthCompositions.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs06_Dimreduct_inDepthCompositions.html).





## polCAs08_Developmental_Trajectories

Links: [jupyter notebook](polCAs08_Developmental_Trajectories.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAs08_Developmental_Trajectories.html).





## polCAsCycling01_Selection

Links: [jupyter notebook](polCAsCycling01_Selection.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling01_Selection.html).





## polCAsCycling02_pBulk

Links: [jupyter notebook](polCAsCycling02_pBulk.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling02_pBulk.html).





## polCAsCycling03_fg8_tomato_check

Links: [jupyter notebook](polCAsCycling03_fg8_tomato_check.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling03_fg8_tomato_check.html).





## polCAsCycling04_pBulk_bySegment.DEA

Links: [jupyter notebook](polCAsCycling04_pBulk_bySegment.DEA.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling04_pBulk_bySegment.DEA.html).





## polCAsCycling05A_POLAROIDS_BadhuriSpace

Links: [jupyter notebook](polCAsCycling05A_POLAROIDS_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling05A_POLAROIDS_BadhuriSpace.html).





## polCAsCycling05B_CONTROLS_BadhuriSpace

Links: [jupyter notebook](polCAsCycling05B_CONTROLS_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling05B_CONTROLS_BadhuriSpace.html).





## polCAsCycling05C_ALL_BadhuriSpace

Links: [jupyter notebook](polCAsCycling05C_ALL_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling05C_ALL_BadhuriSpace.html).





## polCAsBadhuriSpace_LoadingsAgreement

Links: [jupyter notebook](polCAsCycling05C_ALL_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsCycling05C_ALL_BadhuriSpace.html).





## polCAsProgenitors01_Selection

Links: [jupyter notebook](polCAsProgenitors01_Selection.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors01_Selection.html).





## polCAsProgenitors02_pBulk

Links: [jupyter notebook](polCAsProgenitors02_pBulk.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors02_pBulk.html).





## polCAsProgenitors03_fg8_tomato_check

Links: [jupyter notebook](polCAsProgenitors03_fg8_tomato_check.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors03_fg8_tomato_check.html).





## polCAsProgenitors04_pBulk_bySegment.DEA

Links: [jupyter notebook](polCAsProgenitors04_pBulk_bySegment.DEA.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors04_pBulk_bySegment.DEA.html).





## polCAsProgenitors05A_POLAROIDSBadhuriSpace

Links: [jupyter notebook](polCAsProgenitors05A_POLAROIDSBadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors05A_POLAROIDSBadhuriSpace.html).





## polCAsProgenitors05B_CONTROLS_BadhuriSpace

Links: [jupyter notebook](polCAsProgenitors05B_CONTROLS_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors05B_CONTROLS_BadhuriSpace.html).





## polCAsProgenitors05C_ALL_BadhuriSpace

Links: [jupyter notebook](polCAsProgenitors05C_ALL_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsProgenitors05C_ALL_BadhuriSpace.html).





## polCAsNeurons01_Selection

Links: [jupyter notebook](polCAsNeurons01_Selection.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons01_Selection.html).





## polCAsNeurons02_pBulk

Links: [jupyter notebook](polCAsNeurons02_pBulk.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons02_pBulk.html).





## polCAsNeurons03_fg8_tomato_check

Links: [jupyter notebook](polCAsNeurons03_fg8_tomato_check.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons03_fg8_tomato_check.html).





## polCAsNeurons04_pBulk_bySegment.DEA

Links: [jupyter notebook](polCAsNeurons04_pBulk_bySegment.DEA.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons04_pBulk_bySegment.DEA.html).





## polCAsNeurons05A_POLAROIDS_BadhuriSpace

Links: [jupyter notebook](polCAsNeurons05A_POLAROIDS_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons05A_POLAROIDS_BadhuriSpace.html).





## polCAsNeurons05B_CONTROLS_BadhuriSpace

Links: [jupyter notebook](polCAsNeurons05B_CONTROLS_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons05B_CONTROLS_BadhuriSpace.html).





## polCAsNeurons05C_ALL_BadhuriSpace

Links: [jupyter notebook](polCAsNeurons05C_ALL_BadhuriSpace.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/polCAsNeurons05C_ALL_BadhuriSpace.html).





## MfuzzTrends

Links: [jupyter notebook](MfuzzTrends.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/MfuzzTrends.html).





## BraunAtlas_comparison_01atlasPrep

Links: [jupyter notebook](BraunAtlas_comparison.01atlasPrep.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/BraunAtlas_comparison.01atlasPrep.html).





## BraunAtlas_comparison_02organopidsPrep

Links: [jupyter notebook](BraunAtlas_comparison.02organopidsPrep.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/BraunAtlas_comparison.02organopidsPrep.html).





## BraunAtlas_comparison_03polCAsCompare

Links: [jupyter notebook](BraunAtlas_comparison.03polCAsCompare.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/BraunAtlas_comparison.03polCAsCompare.html).





## BraunAtlas_comparison_04KantonCompare

Links: [jupyter notebook](BraunAtlas_comparison.04KantonCompare.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/BraunAtlas_comparison.04KantonCompare.html).





## BraunAtlas_comparison_05VelascoCompare

Links: [jupyter notebook](BraunAtlas_comparison.05VelascoCompare.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/BraunAtlas_comparison.05VelascoCompare.html).





## COL1A2gene_check

Links: [jupyter notebook](COL1A2genes.ipynb) and [html file](https://GiuseppeTestaLab.github.io/polCAs/COL1A2genes.html).




Repository will be complete upon publication


---
*Note: this README file has been generated automatically.* <br>
*Please do not modify it directly but instead work on [this config file](resources/config.yaml).*


