mkdir ext
cd ext
git clone https://github.com/wjakob/nanobind.git
cd nanobind
git submodule update --init --recursive
cd ../../
cmake -S . -B build

cmake --build build