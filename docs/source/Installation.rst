Quick Install Guide
=============

echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
echo "Installation de la Version 5 des codes Dragon & Donjon"
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
mkdir Research && cd Research
wget http://www.polymtl.ca/merlin/downloads/version5_v5.0.6.tgz
tar xvfz version5_v5.0.6.tgz.tgz
cd Version5_beta_ev1803 && 
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
cd Utilib && ../script/install &&
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++" 
cd ../Ganlib && ../script/install && ./rganlib testgan1.x2m -w && 
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
cd ../Trivac && ../script/install && 
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
cd ../Dragon && ../script/install && 
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
cd ../Donjon && ../script/install &&
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
echo "Installation Done with Success"
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
echo "Draglib Installation"
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
cd Research && mkdir libraries && cd libraries && mkdir l_endian && cd l_endian
wget http://www.polymtl.ca/merlin/downloads/libraries/l_endian/draglibendfb7r1SHEM295.gz
# wget http://www.polymtl.ca/merlin/downloads/libraries/l_endian/draglibendfb8r0SHEM295.gz
# wget http://www.polymtl.ca/merlin/downloads/libraries/l_endian/draglibJeff3p3SHEM295.gz
wget http://www.polymtl.ca/merlin/downloads/libraries/l_endian/draglibJef2p2.gz
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
echo "Draglib Installation Done With Success"
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
echo "DRAGON-5 Installation Testing"
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
cd Research/Version5_beta_ev1803/Dragon/data && rdragon 
./rdragon tmacro.x2m -w && ./rdragon tdraglib.x2m -w
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
echo "DRAGON-5 Installation Testing Done with Success"
echo "++++++++++++++++++++++++++++++++++++++++++++++++++++++"
