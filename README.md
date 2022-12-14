# Game-Theory---Job-Scheduling
This project is a game theory research aid. First, jobs are being scheduled to the machines, than rounding throughout all jobs and offering each job to switch to another machine. The simulator stops after reaching Nash Equilibrium. 

**Version 7.0:

This simulator demonstrates the job scheduling problem.
Where each job is a selfish agent and inspires to improve its completion time.
Simulator’s structure:
	1.	A job has a processing time.
	2.	A machine has speed in which it processes the jobs allocated to it, where 1.0 is the unit speed.
	3.	A machine has a policy and it follows it when being allocated with jobs. The different policies are:
	a.	0 – add last.
	b.	1 – add first.
	c.	2 – keeping the jobs scheduled onto the machine sorted from small PT to large PT. 
	d.	3 – keeping the jobs scheduled onto the machine sorted from small PT to large PT. 
	e.	4 – arbitrary priority list.
Input formats:
	1.	Command line arguments – number of machines, policy, speed, number of jobs, round type.
		Both policy and speed are similar o each machine. The PT of each job is random the initial scheduling is
		being done according to the machines’ policy. In addition, it is not possible to invoke policy 4 to the
		machines via this input format.
	2.	File format 1 – a text file in the format of “file format 1” attached with his project.
		The file format (1 / 2), round type, number of machines, number of jobs, a speed and a policy for each machine,
		a processing time for each job. The initial scheduling is being done according to the machines’ policy.
Output:
	Printing to the console the BRD being made for each job throughout the rounds until reaching NE or the
	predetermined stopping condition, printing to the console the final schedule in NE, the number of rounds it
	took to get to NE, the minimal makespan, the current makespan and the scheduling quality which is current
	maksepan / minimal makespan.
Animation:
	moving animation is made by deleting the current job which is being moved,
	than drawing it in its new temporary location until reaching its destnation.
	side effect - partially delets jobs on the path from the job to its destination.
	
**Version 8.0:

This simulator demonstrates the job scheduling problem.
Where each job is a selfish agent and inspires to improve its completion time.
Simulator’s structure:
	1.	A job has a processing time.
	2.	A machine has speed in which it processes the jobs allocated to it, where 1.0 is the unit speed.
	3.	A machine has a policy and it follows it when being allocated with jobs. The different policies are:
	a.	0 – add last.
	b.	1 – add first.
	c.	2 – keeping the jobs scheduled onto the machine sorted from small PT to large PT. 
	d.	3 – keeping the jobs scheduled onto the machine sorted from small PT to large PT. 
	e.	4 – arbitrary priority list.
Input formats:
	1.	Command line arguments – number of machines, policy, speed, number of jobs, round type.
		Both policy and speed are similar o each machine. The PT of each job is random the initial scheduling is
		being done according to the machines’ policy. In addition, it is not possible to invoke policy 4 to the
		machines via this input format.
	2.	File format 1 – a text file in the format of “file format 1” attached with his project.
		The file format (1 / 2), round type, number of machines, number of jobs, a speed and a policy for each machine,
		a processing time for each job. The initial scheduling is being done according to the machines’ policy.
Output:
	Printing to the console the BRD being made for each job throughout the rounds until reaching NE or the
	predetermined stopping condition, printing to the console the final schedule in NE, the number of rounds it
	took to get to NE, the minimal makespan, the current makespan and the scheduling quality which is current
	maksepan / minimal makespan.
Animation:
	moving animation is made by deleting all of the jobs, than drawing the schedule (all of the jobs) until the
	job being moved reaches its destnation.
	side effect - transition is not smooth.

**Version 9.0:

This simulator demonstrates the job scheduling problem.
Where each job is a selfish agent and inspires to improve its completion time.
Simulator’s structure:
	1.	A job has a processing time.
	2.	A machine has speed in which it processes the jobs allocated to it, where 1.0 is the unit speed.
	3.	A machine has a policy and it follows it when being allocated with jobs. The different policies are:
	a.	0 – add last.
	b.	1 – add first.
	c.	2 – keeping the jobs scheduled onto the machine sorted from small PT to large PT. 
	d.	3 – keeping the jobs scheduled onto the machine sorted from small PT to large PT. 
	e.	4 – arbitrary priority list.
Input formats:
	1.	Command line arguments – number of machines, policy, speed, number of jobs, round type.
		Both policy and speed are similar o each machine. The PT of each job is random the initial scheduling is
		being done according to the machines’ policy. In addition, it is not possible to invoke policy 4 to the
		machines via this input format.
	2.	File format 1 – a text file in the format of “file format 1” attached with his project.
		The file format (1 / 2), round type, number of machines, number of jobs, a speed and a policy for each machine,
		a processing time for each job. The initial scheduling is being done according to the machines’ policy.
Output:
	Printing to the console the BRD being made for each job throughout the rounds until reaching NE or the
	predetermined stopping condition, printing to the console the final schedule in NE, the number of rounds it
	took to get to NE, the minimal makespan, the current makespan and the scheduling quality which is current
	maksepan / minimal makespan.
Animation:
	the job being moved is highlighted with a green frame before moving, the the new schedule appears withthe
	same job highlighted with a green frame in its new location in the schedule.
