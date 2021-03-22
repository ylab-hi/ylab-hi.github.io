# Yang Lab

Our website is based on the open source templates forked from [Dr. Stephan Sanders](https://github.com/sanderslab/sanderslab.github.io). Earlier version designed and shared by the labs of [D. Allan Drummond](http://www.allanlab.org/aboutwebsite.html) and [Trevor Bedford](http://bedford.io/misc/about/). We downloaded source codes from their repository and modified our contents based on shared templates. We greatly thank for Stephan, Allan and Trevor for allowing reuse of their codebase. 

If you use conda, these will help you start build for your own
- Step1: Fork [https://github.com/ylab-hi/ylab-hi.github.io](https://github.com/ylab-hi/ylab-hi.github.io)
- Step2: on you forked git, click setting and get your own repository name
- Step3: Under linux
```
git clone https://github.com/**yourid**/ylab-hi.github.io
#conda create -n iobuild python=3.8 ruby=2.6.3
#conda activate iobuild
conda env create -f .condaenv.xml
conda activate iobuild
gem install bundle
bundle install
#local debug, would rebuild automatically everytime you changed a file
sh start.sh
#after confirmation of the changes you want
bundle exec jekyll build
git commit "update" && git push
sh script/deploy
#Note it might take a few minutes for github.io to update, be patient
```

The website is deployed using [GitHub Pages](https://ylab-hi.github.io) and the source code is available on [GitHub](https://github.com/ylab-hi). Please feel free to reuse this code (making sure to cite the Sanders lab, Bedford lab and Drummond lab as the original sources of the lab website template).
