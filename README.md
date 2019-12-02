# Quantum-Multi-collision-Problem
Implementation of quantum multi-collision algorithm on Qiskit.
# Abstract
<!-- Describe your idea in 3 or 4 sentences -->
Finding collisions for a many to one mapping is a fundamental problem in cryptography. In this project, we would implement quantum multi-collision algorithm on Qiskit. Rather then simply applying Grover search, which gives a quadratically speed up, we would like to realize more efficient algorithms to attack the multi-collision problem.
# Description <!-- ⚠️ Optional. Remove this section if not needed -->
<!-- A more detailed description of the idea -->
The multi-collision problem states as follows: For given finite sets <a href="https://www.codecogs.com/eqnedit.php?latex=X" target="_blank"><img src="https://latex.codecogs.com/gif.latex?X" title="X" /></a> and <a href="https://www.codecogs.com/eqnedit.php?latex=Y" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Y" title="Y" /></a> with &nbsp; <a href="https://www.codecogs.com/eqnedit.php?latex=\left&space;|&space;Y&space;\right&space;|&space;=&space;N" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\left&space;|&space;Y&space;\right&space;|&space;=&space;N" title="\left | Y \right | = N" /></a>, and a function <a href="https://www.codecogs.com/eqnedit.php?latex=F:X\rightarrow&space;Y" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F:X\rightarrow&space;Y" title="F:X\rightarrow Y" /></a>, the s-collision finding problem is to find a set of distinct inputs <a href="https://www.codecogs.com/eqnedit.php?latex=x_1,&space;x_2,...,x_s" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x_1,&space;x_2,...,x_s" title="x_1, x_2,...,x_s" /></a> such that 
<p align='center'>
<a href="https://www.codecogs.com/eqnedit.php?latex=F(x_1)=F(x_2)=...=F(x_s)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F(x_1)=F(x_2)=...=F(x_s)" title="F(x_1)=F(x_2)=...=F(x_s)" /></a>.
</p>
For s=2 cases, the problem corresponds to the well-known "birthday paradox", which shows that the probability to find two people sharing the same birthday in a banquet is much more larger than one may intuitively think. In fact, the probability reaches 50% with only 23 people in a room.
</br>
One can use Grover search to solve the multi-collision problem for <a href="https://www.codecogs.com/eqnedit.php?latex=O(N^{1/2})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?O(N^{1/2})" title="O(N^{1/2})" /></a> expected evaluations. Moreover, the optimized algorithm so called "BHT algorithm" gives <a href="https://www.codecogs.com/eqnedit.php?latex=O(N^{1/3})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?O(N^{1/3})" title="O(N^{1/3})" /></a> for s=2 and any arbitrary function <a href="https://www.codecogs.com/eqnedit.php?latex=F" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F" title="F" /></a> (<a href="https://arxiv.org/abs/quant-ph/9705002" target="_blank" >arXiv:quant-ph/9705002</a>). Recently, some algorithms have been proposed with higher efficiency or for more complicated conditions such as s>2 and different features of <a href="https://www.codecogs.com/eqnedit.php?latex=F" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F" title="F" /></a> (<a href="https://arxiv.org/abs/1911.02822" target="_blank" >arXiv:1911.02822</a>). In this project, we would look into the algorithms already proposed and try to do the implementation on Qiskit. Then based on that, we optimize the algorithm as far as possible during the hackathon.

# Members
<!-- up to 5 members in the team. You don't need them when you submit the idea, but they need to be there when the hackathon starts. - @githubhandle - Slack: `@slackhandle` email: `example@example.com` -->

 - @abtmy - Slack: `@Tomoya Abe`
 - @r1t0o0 - Slack: `@Rito`
 - @ace314 - Slack: `@Che Chiang`
 - @BOBO1997 `@Yang Bo`
 - @starktech23 `@Samanvay Sharma`
 - Qiskit Coach: @atilag  

# Deliverable
<!-- A paper, a mobile app, a Terra module, etc -->

# GitHub repo
<!-- A link to the github repo where the project will be developed -->
