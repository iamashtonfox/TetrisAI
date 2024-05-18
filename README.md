# TO RUN THE AI:

#### 1) Copy the repo and cd into {wherever}/TetrisAI

## ON MAC:
#### 2) In a terminal at the top-level of the file, run: "javac -cp "./lib/*:." @tetris.srcs" to compile
#### 3) Run "java -cp "./lib/*:." edu.bu.tetris.Main -q src.pas.tetris.agents.TetrisQAgent -i ./params.model"

## ON WINDOWS/LINUX:
#### 2) In a terminal at the top-level of the file, run: "javac -cp "./lib/*;." @tetris.srcs" to compile
#### 3) Run "java -cp "./lib/*;." edu.bu.tetris.Main -q src.pas.tetris.agents.TetrisQAgent -i ./params.model"

## After compiling, you can also run "java -cp "./lib/*:." edu.bu.tetris.Main -h" to return a list of usable command-line flags for running the AI as well as a description of what they do.

## This model (contained in the params.model file) has been trained for ~15-20 hours and has reached a semi-decent state of being able to play tetris. I *could* train it longer to make it better, but I wont.
## Points in this game of Tetris are earned by performing line clears and T-spins.
