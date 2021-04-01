Bootstrap: docker
From: fermilab/fnal-wn-sl7

%post
   yum install -y freetype-devel git gitflow wget curl-devel redhat-lsb-core openssh-clients curl-devel libxml2-devel mesa-libGLU-devel  libSM-devel openssl-devel
  mkdir /products
  wget http://scisoft.fnal.gov/scisoft/bundles/tools/pullProducts
  chmod +x pullProducts
  ./pullProducts /products slf7 uboone-v09_00_00 s97-e19 prof
  rm *.tar.bz2

%environment
