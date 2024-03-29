
## Introdução à Ciência de Dados com R/tidyverse

  - Organizador: Legalité-PUC RJ
  - Professor: [Dan S. Reznik (PUC-CCE)](https://www.dat-sci.com),
    <dan@upperwestsolucoes.com>
  - Monitores
      - Thomás Jagoda (UFRJ), <thomasjagoda@poli.ufrj.br>
  - Homepage: <https://dan-reznik.github.io/MPRJ-Main/>

### Notebook recomendado

  - CPU i3 (6a geração ou melhor), RAM \>= 4Gb, Windows10  
  - Tela: 14” (ou maior) e “full HD” (1920x1080). Evitar telas HD “puro”
    (720p)
  - Exemplo: [Samsung Essentials
    E30](https://www.americanas.com.br/produto/133794107)

### Downloads

  - [R 3.6.3](https://cran.r-project.org/bin/windows/base/)
  - [RStudio 1.2.5033](https://rstudio.com/products/rstudio/download/#download)
  - [Git](https://git-scm.com/downloads)
  - [Notepad++](https://notepad-plus-plus.org/download/v7.6.4.html)

### Pós-Instalação

  - Instalar pacote `tidyverse` executando no cmd prompt:
      - `R -e
        "install.packages('tidyverse',repo='https://cloud.r-project.org')"`

### Git e GitHub

<img src="pics/git.png" width="50%" />

  - GitHub
      - Criar conta no GitHub
      - Fork: <https://github.com/JagodaT/Curso-Data-Science>
  - RStudio, criar chaves SSH
      - `git remote -v`
      - `git remote set-url origin git@github.com:user/repo_name.git`
  - Git, identificar usuário no cmd prompt:
      - `git config --global user.email "<seu_mail>@<...>.com"`
      - `git config --global user.name "<seu nome>"`

### Slides

  - [Aula
    Introdutória](https://drive.google.com/file/d/1OIzDMSyUu_GTgvxpkKXvTqNeYLjUEY2C/view)

### Links Interessantes

  - Estudo sobre o [Corona
    Vírus](https://www.r-bloggers.com/covid-19-epidemiology-with-r/)
  - [Companies Using
    R](https://github.com/ThinkR-open/companies-using-r)
  - Site com materiais diversos sobre R-tidyverse:
    [teachR](https://teachingr.com)

### Exercícios

  - Página [principal](https://jagodat.github.io/MPRJ-Exercicios/)
      - dplyr
          - [1a
            lista](https://jagodat.github.io/MPRJ-Exercicios/content/ex_dplyr.html),
            Matheus Donato
          - [2a
            lista](https://teachingr.com/content/the-5-verbs-of-dplyr/the-5-verbs-of-dplyr-exercise.html),
            Ben Stenhaug
      - ggplot2
          - [1a
            lista](https://jagodat.github.io/MPRJ-Exercicios/content/visualizacao.html),
            Thomás Jagoda
          - [2a
            lista](https://jagodat.github.io/MPRJ-Exercicios/content/visualizacao2.html),
            Thomás Jagoda

### Livros Online (grátis)

  - <span style="background-color: #FFFF00">H. Wickham & G. Grolemund
    </span>, [“R for Data Science” (r4ds)](https://r4ds.had.co.nz/)
  - Kieran Healy, [“Data Visualization”](https://socviz.co/)
  - Claus Wilke, [“Fundamentals of Data
    Visualization”](https://serialmentor.com/dataviz/)
  - Winston Chang, [Graphics Cookbook](https://r-graphics.org/), 2nd
    edition
  - Garrett Grolemund, [“Hands-on Programming with
    R”](https://rstudio-education.github.io/hopr/)
  - Claudia Engel, [“Data Wrangling with
    R”](https://cengel.github.io/R-data-wrangling/)
  - Jenny Bryan, [Happy Git and GitHub for the
    useR"](https://happygitwithr.com/)
  - Yihui Xie et al., [“Blogdown: Creating Websites with R
    Markdown”](https://bookdown.org/yihui/blogdown/)
  - Max Kuhn, [“Applied Predictive
    Modeling”](http://appliedpredictivemodeling.com/)
  - Max Kuhn, [“Feature Engineering and Selection: A Practical Approach
    for Predictive Models”](https://bookdown.org/max/FES/)
  - Mark Sellors, [“Field Guide to the R
    Ecosystem”](https://fg2re.sellorm.com/)
  - Jennifer Bryan e Jim Hester, ["What They Forgot To Teach You About
    R](https://rstats.wtf)
  - Colin Fay, Vincent Guyader, Cervan Girard e Sébastien Rochette,
    [“Engineering Production-Grade Shiny
    Apps”](https://thinkr-open.github.io/building-shiny-apps-workflow/)

### Vídeos dos “Mestres”

  - Hadley Wickham, [“Whole
    Game”](https://www.youtube.com/watch?v=go5Au01Jrvs)
  - David Robinson,
    [“Tidytuesdays”](https://www.youtube.com/user/safe4democracy/videos)
  - Ben Stenhaug, [“Tidyverse Tutorial
    Playlist”](https://www.youtube.com/watch?v=lTTJPRwnONE&list=PLLxj8fULvXwGOf8uHlL4Tr62oXSB5k_in)

### Sites Úteis

  - Tidyverse
      - [Pacotes](https://www.tidyverse.org/packages/)
      - [Cheatsheets](https://www.rstudio.com/resources/cheatsheets/)
      - [Regular
        Expressions](https://stringr.tidyverse.org/articles/regular-expressions.html)
      - [TeachR](https://teachingr.com/)
  - Visualização
      - [Data Visualization in
        R](https://djnavarro.github.io/satrdayjoburg/),
        [slides](https://djnavarro.github.io/satrdayjoburg/slides)
      - [Galeria do
        ggplot2](https://www.r-graph-gallery.com/portfolio/ggplot2-package/)
      - [Yan Holz’s Classes](https://www.yan-holtz.com/teaching)
  - Markdown
      - [Pimp my Rmd](https://holtzy.github.io/Pimp-my-rmd/)
  - Pacotes R
      - [Leaderboard](https://www.rdocumentation.org/trends)
      - [Task Views](https://cran.r-project.org/web/views/)
      - [Awesome R](https://awesome-r.com/)
  - Blogs
      - [R-Bloggers](https://www.r-bloggers.com/)
      - Hadley Wickham, [“Como se tornar um Cientista de
        Dados”](https://gist.github.com/hadley/820f09ded347c62c2864)
  - Version Control
      - Abhishek Joshi, [“Tutorial
        Git”](https://medium.com/@abhishekj/an-intro-to-git-and-github-1a0e2c7e3a2f)
      - [Rstudio &
        Git](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN)
      - Karl Broman, [“Github
        tutorial”](http://kbroman.org/github_tutorial/)
      - Michael Freedman, [“Git
        Collaboration”](http://slides.com/michaelfreeman/git-collaboration)
