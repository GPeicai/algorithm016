学习笔记



不同路径二的状态转移方程：

dp[i][j] = 0    ，(i,j)上有障碍物

dp[i][j] = dp[i-1][j] + dp[i][j-1]  ，(i,j)上无障碍物






![f(i,j)=\left\{\begin{aligned}0&,&u(i,j)=0\\f(i-1,j)+f(i,j-1)&,&u(i,j)\neq0\end{aligned}\right. ](./p__f_i,_j__=_left_{_begin{aligned}_____0_&_,_&_u_i,_j__=_0______f_i_-_1,_j__+_f_i,_j_-_1__&_,_&_u_i,_j__neq_0_end{aligned}_right.__.png) 



毕业不是终点，掌握才是目的！
