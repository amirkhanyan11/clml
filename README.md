# Installation 
```bash
git clone https://github.com/amirkhanyan11/clml.git /home/$USER/clml && cd /home/$USER/clml
chmod u+x ./clml
echo "export PATH=$PATH:/home/$USER/clml" >> ~/.zshrc
source ~/.zshrc
cd -
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
