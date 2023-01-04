# Cole's Senior Seminar

This is the $\LaTeX$ source for my college Senior Seminar paper. During this course, a student writes a 5-6 page paper, in the Association for Computing Machinery (ACM) style, that is an overview of recent peer-reviewed computer science publications on a topic of their choice. The student presents the paper as a 25-minute conference-style presentation for faculty, fellow students, alumni, and others. The student needs to demonstrate an in-depth understanding of their topic by writing a clear paper that summarizes (in the student’s own words) the material that they learned from their sources and clearly presenting it, including the ability to answer questions on the material.

My paper is based in large part on the 2018 paper ["*A Dynamic Packet Scheduling Method for Multipath TCP in Heterogeneous Wireless Networks*"](https://ieeexplore.ieee.org/document/8600179/) by Guannan Xie, Huifang Chen, Lei Xie, and Kuang Wang. 

# Abstract 

Today many devices contain hardware to transmit data across the internet via cellular, WiFi, and wired connections. Many of these devices communicate by using a protocol known as Transmission Control Protocol (TCP).  TCP was developed when network resources were expensive, and it was rare for a typical network-aware device to have more than one connection to a network.  An extension to TCP known as Multipath TCP (MPTCP) was developed to leverage the multiple network connections to which devices now have access. While the MPTCP extension has been successful in its goal of using multiple network connections to send data simultaneously, MPTCP presents new challenges. Scheduling data to be sent across multiple network connections with varying network conditions can result in data arriving out of order, adding increased system overhead and network latency. This paper presents the challenges of MPTCP packet scheduling and summarizes a proposed solution that has been found to increase performance over existing MPTCP scheduling methods.

See full version [here](https://umm-csci.github.io/senior-seminar/seminars/fall2022/maxwell.pdf).

# Acknowledgements

I would like to thank my advisor [Peter Dolan, Ph.D.](https://academics.morris.umn.edu/peter-dolan) for providing outstanding feedback and guidance throughout the research and writing of this paper. I also want to thank [Kristin Lamberty, Ph.D](https://academics.morris.umn.edu/kristin-lamberty) for facilitating the senior seminar process and [Kevin Arhelger](https://www.linkedin.com/in/kevarh/) for his professional review and feedback.
