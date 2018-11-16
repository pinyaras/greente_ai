Power-Aware Traffic Engineering with Deep Reinforcement Learning


Power-aware traffic engineering via coordinated sleeping is often formulated into MIP problems, which are generally NP-Hard thus the computation time does not scale for large networks, causing delayed control decision making for highly dynamic networks. Motivated by recent advances in deep reinforcement learning (RL), we consider building intelligent systems that learn to adaptively change router's power state according to traffic dynamics. The forward propagation property of neural networks can greatly speedup power on/off decision making. Typically, conducting RL requires a learning agent to iteratively explore and perform the ``good'' actions based on the feedbacks from the environment. However, state-of-the-art monitoring techniques fail to achieve timely network-wide feedbacks. By coupling recent techniques of SDN (for performing actions to the environment) and INT (for collecting environment feedbacks), we craft GreenTE.ai, a closed-loop control system. Based on the system, we propose novel techniques to enhance the learning ability. Compared with classic approaches, our proposal is generalized, time-efficient and environment-adaptive. It generates a reasonable power saving action within 276ms considering both energy efficiency and network load balancing.
