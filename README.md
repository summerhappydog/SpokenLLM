# SpeechLLM-QA: Question-Conditioned Audio Compression for End-to-End Spoken Question Answering

This repository contains the code for my Master's thesis on end-to-end Spoken Question Answering.

The project investigates whether audio representations for Spoken QA can be compressed more effectively by conditioning the compression process on the input question. The experiments compare transcript-based pipeline baselines with several end-to-end audio-language model variants using Whisper audio embeddings and a Mistral-based language model.

Model checkpoints are available on Hugging Face:

https://huggingface.co/Summerhappydog/SpokenLLM

All evaluation results reported in the thesis were obtained using the epoch-10 checkpoints.

## Repository Structure

* `src/`: model definitions, training, inference, and evaluation code
* `scripts/`: scripts for running experiments
* `requirements.txt`: Python dependencies

## Notes

The code was developed for the experiments reported in the thesis. It is intended mainly for reproducibility and reference.