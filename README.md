# CS342-Homework-2-solution

Download Here: [CS342 Homework 2 solution](https://jarviscodinghub.com/assignment/cs342-homework-2-solution-2/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Q. Consider the following memory reference string (only page numbers are shown):
6 6 3 3 3 4 4 4 4 4 7 7 7 2 2 7 4 4 4 4 4 4 3 3 3 4 5 5 5 5 5 5 7 7 7 4 4 4 2 2 2 2 2 3 3
0 0 0 1 1 1. Assume at every tick, we have a memory reference. The first memory
reference is done at tick 1. Assume at every 10 ticks, reference bits are cleared, just
after making the 10th memory reference. We use a single reference bit for each page.
Assume there are 3 frames allocated to a process. All frames are initially empty.
Assume we use clock algorithm (i.e., a second change algorithm) as the page
replacement algorithm. Find out how many page faults we will have (note that we are
not using Modified/Dirty bit). Assume for a new page that is brought in, its reference
bit is set to 1.
Q. Consider a computer that is uses segmentation and paging. The segment table of a
process is the following:
Segment Base Length
0 1024 1024
1 4196 512
2 128 256
3 2048 768
Assume page size is 64 bytes. Assume virtual addresses are 16 bits long. Assume
physical addresses are also 16 bits long. Assume a page i is located in a frame i+10
(for example, page #11 of linear logical memory is in frame #21 of physical memory).
Convert the following logical addresses to their physical ones:
a) (0, 50)
b) (1,0)
c) (1,100)
d) (1,700)
e) (2,10)
f) (3,200)
All numbers above are decimal.
Q. Assume a cigarette requires three ingredients (items) to smoke: Tobacco (t), Paper
(p) and a Match (m). Assume there are 3 smokers around a table, each of whom has
an infinite supply of one of the three ingredients (items) — one smoker has an infinite
supply of tobacco, another has an infinite supply of paper, and the third has an infinite
supply of matches. Assume there is also a non-smoking agent which has also an
infinite supply of these items. The agent enables the smokers to make their cigarettes
by randomly selecting and putting two items (out of three items) on the table. Then
the smoker having the missing item will take the items from the table (in this way will
make the table empty), will make his cigarette, and will be able to smoke for a while.
When table becomes empty, agent again chooses two items in random and places
them on the table. Another smoker can now smoke (or maybe the currently smoking
smoker will take those items again and start smoking again after it has finished its
current smoking). This process continues forever. Synchronize the agent and 3
smokers by use of semaphores to act in this way.
Q. Assume we have processes A, B, C, D, E arriving to a system at the following
times shown in the table below. The CPU time required by each process is also shown
in the table. Assume the CPU scheduling algorithm is Round-Robin with time
quantum q. Assume q is very small (very close to zero, but is not zero), hence perfect
processor sharing is happening. Ignore the context switching overhead, i.e. context
switch time is equal to 0. Compute the waiting time and finish time of each process.
Arrival Time CPU Time
Process A 0 145
Process B 50 40
Process C 90 70
Process D 210 95
Process E 240 45
Q. Consider a disk with N tracks numbered from 0 to N-1, and assume that requested
sectors are distributed randomly and evenly over the disk. We want to calculate the
average number of tracks (i.e., cylinders) traversed by a seek.
a) Calculate the probability of a seek of length j when the head is currently
positioned over track t.
b) Calculate the probability of a seek of length K, for an arbitrary current
position of the head.
c) Calculate the average number of tracks traversed by a seek.
Q. Assume block size in a file system that is using hierarchical indexed allocation is
4KB. Assume disk pointer size is 8 bytes. The hierarchy can grow to 3 levels at most
(like Unlix/Linux file system). How many index blocks are required for a file of size
1 MB, 100 MB, 4 GB and 1 TB? What can be the maximum file size in bytes?
Assume no caching of index blocks, how many disk accesses are required on the
average to randomly access (uniform random) the 4 GB file?
