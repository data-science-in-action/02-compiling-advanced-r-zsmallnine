# 02-compiling-advanced-r-zsmallnine
02-compiling-advanced-r-zsmallnine created by GitHub Classroom
Problem1：Quitting from lines 223-235 (Introduction.Rmd) 
Error in cat(paste0(contributors$desc, collapse = ", ")) :

Solution：add encoding="UTF-8" in line 224 of introduction.rmd to fix it.

Problem2：package ‘emo’ is not available

Solution：install.packages("devtools")
devtools::install_github("hadley/emo")

problem3：The dbplyr package is required to communicate with database backends

solution：install.packages("dbplyr")

problem4：`ggbeeswarm` must be installed to use `type = "beeswarm"` option

solution：install.packages("ggbeeswarm ")

problem5：  Error 1 occurred building shared library.
Calls: local ... withVisible -> eval -> eval -> cppFunction -> sourceCpp

Solution：Add C:\Rtools\bin and c:\Rtools\mingw_32\bin to the path of the environment variable.
Problem6: LaTeX failed to compile _main.tex. See https://yihui.org/tinytex/r/#debugging for debugging tips.

Solution: Download MiKTeX, and install the package “xecjk” in MikTex Console

Problem7: Font inconsola not found

Solution: Download the font “inconsola”,then install it.
