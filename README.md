# GShare
The program implements GShare branch predictor.

## Code and Execution
The `main()` is defined in `gshare_prediction.c`. To run the application, simply execute (on Windows)
```
.\gshare_prediction.exe
```

## Results
The predictions for the gcc-1k and gcc-10M trace files are reported in the aprropriately named prediction files.

## References
* The documentation for the trace parser and the gcc-1k and gcc-10M trace files can be found [here](https://acg.cis.upenn.edu/milom/cis501-Fall10/traces/trace-format.html).
* You can read about GShare [here](https://www.hpl.hp.com/techreports/Compaq-DEC/WRL-TN-36.pdf).
