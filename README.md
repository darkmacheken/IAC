# IAC
Introduction to Computer Architecture Project.

## Introduction
The project consists in the developing of a game with the same mechanics of 
[Flappy Bird](https://en.wikipedia.org/wiki/Flappy_Bird).
The project was developed using the assembly language from the [P3 processor](http://algos.inesc-id.pt/arq-comp/?Material_Did%C3%A1tico___Processador_P3).

The rules and instructions of the game are in the statement under **/docs**.
## Requirements
To run the project you need the P3 simulator:
- P3 Simulator ([p3sim](http://algos.inesc-id.pt/arq-comp/userfiles/downloads/p3sim.jar) or 
[P3JS](https://p3js.goncalomb.com/))
- Java 7+ (for the [p3sim](http://algos.inesc-id.pt/arq-comp/userfiles/downloads/p3sim.jar))

## How to run
### P3JS
To run the project in this simulator, you just need go to the [P3JS](https://p3js.goncalomb.com/) site,
paste the source code to the editor and click "Assemble and Run".

### p3sim
To run the project, you need first to compile the code to binary. Use the official assembler that
can be download from the [P3 processor](http://algos.inesc-id.pt/arq-comp/?Material_Did%C3%A1tico___Processador_P3)
page. To start the simulator you need to run the following command:

```
    java -jar p3sim.jar
```

Load the binary that was the output of the assembler and click run.
