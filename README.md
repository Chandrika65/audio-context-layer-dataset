# Audio Context Layer - Audio QA Dataset

## Dataset Description

This dataset contains audio question-answer pairs for the Audio Context Layer assignment.

The dataset is divided into three splits:

- train.csv - 12 samples
- validation.csv - 4 samples
- test.csv - 4 samples

## Data Format

Each CSV file contains these columns:

| Column | Description |
|---|---|
| audio_file | Name of the audio file |
| question | Natural language question |
| question_type | Type of question |
| answer | Expected answer |

## Question Types

- perceptual
- counting
- temporal
- reasoning

## Audio

The dataset uses a synthetic demonstration audio file containing:

- Clapping
- Knocking
- Speech

Event sequence:

Clap → Clap → Clap → Knock → Knock → Speech → Clap → Knock

Therefore:

- Claps: 4
- Knocks: 3
- Speech events: 1
- Total events: 8

## Dataset Split

| Split | Samples |
|---|---:|
| Train | 12 |
| Validation | 4 |
| Test | 4 |

Each split contains examples from the four question types.

## Note

This is a small synthetic/demo dataset created for the Audio Context Layer assignment. It is intended to demonstrate the audio question-answering pipeline.
