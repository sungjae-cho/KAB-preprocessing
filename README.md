# KAB-preprocessing

Python and bash scripts to preprocess the [KAIST Audio Book Dataset](https://www.aihub.or.kr/open_data/21292) to be used for TTS training data

## Step 1. Renaming the original wav files

Set `rDirectory` as the wav directory in the KAIST Audio Book Dataset. Then, run cells in a row.


## Step 2. Trimming and resampling the wav files

Run the shell script below, which will take a long time.

```bash
sh 02_KAB.sh
```
