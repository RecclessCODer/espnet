<!-- Generated by scripts/utils/show_asr_result.sh -->
# mic=ihm: Updated results: +Specaug +Transformer-LM
## Environments
- date: `Thu Mar 18 03:15:25 UTC 2021`
- python version: `3.8.8 (default, Feb 24 2021, 21:46:12)  [GCC 7.3.0]`
- espnet version: `espnet 0.9.8`
- pytorch version: `pytorch 1.8.0`
- Git hash: `106acf3e84fc1d466d6c07c7914847a169f9713c`
  - Commit date: `Thu Mar 18 04:22:14 2021 +0000`

## Transformer LM
- ASR config: [conf/tuning/train_asr_transformer4.yaml](conf/tuning/train_asr_transformer4.yaml)
- LM config: [conf/tuning/train_lm_transformer2.yaml](conf/tuning/train_lm_transformer2.yaml)
- Decode config: [conf/tuning/decode_transformer2.yaml](conf/tuning/decode_transformer2.yaml)
- Pretrained model: [https://zenodo.org/record/4615756](https://zenodo.org/record/4615756)

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_transformer2_lm_lm_train_lm_transformer2_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_dev|13057|94802|83.5|12.0|4.6|2.6|19.1|51.9|
|decode_transformer2_lm_lm_train_lm_transformer2_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_eval|12643|89666|83.8|12.0|4.2|2.2|18.3|49.4|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_transformer2_lm_lm_train_lm_transformer2_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_dev|13057|451641|91.4|3.7|5.0|2.9|11.5|51.9|
|decode_transformer2_lm_lm_train_lm_transformer2_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_eval|12643|432094|91.9|3.7|4.4|2.6|10.7|49.4|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_transformer2_lm_lm_train_lm_transformer2_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_dev|13057|254909|87.5|6.7|5.8|2.6|15.1|51.9|
|decode_transformer2_lm_lm_train_lm_transformer2_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_eval|12643|243330|88.5|6.4|5.1|2.5|14.0|49.4|

## Without LM
- ASR config: [conf/tuning/train_asr_transformer4.yaml](conf/tuning/train_asr_transformer4.yaml)
- Decode config: [conf/tuning/decode_transformer2.yaml](conf/tuning/decode_transformer2.yaml)

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_transformer2_asr_model_valid.acc.ave/ihm_dev|13057|94802|83.4|12.9|3.7|3.2|19.8|52.7|
|decode_transformer2_asr_model_valid.acc.ave/ihm_eval|12643|89666|83.6|13.0|3.4|2.7|19.1|50.3|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_transformer2_asr_model_valid.acc.ave/ihm_dev|13057|451641|91.8|3.8|4.4|3.2|11.4|52.7|
|decode_transformer2_asr_model_valid.acc.ave/ihm_eval|12643|432094|92.2|3.8|4.0|2.9|10.7|50.3|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_transformer2_asr_model_valid.acc.ave/ihm_dev|13057|254909|87.7|6.9|5.4|2.9|15.2|52.7|
|decode_transformer2_asr_model_valid.acc.ave/ihm_eval|12643|243330|88.4|6.8|4.8|2.7|14.2|50.3|


# RESULTS on Dec 28, 2020
## Environments
- date: `Mon Dec 28 16:38:46 EST 2020`
- python version: `3.8.5 (default, Sep  4 2020, 07:30:14)  [GCC 7.3.0]`
- espnet version: `espnet 0.9.6`
- pytorch version: `pytorch 1.4.0`
- Git hash: `844b2f2ee9c7f9da1881447a6e60b6fe6e05e4df`
  - Commit date: `Mon Dec 28 13:00:35 2020 -0500`
- Pretrained model: https://zenodo.org/record/4396314

## asr_train_asr_e85_raw_en_bpe100_optim_conflr5.0_sp
### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_ctc_weight0.2_lm_weight0.2_lm_lm_train_lm_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_dev|13057|94802|73.8|18.6|7.6|3.6|29.8|62.6|
|decode_asr_ctc_weight0.2_lm_weight0.2_lm_lm_train_lm_en_bpe100_valid.loss.ave_asr_model_valid.acc.ave/ihm_eval|12643|89666|73.5|19.8|6.7|3.5|30.0|60.1|

# RESULTS
## Environments
- date: `Mon Mar  2 21:48:39 EST 2020`
- python version: `3.7.6 (default, Jan  8 2020, 19:59:22)  [GCC 7.3.0]`
- espnet version: `espnet 0.6.0`
- pytorch version: `pytorch 1.4.0`
- Git hash: ``
  - Commit date: ``

## asr_train_raw_char
### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_ihm_devdecode_lm_valid.loss.best_asr_model_valid.acc.best|12900|94753|67.6|22.7|9.7|4.0|36.4|70.1|
|decode_ihm_evaldecode_lm_valid.loss.best_asr_model_valid.acc.best|12479|89496|65.0|25.6|9.4|3.9|38.9|67.7|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_ihm_devdecode_lm_valid.loss.best_asr_model_valid.acc.best|12900|451698|80.4|7.6|11.9|3.9|23.5|70.1|
|decode_ihm_evaldecode_lm_valid.loss.best_asr_model_valid.acc.best|12479|431533|79.2|8.9|11.9|4.1|24.9|67.7|

