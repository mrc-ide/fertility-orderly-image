FROM mrcide/hiv-orderly:latest

# Add new packages here (in alphabetical order)
RUN install_packages --repo "https://www.vaccineimpact.org/drat/" \
    countrycode \
    cowplot \
    lwgeom \
    magrittr \
    Matrix \
    mgcv \
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

RUN install_remote \
    osymandius/dfertility \
    osymandius/moz.utils \
    mrc-ide/demogsurv

WORKDIR /orderly
