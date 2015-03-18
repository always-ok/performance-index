# performance-index
This is the implementation of PID controllers perfomrance assessment. 
Run pid_opt.m and it will automatically run the model, and give the performance index and tuned PID controller parameters. This file will first identify model and then tune PID controller parameters.
After running pid_opt.m, run vpid.m which uses newton's iterative method to achieve the performance index.
