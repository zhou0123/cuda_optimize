v1: 分块，双缓存，合并访存，shared memory，流水  
My gemm Performance= 6237.15 GFlop/s, Time= 0.344 msec, Size= 2147483648 Ops,   
CuBlas Performance= 6477.47 GFlop/s, Time= 0.332 msec, Size= 2147483648 Ops,  

v2: 解决shared memory conflict  
My gemm Performance= 6959.25 GFlop/s, Time= 0.309 msec, Size= 2147483648 Ops,  
CuBlas Performance= 6402.59 GFlop/s, Time= 0.335 msec, Size= 2147483648 Ops,  
