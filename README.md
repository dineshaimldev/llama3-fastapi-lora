# llama3-fastapi-lora

LoRA fine-tuning, evaluation, and FastAPI serving workflows for Llama 3.

## Repository layout

```text
llama3-fastapi-lora/
├── data/          # prep scripts
├── train/         # training script
├── eval/          # evalplus + fastapi_bench
├── notebooks/     # Kaggle/Colab runners
└── README.md
```

### Directory descriptions

- `data/`: Dataset preparation and preprocessing scripts.
- `train/`: Model training and LoRA fine-tuning scripts.
- `eval/`: Evaluation workflows, including EvalPlus and FastAPI benchmarking utilities.
- `notebooks/`: Notebook-based runners and experiments (for example Kaggle/Colab).
