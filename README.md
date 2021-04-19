# cimemctcomps

Repo containt code from https://github.com/ESMCI/cime only the directories  
src/components/data_comps_mct  
src/components/stub_comps_mct  
src/components/xcpl_comps_mct  

Made with the following commands:

git filter-repo --path-rename src/components/data_comps_mct:components/data_comps --path-rename components/data_comps:components/data_comps  
git filter-repo --path-rename src/components/stub_comps_mct:components/stub_comps --path-rename components/stub_comps:components/stub_comps  
git filter-repo --path-rename src/components/xcpl_comps_mct:components/xcpl_comps --path-rename components/xcpl_comps:components/xcpl_comps  

git filter-repo --path components/data_comps --path components/stub_comps --path components/xcpl_comps  

git remote add mctcomps (this repo)  
git push mctcomps master

