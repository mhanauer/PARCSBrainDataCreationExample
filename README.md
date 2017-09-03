# Make data for five participants with lengths 35, 38, 40, 42, and 44
# Need to make sure that you make the changes after the intervention has started
par1Con = as.data.frame(sample(c(10:30), round(5),0))
colnames(par1Con) = c("par1")
par1Inter = as.data.frame(sample(c(20:50), 35-5))
colnames(par1Inter) = c("par1")
par1 = as.data.frame(rbind(par1Con, par1Inter))
write.csv(par1, "par1.csv", row.names = FALSE)


par2Con = as.data.frame(sample(c(10:30), round(8),0))
colnames(par2Con) = c("par2")
par2Inter = as.data.frame(sample(c(20:50), 38-8))
colnames(par2Inter) = c("par2")
par2 = rbind(par2Con, par2Inter)
write.csv(par2, "par2.csv", row.names = FALSE)


par3Con = as.data.frame(sample(c(10:30), round(10),0))
colnames(par3Con) = c("par3")
par3Inter = as.data.frame(sample(c(20:50), 40-10))
colnames(par3Inter) = c("par3")
par3 = rbind(par3Con, par3Inter)
write.csv(par3, "par3.csv", row.names = FALSE)


par4Con = as.data.frame(sample(c(10:30), round(12),0))
colnames(par4Con) = c("par4")
par4Inter = as.data.frame(sample(c(20:50), 42-12))
colnames(par4Inter) = c("par4")
par4 = rbind(par4Con, par4Inter)
write.csv(par4, "par4.csv", row.names = FALSE)


par5Con = as.data.frame(sample(c(10:30), round(14),0))
colnames(par5Con) = c("par5")
par5Inter = as.data.frame(sample(c(20:50), 44-14))
colnames(par5Inter) = c("par5")
par5 = rbind(par5Con, par5Inter)
write.csv(par5, "par5.csv", row.names = FALSE)





