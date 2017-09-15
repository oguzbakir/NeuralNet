# NeuralNet
## How to use it?
All you need is a input file. To create a input file execute following commands:
```
g++ generator.cpp -o generate.o
./generate.o > trainingData.txt 
```
After creating input file you can modify learning rate(core.cpp:130) and momentum(core.cpp:131)
To run network, execute following commands:
```
g++ core.cpp -o network.o
./network.o
```
