## VSP to SSP 
#### Vladimir Kazei, Oleg Ovcharenko, Yan Yang (KAUST, 2019)


This program redatums vertical seismic profile (VSP) data to virtual surface seismic profile (SSP) data by crosscorrelation of the first order free-surface multiples from one shot at the surface (virtual receiver) with direct waves from another shot (shot), which follows from interferometric principles. Virtual receivers are created at the surface at the possitions of actual sources (e.g. Schuster, https://doi.org/10.1017/CBO9780511581557.005)

run 

"vsp2ssp.m" 

to create the redatumed data that is visualised below: 

![](virtualData.gif)

Green line, dependent on the redatumed shot position, estimates the ray coverage. If the virtual receiver is further than this line away from the well, there exists a ray path of the firs order multiple hitting the well, redatumed source and virtual receiver at the same time.

vladimir.kazei@kaust.edu.sa
