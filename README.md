# asr-wer
Simple Single File C++ Implementation for Word Error Rate (WER) & Sentence Error Rate (SER) 
Calculation for Evaluating Automatic Speech Recognition.

# Compilation
```g++ calculate-wer.cpp -o wer```

# usage
```wer <org ref file transcript> <asr result file transcript>```
  
# Example

```
./wer ref.txt asr.txt
FINAL WER = 0.375622   FINAL SER = 0.79798
```
