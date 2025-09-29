## NoLiES: The non-linear embeddings surveyor

Code for the paper _Attribute-based Explanation of Non-Linear Embeddings of High-Dimensional Data_

presented at IEEE VIS 21 -- published in IEEE Transactions on Visualization and Computer Graphics (TVCG).

Preferably cited as: \
J.-T. Sohns, M. Schmitt, F. Jirasek, H. Hasse, H. Leitte. Attribute-based Explanation of Non-Linear Embeddings of High-Dimensional Data. _IEEE Transactions on Visualization and Computer Graphics (2022)_, 28(1), 540-550. _DOI: https://doi.org/10.1109/TVCG.2021.3114870_

## Video Explanations

![teaser image](https://github.com/Jan-To/nolies/blob/main/teaser_img.jpg)

[Preview Video on RPTU-hosted Site (2min)](https://vcm.uni-kl.de/Panopto/Pages/Viewer.aspx?id=f37f5bac-7f0f-4cf3-9ea5-b367007ece9c)

[Presentation at IEEE VIS on RPTU-hosted Site (12min)](https://vcm.uni-kl.de/Panopto/Pages/Viewer.aspx?id=c9f5aae6-0cfe-4eb8-8ab5-b367007ef6ff)

## Run the code on your own data

Download the repository and create an environment with the dependencies:
```
git clone https://github.com/Jan-To/nolies
conda env create -f nolies.yml
conda activate nolies
```

Make a copy of the template jupyter notebook:
```
cp template.ipynb my_data.ipynb
```

Update the notebook to load your data. Open the notebook with jupyter lab or jupyter notebook and edit the section **Load data**. Important parameters are grouped in the section **Parameters** and **Preprocessing**:
```
jupyter lab
```

Start the interactive web app:
```
panel serve --show my_data.ipynb
```
