'''bash
cd /home/$USER
mkdir -p scripts
git clone https://github.com/amirkhanyan11/clml.git __tmp
mv __tmp/clml /home/$USER/scripts/clml
cd ./scripts
chmod u+x clml
echo "export PATH=$PATH:/home/$USER/scripts >> ~/.zshrc"
source ~/.zshrc
'''