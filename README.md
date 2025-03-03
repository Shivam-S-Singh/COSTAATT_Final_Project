# <ins>Harnessing Software Engineering Principles in Network Operations</ins>

## The Application of DevOps in Campus Area Networks

<img src="https://github.com/Shivam-S-Singh/COSTAATT_Final_Project/blob/2cc85cc26c99372265f3745dce79d3cc1dee5f2c/TitlePic.jpg" alt="Title Pic">

This is a practical exercise to address common challenges faced in computer networking that can be solved by utilizing software engineering concepts and tools originally intended to streamline the production and management of code.

<!-- Talk about how we will approach this issue and that this project is a proof of concept for company buy in-->
<!-- Describe the common issues faced and elaborate on our approach to each issue-->

Common Issues faced in Network Engineering:
- Documentation
- Production Network as the Single Source of Truth
- Configuration Management
- Testing on Production
- Change Management Challenges


<!-- List resources in earlier part of project, software, tools, network devices, system requirements, network images -->


### Building Our Network
We will be doing a greenfield deployment instead of trying to simulate COSTAATT's existing network.
The reason I chose to build a network from scratch is because having a design phase will allow me to better showcase some of the tools that will be utilized in this project.
With that being said, we need to first design a new network. If you would like details behind my design choices as well as the process you can reference the Project Proposal Document.


Tradionally in the earlier design process of networks, the most commonly used tools were Visio, Excel and Word. Where Visio would be used for diagrams of the proposed network. Word and Excel would be used to log logical information such as VLANs and IP Addressing. This was what was available at the time and there are licensing cost associated with these software.


The tools that were utilized in the design stage of the network were Draw.IO and NetBox. In the spirit of open source development we will be utilizing as much freely available software from the initial start of the project all the way to final product.

Below is a high level diagram of what our network will look like. This is a 3-Tier network

![COSTAATT High Level Diagram](https://github.com/Shivam-S-Singh/COSTAATT_Final_Project/blob/f9ebebf90d190d41b07ddb6494e0a1dbd5036574/NetworkCostaatt_HLD.jpg)

While we are not working with physical devices, below serves as a reference to what the devices would look like on a switch rack. The devices chosen were based on its relation to the network OS software that will run in GNS3.



<!-- List resources in start of project -->
![COSTAATT Core Switch Rack](https://github.com/Shivam-S-Singh/COSTAATT_Final_Project/blob/abf5796238cafb637c89ff2fbfaf4b6eca8b7ddc/COSTAATT_South_Campus_Core_SwitchRack.jpg)

![COSTAATT Access Switch Rack](https://github.com/Shivam-S-Singh/COSTAATT_Final_Project/blob/a2fba9ad2b3cdaf24e2b8b82360586891f4910ef/COSTAATT_South_Campus_Access_SwitchRack.jpg)
