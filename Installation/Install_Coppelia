wget -P /tmp https://www.coppeliarobotics.com/files/CoppeliaSim_Edu_V4_5_1_rev4_Ubuntu20_04.tar.xz
cd /tmp && tar -xvf CoppeliaSim_Edu_V4_5_1_rev4_Ubuntu20_04.tar.xz
mv CoppeliaSim_Edu_V4_5_1_rev4_Ubuntu20_04 ~/

echo 'export COPPELIASIM_ROOT_DIR="$HOME/CoppeliaSim_Edu_V4_5_1_rev4_Ubuntu20_04"' >> ~/.bashrc && source ~/.bashrc
echo 'alias coppelia="$COPPELIASIM_ROOT_DIR/coppeliaSim.sh"' >> ~/.bashrc && source ~/.bashrc

sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev

coppelia
