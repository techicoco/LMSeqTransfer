# SeqTransfer

Run task_affinity_estimation.py to calculate the task affinity between task a and task b.


Considering the characteristics of medical image segmentation tasks, we analyze the image and label similarity between tasks and compute the task affinity
score.

ICA.py is for the image characteristics similarity estimation.

OCA.py is for the object characteristics similarity estimation.

Determine the hyperparameters through Bayesian Optimization and set the edges in edge.py.


Construct the graph through clustering and new centroids setting up.
![image](https://github.com/techicoco/SeqTransfer/assets/151148523/20d14422-b906-44fc-8bbe-a7dcf22f9c8f)


Minimize the transfer cost to find the effective sequential transfer path p* as the solution to the optimal sequential transfer problem.
![image](https://github.com/techicoco/SeqTransfer/assets/151148523/7598b749-615a-446c-8698-c18e20960283)

