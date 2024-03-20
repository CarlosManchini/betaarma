library(devtools)
install_github("carlosmanchini/betaarma")

library(betaarma)

help("simu.barma")
(y <- simu.barma(100, phi=c(.5), theta=1, prec=120, lambda=1)) #link

help("fit.barma")
fit.barma(y, ar=1:2, ma=1)
