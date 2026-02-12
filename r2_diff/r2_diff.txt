# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# r2_diff function Use r2_diff (r2redux) With (In) R Software
install.packages("r2redux")
library("r2redux")
# Estimation r2_diff function Use r2_diff (r2redux) With (In) R Software
r2_diff = read.csv("https://raw.githubusercontent.com/timbulwidodostp/r2_diff/main/r2_diff/r2_diff.csv", sep = ";")
nv = length(r2_diff$V1)
v1 = c(1)
v2 = c(2)
r2_diff = r2_diff(r2_diff, v1, v2, nv)
r2_diff
# r2_diff function Use r2_diff (r2redux) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished