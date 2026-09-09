# PUBH4201LAB1
# Instructions for Creating my repo
### Setup
  ### pip install conda
  conda -- version
  mkdir PUBH4201/LAB 1
  cd LAB 1
  touch README.md .gitignore environment.yml AI_USAGE.md
  mkdir src data
  touch src/.gitkeep data/.gitkeep ### Make sure you are still in LAB1
  mamba create -n PUBH4201/LAB1 python=3.12 pandas=2.2 -y ### or use LAB1
  conda activate PUBH4201/LAB1
  conda env export --from-history > environment.yml
  mamba env remove -n  LAB1 -y
  mamba env create -n  environment.yml
  conda activate PUBH4201/LAB1
  #### If you did not accidentally set up JupyterLab in terminal, use this
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ElizabethKishiAdefisan/PUBH4201LABONE.git
git push -u origin main
#### Else, i suggest opening up your repo, clicking "yes" on adding a README and. gitignore, and then individually setting up each file. Beacase SRC and Data are empty,  I suggest you use the tool given to me by my Gemini AI to make a file called ".gitkeep"
#### It is important that you are always in the LAB1 cd when doing this in the terminal
