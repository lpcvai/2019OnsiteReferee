# Referee Program for the IEEE International Low-Power Image Recognition Challenge (LPIRC)

Please read the announcement at [IEEE Rebooting Computing](http://rebootingcomputing.ieee.org/lpirc)

The rules, the methods used by the past winners, and their scores are available in this paper: "Low-power image recognition challenge," Asia and South Pacific Design Automation Conference (ASP-DAC), Chiba, 2017, pp. 99-104.
doi: 10.1109/ASPDAC.2017.7858303. Download the paper from [IEEExplore](http://ieeexplore.ieee.org/document/7858303/).

Please read the [Sample Client Program](https://github.com/ieeelpirc/sampleclient).

LPIRC is an on-site competition. All participants must bring their systems to the competition sites

-2015 San Francisco (with Design Automation Conference)

-2016 Austin (with Design Automation Conference)

-2017 Honolulu (with Computer Vision and Pattern Recognition)

LPIRC is an on-site competition and participants bring their systems to the competition site. LPIRC uses a client-server model: the referee is the web server and participants' systems are clients. To reduce intereference, only one client is allowed to connect to the server at any moment.

The server and the client use HTTP for communication. The client uses GET to retreive images and POST to return answers.

* Procedure to prepare for a system:
1. [Download Sample Images](http://vision.cs.unc.edu/LPIRC/login.php)
2. Divide the images into training and testing sets
3. Train the recognition program
4. [Download the Sample Client](https://github.com/ieeelpirc/sampleclient)
5. [Download the Referee Program](https://github.com/ieeelpirc/referee)
6. Set up the referee system.
7. Copy the testing data to the referee
8. Test the communication between the client and the referee






