FROM mrcide/hiv-orderly:latest

# Add new packages here (in alphabetical order)
RUN install_packages --repo "https://mrc-ide.r-universe.dev"\
    countrycode \
    cowplot \
    dfertility \
    demogsurv \
    lwgeom \
    magrittr \
    Matrix \
    mgcv \
    moz.utils \
    mvtnorm \
    R6 \
    RcppEigen \
    rdhs \
    remotes \
    rlang \
    spdep \
    tidyverse \
    TMB \
    zoo

RUN install_remote mrc-ide/rrq@orderly1compat

WORKDIR /orderly
