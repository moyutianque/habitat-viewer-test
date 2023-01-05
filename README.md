# habitat-viewer-test
Only viewer.py has python code and it is mostly from official habitat-sim repo. The depth overlapping issue happens at line 467 when calling ```self.sim.get_sensor_observations()```

Please find the testing data and tmp testing output from [google drive](https://drive.google.com/file/d/1eLMQZ5wclMkq2EUvMSpzJkVzSMmFoKQN/view?usp=sharing)

To reproduce, please run

```bash
sh run_my_inter_replica.sh
```
