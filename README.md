# InSituQuantification_Cellpose
Combines an ImageJ friendly version of cellpose (see other repository), napari and plotly to perform per nucleus in situ quantification and co-expression analysis.

ColocalizationAnalysis_aukpt1 and pt2 take measurements files from ImageJ (.csv) containing quantified nuclear intensities for different channels and normalize, filter, and 
threshold them for doing co-expression analysis.  Selection of filters is made easy with interactive plotly/napari allowing one to choose a point and see the original data.

ColocalizationAnalysis_aukpt3 does similar but with a 3rd channel.

ColocalizationAnalysis_af2345 does much the same.

The .ijm files take the original .nd2 files, pre-process, and then use cellpose to find the nucleii and quantify the signal in the in situ channels.
