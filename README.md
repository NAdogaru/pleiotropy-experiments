# epistasis-experiments

## About
In order to run the experiments, at least **JDK 21** is required: if you are using a Unix based system, you can install one easily using [sdkman](https://sdkman.io/).
The Java archive (June 2025) in this repository is based on the following frameworks:
- [JGEA](https://github.com/ericmedvet/jgea)
- [2D-robot-evolution](https://github.com/ericmedvet/2d-robot-evolution)

## Usage
An experiment can be started by invoking:
```shell
java -jar ./robotevo2d.main-1.5.1-SNAPSHOT-jar-with-dependencies.jar --expFile <exp-file> --nOfThreads <nt>
```
where `<exp-file>` is the path to a file with an **experiment description** and `<nt>` is the **number of threads** to be used for running the experiment. For the number of threads `<nt>`, it is suggested to use a number $n$ lower or equal to the number of cores on the machine you run the experiment on.

### Available Experiment Files
You can find epistasis experiment description files in the following folders:

- `robot-cleaner-examples/`
- `vsr-examples/`