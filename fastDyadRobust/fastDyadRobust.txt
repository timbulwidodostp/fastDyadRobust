# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fast computation of cluster-robust standard errors for dyadic data via multiway decomposition Use fastDyadRobust With (In) R Software
install.packages("remotes")
remotes::install_github("komatsuna4747/fastDyadRobust")
library("fastDyadRobust")
fastDyadRobust = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fastDyadRobust/main/fastDyadRobust/fastDyadRobust.csv",sep = ";")
# Estimation Fast computation of cluster-robust standard errors for dyadic data via multiway decomposition Use fastDyadRobust With (In) R Software
fastDyadRobust <- fastDyadRobust::feolsDyadRobust(dy ~ dx1 + dx2, fastDyadRobust, cluster = c("src", "dst"))
summary(fastDyadRobust)
# Fast computation of cluster-robust standard errors for dyadic data via multiway decomposition Use fastDyadRobust With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished