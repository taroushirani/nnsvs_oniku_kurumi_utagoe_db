# nnsvs_oniku_kurumi_utagoe_db

[NNSVS](https://github.com/r9y9/nnsvs) recipe of Oniku Kurumi's singing voice database (56 songs).
Almost all codes are derived from [kiritan_singing](https://github.com/r9y9/kiritan_singing).

## Requirements
- nnsvs
- pysinsy
- nnmnkwii
- librosa
- soundfile
- scipy
- numpy
- tqdm
- jaconv

## How to use
Due to the licensing issue, this recipe does not include data nor helper scripts for downloading automatically. First of all, you need to get ONIKU_KURUMI_UTAGOE_DB.zip from [御丹宮くるみ Official WEB](http://onikuru.info/db-download/) (the terms of service are written in Japanese). Next, clone this repository and change `db_root` in `00-svs-world/run.sh` according to your environment. Then move to `00-svs-world` directory and run:

    run.sh --stage 0 --stop-stage 6

The directory structure made by this recipe is the same as kiritan_singing does.

## Sample code
- Jupyter Notebook coming soon (Google Colaboratory, comments are written in Japanese)

## Resources

- 御丹宮くるみ Official WEB: http://onikuru.info/db-download/ (Japanese)
