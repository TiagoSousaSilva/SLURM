# SLURM Implementation

The "SLURM Implementation" project was carried out on AWS, where a virtual network environment was set up to enhance job processing capabilities. The main machine, named "Controller," was deployed with SLURM, a job scheduler and workload manager. Three additional machines, known as "Workers," were connected to the Controller's private interface.

To enable seamless communication between the Controller and the Workers, several configurations were implemented. Routing tables were set up in AWS to direct network traffic properly. A Virtual Private Cloud (VPC) was created to provide a secure and isolated network environment. Additionally, iptables were configured to manage network filtering and ensure secure communication.

The Controller acted as the central job scheduler, sending tasks to the Workers for processing. Through this SLURM implementation, job processing efficiency was significantly improved, allowing tasks to be completed faster and more effectively.

Overall, the "SLURM Implementation" project demonstrated the successful deployment and integration of SLURM within an AWS virtual network, utilizing routing tables, VPC, and iptables to establish secure communication and optimize job processing capabilities.
