1. Model first training to 23K samples then 70K the 70K checkpoint used to train current model.
2. Dataset - LinNY-DLM/train_dataset
3. Training set size: 720000
4. Validation set size: 1000
5. per_device_train_batch_size = 12
6. gradient_accumulation_steps = 8
7. max_steps = 313
8. Total training samples: 30048
9. Samples per step: 96
10. learning_rate = 3e-4
11. optim = "adamw_8bit"
12. lr_scheduler_type = "linear"
13. Final Training Loss = 0.38
14. Final Validation Loss = 0.47
