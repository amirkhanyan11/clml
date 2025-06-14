# Installation 
```bash
cd /home/$USER
mkdir -p clml
git clone https://github.com/amirkhanyan11/clml.git __tmp_
mv __tmp_/clml /home/$USER/clml
rm -rf __tmp_
cd ./clml
chmod u+x clml
echo "export PATH=$PATH:/home/$USER/clml" >> ~/.zshrc
source ~/.zshrc
```

## How to use
```bash
clml Foo
```
This will add Foo header and cpp files in your inc and src directories 
```
.
├── inc
│   └── Foo.hpp
├── src
│   └── Foo.cpp
└── main.cpp
```
