# nnsvs_oniku_kurumi_utagoe_db

[NNSVS](https://github.com/r9y9/nnsvs) recipe of Oniku Kurumi Utagoe Database (56 songs).
Almost all codes are derived from [kiritan_singing](https://github.com/r9y9/kiritan_singing).

## Important Notice
**The recipe of Oniku Kurumi Utagoe Database is merged into NNSVS repository on 04 Nov 2020.  Please use the official one.**

This repository is maintained only for the experimental purpose.

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
- pyyaml

## How to use
Due to the licensing issue, this recipe does not include data nor helper scripts for downloading automatically. First of all, you need to get ONIKU_KURUMI_UTAGOE_DB.zip from [御丹宮くるみ Official WEB](http://onikuru.info/db-download/) (the terms of service are written in Japanese). Next, clone this repository and change `db_root` in `00-svs-world/config.yaml` according to your environment. Then move to `00-svs-world` directory and run:

    run.sh --stage 0 --stop-stage 6

The directory structure made by this recipe is the same as kiritan_singing does.

## Sample code
- [Jupyter Notebook(Using the official recipe)](https://gist.github.com/taroushirani/8eae48b2a88c7cedbfa9b4d773fc1fff) (Google Colaboratory, comments are written in Japanese)
- [Jupyter Notebook(Older version)](https://gist.github.com/taroushirani/36b03699b7184595fb86cefb1dfe5285) (Google Colaboratory, comments are written in Japanese)

## Resources

- 御丹宮くるみ Official WEB: http://onikuru.info/db-download/ (Japanese)
