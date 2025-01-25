# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# BerG regression for count data with underdispersion, equidispersion, or overdispersion and possibly with heavy tail Use bergreg With (In) R Software
install.packages("remotes")
remotes::install_github("rdmatheus/bergreg")
library("bergreg")
bergreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bergreg/main/bergreg/bergreg.csv",sep = ";")
# Estimation BerG regression for count data with underdispersion, equidispersion, or overdispersion and possibly with heavy tail Use bergreg With (In) R Software
Bergreg <- bergreg(Dependen ~ Independen_1 + Independen_2 | Independen_1 + Independen_2, data = bergreg)
summary(Bergreg)

# A BerG regression for count data with underdispersion, equidispersion, or overdispersion and possibly with heavy tail Use bergreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished