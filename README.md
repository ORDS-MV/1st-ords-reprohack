![](https://github.com/reprohack/reprohack-hq/blob/master/assets/reprohack-banner.png?raw=true)

_1st ORDS ReproHack_
=== 

<img src="https://github.com/ORDS-Rostock/1st-ords-reprohack/blob/main/reprohack-rostock.png?raw=true" alt="drawing" width="200"/>

###### tags: `Reprohack` `ORDS` `Rostock` `TKFDM` 

:::info
- :calendar: **11th May 2021 CEST**
- :watch: **9:30--15:00** 
- :earth_africa: **Remote:** https://bbb-greenlight.uni-rostock.de/b/fra-zr0-xmc-sa1
- :purple_heart: **Code of Conduct:** https://github.com/reprohack/reprohack-hq/blob/master/CODE_OF_CONDUCT.md
- :arrow_forward: **Slides:** https://anja-eggert.net/wp-content/uploads/intro-slides.html
- :writing_hand: **Author feedback form:** https://evasys.uni-rostock.de/evasys/online.php?p=ReproHack

# Agenda

**9:30 - Opening and virtual come together**

* Introduction ORDS
* Icebreaker
* Introduction TKFDM
* Article including Code and Data
* Team formation 

**10:00 - 1st part of the workshop**

* Hands-on analysis in teams

**11:30 - Rejoin and tell**

**12:00 - Lunch break :pizza: :stew: :strawberry:**

**13:00 - 2nd part of the workshop**

* Continue working in your team
* Prepare feedback to the group and for the authors

**14:30 - Evaluation and Goodbye**

### **Participants**
***Please sign in (Affiliation / Twitter / GitHub)***
#### If you have a twitter handle, please add it!
* Frank Krüger (University of Rostock / [@\_frank_k\_](https://twitter.com/_frank_k_) / [f-krueger](https://github.com/f-krueger) ) 
* Manuela Reichelt (FBN Dummerstorf / [@manuReichelt](https://twitter.com/ManuReichelt) / [ManuelaReichelt](https://github.com/ManuelaReichelt))
* Anja Eggert (FBN Dummerstorf / [@AnjaEggert42](https://twitter.com/AnjaEggert42) / [AnjaEggert](https://github.com/AnjaEggert))
* Max Schröder (University of Rostock / [@m6121](https://twitter.com/m6121) / [m6121](https://github.com/m6121))
* Jessica Rex (Technical University of Ilmenau / [@ThatDataStuff] (https://twitter.com/ThatDataStuff)
* Roman Gerlach (Friedrich-Schiller-University Jena / [@FDMThueringen](https://twitter.com/FDMThueringen) )
* Kevin Lang (Bauhaus-Universität Weimar / [@kev_lan](https://twitter.com/kev_lan) / [GitHub](https://github.com/KujaEx))
* Anke Günther (Uni Rostock, Uni Greifswald)
* Fabian Dröge (Uni Jena / [GitLab](https://gitlab.com/FabianGD))
* Sheeba Samuel (Uni Jena/ [@sheebasamuel](https://twitter.com/sheebasamuel)/[GitLab](https://github.com/Sheeba-Samuel/))
* Phillip Seeber (Uni Jena / [GitLab](https://gitlab.com/sheepforce))
* Kai Budde (Uni Rostock / [GitHub](https://github.com/buddekai))
* Stephanie Dahn (Uni Rostock) [GitHub](https://github.com/KangarooSurfer) [Twitter](https://twitter.com/stephaniedahn)
* Markus Zehner (Uni Jena / [GitHub](https://github.com/MarkusZehner))
* Henja Wehmann (Uni Rostock)
* Felix Cremer (DLR Jena / [GitHub](https://github.com/felixcremer))
* Sebastian Seidenath (Friedrich-Schiller-University Jena)
* Oscar Beltran (Leibniz Institute for Baltic Sea Research)
* Taufia Hussain (Uni Rostock/ [GitHub])
* Inga Ulusoy (Scientific Software Center, Uni Heidelberg / [GitHub](https://github.com/iulusoy))

:::

# Icebreaker

Form teams and try to answer the following questions in breakout rooms.

- Who are you?
- Why are you here?
- What is your level of repro-experience?
- What is your favorite (new) hobby after a year of on/off Corona lock down?

**As a group: name your room!**
- What do you have in common?

**Rooms:**
1. all-over-Germany-group
2. Thuringian-group
3. techincal-issues-group
4. wannabe-musicians-group
5. white-wall-group

# :recycle: ReproHacking - Plan of Action

In contrast to other ReproHacks, here we focus on one particular paper rather than an entire list of papers. We selected the following article:

Luis M. Vilches-Blázquez & Daniela Ballari (2020):
**Unveiling the diversity of spatial data infrastructures in Latin America: evidence from an exploratory inquiry**, Cartography and Geographic Information Science, DOI: [10.1080/15230406.2020.1772113](https://doi.org/10.1080/15230406.2020.1772113)

(author copy available for [Download](https://unibox.uni-rostock.de/getlink/fi6BVET7tsTf89NdAdkHmGcc/SDI_10.1080%4015230406.2020.1772113.pdf))

# :computer: Form Teams

Feel free to either join the predefined teams *Beginners*, *Advanced*, or *Experts*, create your own team, or work individually on the paper. 

## Beginners (Room 1)
The paper is analysed with respect to their published resources and the original analysis is re-run in order to see whether the same results will be generated.

_Participants are expected to have some basic knowledge of R_


Participants:
* **Manuela Reichelt**
* **Anja Eggert**
* **Jessica Rex**
* **Franziska Koebsch**
* **Anke Günther**
* **Henja Wehmann** (knows R, but programming skills are a mess)
* Stephanie Dahn (**really** basic R knowledge)
* **Alexander Schwab** (no significant knowledge unfortunately)
* **Sebastian Seidenath** (no significant knowledge unfortunately)
* **Taufia Hussain (basic R knowledge)**
* Dietmar Zechner (no knowledge)
* Oscar Beltran



### Feedback
* Figure 2b: "Yes" bar missing for Colombia 2017 in the article, caused by zooming in too much on the y-axis (bottom)
*  Round while preserving sum:
[Link to r-bloggers](https://www.r-bloggers.com/2016/07/round-values-while-preserve-their-rounded-sum-in-r/)

## Advanced Python (Room 2)
The paper's analysis is re-implemented in a Python Jupyter notebook to see whether the same results can be generated in a different computational environment. 

_Participants are expected to have some basic knowledge in R and Python_

Participants:
* **Frank Krüger**
* **Kevin Lang** (Python with Jupyter)
* **Inga Ulusoy**
* **Fabian Dröge** --> Julia or Python, I don't mind :)
* **Felix Cremer** would like to use [Julia](https://julialang.org/)
* **Markus Zehner**
* **Sheeba Samuel**

### Feedback so far
 * recreated first two plots with `python` and `julia`
 * some raw values adjusted (inserted magic numbers)
 * Translation to Julia seems complicated
 * R code is fairly structured and easy to follow, makes the task of mapping into a different language a lot easier
 * for the maps, we use shape files from https://tapiquen-sig.jimdofree.com/english-version/free-downloads/americas/
 * the shapefiles were added manually over the bar plots
## Experts (Room 3)

A computational environment for both, the original analysis and the re-implemement analysis, is created.

_Participants are expected to have some basic knowledge in R, Python and Docker_

Participants:
* **Max Schröder**
* **Roman Gerlach**
* **Phillip Seeber** (Haskell, Nix)

### Documentation
* Paper uses survey to gather data
* Data and source code published on figshare:
    * Excel sheet with cleaned data (years: 2019, 2017, 2014) (cleaning process see paper)
    * Rmarkdown document
    * HTML with details and figures
* Use command to produce HTML: `Rscript -e "library(knitr); knitr::knit2html('Survey_Trend_SDI.Rmd')"` or better: `Rscript -e "library(knitr); rmarkdown::render('Survey_Trend_SDI.Rmd')"`
* We aim at two different computing environments:
    * [Docker](https://www.docker.com/)
    * [Nix](nixos.org)



### Docker

#### R

`install.R`:
```R
install.packages(c('remotes'), repos='https://ftp.fau.de/cran/')

require(remotes)

install_version("knitr", version='1.28', repos="https://ftp.fau.de/cran/")
install_version("rmdformats", version='0.3.6', repos="https://ftp.fau.de/cran/")
install_version("readxl", version='1.3.1', repos="https://ftp.fau.de/cran/")
install_version("ggplot2", version='3.2.1', repos="https://ftp.fau.de/cran/")
install_version("stringr", version='1.4.0', repos="https://ftp.fau.de/cran/")
install_version("rworldmap", version='1.3-6', repos="https://ftp.fau.de/cran/")
install_version("RColorBrewer", version='1.1-2', repos="https://ftp.fau.de/cran/")
install_version("DT", version='0.12', repos="https://ftp.fau.de/cran/")
install_version("plyr", version='1.8.6', repos="https://ftp.fau.de/cran/")
install_version("tidyr", version='1.0.2', repos="https://ftp.fau.de/cran/")
install_version("ggpubr", version='0.2.5', repos="https://ftp.fau.de/cran/")

require(c(
    knitr,
    rmdformats,
    readxl,
    ggplot2,
    stringr,
    rworldmap,
    RColorBrewer,
    DT,
    plyr,
    tidyr,
    ggpubr
))
```

```dockerfile
FROM r-base:3.6.3

LABEL maintainer="max.schroeder@uni-rostock.de;roman.gerlach@uni-jena.de"

RUN apt update \
    && apt install -y \
         libcurl4-openssl-dev \
         pandoc \
    && apt clean \
    && rm -rf /var/lib/apt/lists/*

COPY install.R /tmp/install.R

RUN Rscript /tmp/install.R
```

```bash
docker build -t ords-reprohack:r-container .
docker run --rm -u $(id -u) -v /data/reprohack:/opt/data -w /opt/data ords-reprohack:r-container Rscript -e "library(knitr); rmarkdown::render('Survey_Trend_SDI.Rmd')"
```

#### Python 

Software dependencies:

* Jupyter Notebook with Python3 Kernel
* Python packages:
    * pandas
    * matplotlib
    * geopandas

```dockerfile
FROM jupyter/scipy-notebook:09fb66007615

LABEL maintainer="max.schroeder@uni-rostock.de;roman.gerlach@uni-jena.de"

RUN python3 -m pip install -r geopandas==0.9.0
```

### Nix

The Nix version reproduces the original data with hermetic nix down to the exact hashes. 
A GitLab repository with the Nix expressions and a short description how to build is at [GitLab](https://gitlab.com/sheepforce/reprohack).

The build definition is given by 
```nix
{ stdenvNoCC, lib, fetchurl, unzip, rPackages, rWrapper, pandoc }:

let
  rPkgs = import ./pkgs.nix { inherit rPackages; };
  rWithPkgs = rWrapper.override { packages = rPkgs; };

in stdenvNoCC.mkDerivation rec {
  pname = "ReproHack-Original";
  version = "1.0";

  src = fetchurl {
    url = "https://s3-eu-west-1.amazonaws.com/pfigshare-u-files/22720802/SupplementaryMaterial.zip";
    sha256 = "00lsp163q44dn8adlra8vaf4cgcyiifv2nh0qabypsfcgzj0c2sd";
  };

  nativeBuildInputs = [
    pandoc
    rWithPkgs
    unzip
  ];

  phases = [
    "unpackPhase"
    "buildPhase"
    "installPhase"
  ];

  installTargets = [
    "Survey_Trend_SDI.html"
    "Survey_Trend_SDI_files"
  ];

  unpackPhase = ''
    unzip $src
  '';

  buildPhase = ''
    Rscript -e "library(knitr); rmarkdown::render('Survey_Trend_SDI.Rmd')"
  '';

  installPhase = ''
    mkdir -p $out
    for i in ${toString installTargets}; do
      cp -r $i $out/.
    done
  '';
}
```
which is fully reproducible, as the dependencies are exactly pinned by git and sha256 hashes.

A Jupyter Lab environment that can fully run the Jupyter notebook from the advanced group can be obtained from within the `Python` directory by executing
```
nix-shell --command "jupyter lab"
```
and in jupyter lab select the `ReproHackPython` kernel.

:books: Reproduce
---
- We attempt to reproduce the paper from available materials and documentation
- Make notes about your experiences, in particular with respect to how easy it is to:
    - :earth_africa: navigate the materials
    - :repeat: reproduce the analysis
    - :recycle: reuse the materials


:memo:  Feedback to authors
---

* Fill in the author feedback form, documenting your experiences reproducing your chosen group
  - :writing_hand: **Feedback form:** https://evasys.uni-rostock.de/evasys/online.php?p=ReproHack

---

# :raised_hand_with_fingers_splayed:  5-finger Feedback for this event

## :point_up: One thing that you enjoyed
_(put your comments here)_
- to try something I have no idea- Thanks a lot to the organizers
- high level overview of completely foreign data and working with them
- trying to get into a completely new language
- coding together 
- learning
- I enjoyed taking on the role of inspecting in detail the results of a paper and exploring the tools available to do so.
- working in just one paper +1

## :point_up: One thing that can be improved
_(put your comments here)_
- the tooling was communicated more openly on the website than it was in the end in reality (reduction to Python, Julia)
- more smaller breaks in between where technical issues can be adressed and where you have time to read into new things (and for having snacks :D )
- more structured sections for working and listening - doing everything at once sometimes was very exhausting for me
- perhaps have the paper at least one hour beforehand to know what it is about.
- give an overview about the data (files and meaning)
- give a short introduction about the paper and what we are reproducing
- after coming back from lunch had problems to enter a breakout room
- technical issues in joining the main room
- it would be good to have a place (online) to share the intermediate results/code within the breakout group members. May be also a shared computational environment.

## :point_up: One thing that you did not like
_(put your comments here)_
- working remotely :/
- doing only plots, it would also be interesting to have a paper with a more interesting methodology, where also the reproduction is harder, because we could have rounding errors and other subtle differences

## :point_up:  One thing that you would like to keep
_(put your comments here)_
- separation into groups with different technologies and aspects
- openness to beginners 
- different levels of expertise
- open to different programming languages +1

## :point_up: One thing that came up short
_(put your comments here)_
- time, I think it would be nicer, to have a little bit more time
- intro into reproducibility and what we are actually looking for while doing the analysis

