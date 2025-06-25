# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Gaussian location-scale regression Use lmls With (In) R Software
install.packages("lmls")
library("lmls")
lmls = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lmls/main/lmls/lmls.csv",sep = ";")
# Estimation Gaussian location-scale regression Use lmls With (In) R Software
lmls <- lmls(y ~ poly(x, 2), ~ x, data = lmls)
summary(lmls)
# Gaussian location-scale regression Use lmls With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished