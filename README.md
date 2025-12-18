# LDMS-google-traces-spark

# Data
Sample data to use: 150 from 154 for job_events, task_constraints, task_events, task_usage

# Tasks 
**1. What is the distribution of the machines according to their CPU capacity? Can you explain (motivate) it?** 
  
  At timestamp "0" there are 12,477 machines initially started. The CPU capacity of the machines can be grouped into three types of capacity volumes   (0.25, 0.5 and 1). 1% of the the machines use 0.25 CPUs, 6% 1.0 CPUs and 93% were using 0.5 CPUs when initally started.

**2. What is the percentage of computational power lost due to maintenance (a machine went
offline and reconnected later)? The computational power is proportional to both the CPU capacity and the unavailabil-
ity period of machines.** (Masa)

**3. Is there a class of machines, according to their CPU, that stands out with a higher mainte-
nance rate, as compared to other classes ?** (Masa)

**4. What is the distribution of the number of jobs/tasks per scheduling class? Comment on the
results.** (Lena)

**5. Would you qualify the percentage of jobs/tasks that got killed or evicted as important?** (Lena)

**6. Do tasks with a low scheduling class have a higher probability of being evicted?**

**7. In general, do tasks from the same job run on the same machine? Comment on the observed
locality strategy and its pros and cons.**

**8. Are the tasks that request the more resources the one that consume the more resources?**

**9. Can we observe correlations between peaks of high resource consumption on some machines and task eviction events?**

**10. How often does it happen that the resources of a machine are over-committed?**

11. Your original question 1. Motivate the originality of the question.
    
12. Your original question 2. Motivate the originality of the question.
