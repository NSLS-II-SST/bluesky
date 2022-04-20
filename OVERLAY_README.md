#RSOX Fork 
To install or update overlay from github, as operator account: 

```bash
conda activate $BS_ENV
pip install git+https://github.com/NSLS-II-SST/bluesky --prefix /nsls2/data/sst1/rsoxs/shared/config/bluesky_overlay/2022-2.1-py39-tiled --upgrade -I --no-dependencies
```