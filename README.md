# NMT_hyperParam

The Folder /OpenNMT-py, contains the implementation of: https://github.com/OpenNMT/OpenNMT-py. It was not altered in any way.
The Dataset we used for training can be found at /dataset. 

Or can be downloaded the gollowing way: 
wget http://www.quest.dcs.shef.ac.uk/wmt16_files_mmt/training.tar.gz &&  tar -xf training.tar.gz -C data/multi30k && rm training.tar.gz
wget http://www.quest.dcs.shef.ac.uk/wmt16_files_mmt/validation.tar.gz && tar -xf validation.tar.gz -C data/multi30k && rm validation.tar.gz
wget http://www.quest.dcs.shef.ac.uk/wmt17_files_mmt/mmt_task1_test2016.tar.gz && tar -xf mmt_task1_test2016.tar.gz -C data/multi30k && rm mmt_task1_test2016.tar.gz

The model can be trained by running: 

All available training options can be found at: 
http://opennmt.net/OpenNMT-py/options/train.html


