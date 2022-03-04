FROM mrcide/hiv-orderly:latest

# Add new packages here (in alphabetical order)
RUN install_packages --repo "https://www.vaccineimpact.org/drat/" \
    countrycode \
    lwgeom \
    magrittr \
    Matrix \
    mgxv \
    mvtnorm \
    parallel \
    R6 \
    RcppEigen \
    rdhs \
    remotes \
    rlang \
    spdep \
    tidyverse \
    TMB \
    zoo

RUN install_remote \
    osymandius/dfertility

WORKDIR /orderly
