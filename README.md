# For Jiaxing

First, change the default db_bench path in the default.ini

then, use `sudo` model to run the test file by `python3 motivation_bootstrap.py`

if there is any missing package, use `pip3` to install it.

## something you should change before running

there is a `/home/jinghuan/huawei/result` dir in the *motivation_bootstrap.py*, change it into any directory you want to store the result data, remember, since you are running in the sudo model, any missing directory will be created.


## task and result saving

For each experiment group, you should write a python script and a json config file. While running the script, a newly finished task will be stored in the target `result_dir`, while others will be stored in the task queue. So you can save the checkpoint for one experiment set, and next time you run the same script, all tasks stored in result dir will be skipped.

## Result visualization

You can use this [link](https://github.com/supermt/hmm_lsm) to get some useful utils to do the machine learning analysis and result visualization

# multi-task set

You can see the file `rate_limiting_motivation.py` to see how to setup multi options for the experiment sets.  
