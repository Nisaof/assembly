# CSE232 Term Project
cd /Users/nisaoff/Desktop/assembly
make clean && make
./assembler test_main.asm && ./assembler sub.asm && ./assembler data.asm
./linker_exec exp test_main.o test_main.t sub.o sub.t data.o data.t
./loader exp.exe exp.t

