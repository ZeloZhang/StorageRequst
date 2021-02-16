# StorageRequst

We started from SnowStorm simulation dataset:
numu: /data/sim/IceCube/2016/filtered/level2/neutrino-generator/214[30-32]
nue: /data/sim/IceCube/2016/filtered/level2/neutrino-generator/214[68-70]
nutau: /data/sim/IceCube/2016/filtered/level2/neutrino-generator/214[71-73]

We are going to process them through cascade level3 filters and cascade finallevel filters, the out put files will be stored at:
level3: /data/ana/analyses/diffuse/cascades/sim/filtered/cascade_level3/{datasetID}/
finallevel: /data/ana/analyses/diffuse/cascades/sim/filtered/cascade_finallevel/{datasetID}/

We are going to keep the directory structure in /data/sim, which means we are going to create subdirectory such as {datasetID}/0000000-0000999/ for every thousand files. And for finallevel, in each subdirectory ({datasetID}/0000000-0000999/ and so on), we are going to create three subdirectories, which are final_cascade, final_hybrid, final_muon.
