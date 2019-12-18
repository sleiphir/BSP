Compile & Execute:
```bash
g++ -c main.cc Dungeon.cc Frame.cc && g++ main.o Dungeon.o Frame.o  -o sfml-app -lsfml-graphics -lsfml-window -lsfml-system && ./sfml-app
```

## Current state
_Paths are being generated between the farthest siblings in the binary tree._
Next step is to randomly generate those paths so not all siblings are connected and generate other paths between non-siblings to connect everything together
