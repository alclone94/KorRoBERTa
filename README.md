# KorRoBERTa

Example of Korean RoBERTa training with Huggingface Transformers

Pretrained RoBERTa model at bert/senti_base_model/100000step has pre-trained with Korean corpus(https://corpus.korean.go.kr/)

You can get sentiement analysis dataset at https://github.com/e9t/nsmc

## Quick start

### RoBERTa pretraining
step 1.
`bash ./script/data_preprocess_example.sh`

step 2.
`bash ./script/pretrain_example.sh`

### NSMC

training
`bash ./script/nsmc_train_example.sh`

evaluating
`bash ./script/nsmc_eval_example.sh`
