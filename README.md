# aws
Amazon Web Services, Inc. (AWS) is a subsidiary of Amazon that provides on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis. These cloud computing web services provide distributed computing processing capacity and software tools via AWS server farms. One of these services is Amazon Elastic Compute Cloud (EC2), which allows users to have at their disposal a virtual cluster of computers, available all the time, through the Internet. AWS's virtual computers emulate most of the attributes of a real computer, including hardware central processing units (CPUs) and graphics processing units (GPUs) for processing; local/RAM memory; hard-disk/SSD storage; a choice of operating systems; networking; and pre-loaded application software such as web servers, databases, and customer relationship management (CRM).

AWS services are delivered to customers via a network of AWS server farms located throughout the world. Fees are based on a combination of usage (known as a "Pay-as-you-go" model), hardware, operating system, software, or networking features chosen by the subscriber required availability, redundancy, security, and service options. Subscribers can pay for a single virtual AWS computer, a dedicated physical computer, or clusters of either.[8] Amazon provides select portions of security for subscribers (e.g. physical security of the data centers) while other aspects of security are the responsibility of the subscriber (e.g. account management, vulnerability scanning, patching). AWS operates from many global geographical regions including 6 in North America.[9]

Amazon markets AWS to subscribers as a way of obtaining large-scale computing capacity more quickly and cheaply than building an actual physical server farm.[10] All services are billed based on usage, but each service measures usage in varying ways. As of 2021 Q4, AWS has 33% market share for cloud infrastructure while the next two competitors Microsoft Azure and Google Cloud have 21%, and 10% respectively, according to Synergy Group.[11][12]


Contents
1	Services
2	History
2.1	Founding (2000–2005)
2.2	S3, EC2, and other first generation services (2006–2010)
2.3	Growth (2010–2015)
2.4	Market leadership (2016–present)
2.5	Customer base
2.6	Significant service outages
3	Availability and topology
4	Pop-up lofts
5	Charitable work
6	Environmental impact
7	Denaturalization protest
8	See also
9	Notes
10	References
11	External links
Services
Main articles: Amazon Elastic Compute Cloud and Amazon S3
As of 2021, AWS comprises over 200[13] products and services including computing, storage, networking, database, analytics, application services, deployment, management, machine learning,[14] mobile, developer tools, RobOps and tools for the Internet of Things. The most popular include Amazon Elastic Compute Cloud (EC2), Amazon Simple Storage Service (Amazon S3), Amazon Connect, and AWS Lambda (a serverless function enabling serverless ETL e.g. between instances of EC2 & S3).[15]

Most services are not exposed directly to end users, but instead offer functionality through APIs for developers to use in their applications. Amazon Web Services' offerings are accessed over HTTP, using the REST architectural style and SOAP protocol for older APIs and exclusively JSON for newer ones.

History
Further information: Timeline of Amazon Web Services
Founding (2000–2005)

Early AWS "building blocks" logo along a sigmoid curve depicting recession followed by growth.
The genesis of AWS came in the early 2000s. Prior experience with building Merchant.com, Amazon's e-commerce-as-a-service platform for third-party retailers to build their own web-stores, led them to pursue service-oriented architecture as a means to scale their engineering operations[16][17][18][19][20][21][22] led by the then CTO, Allan Vermeulen.[23]

Around the same time frame, Amazon was frustrated with the speed of its software engineering, and sought to implement various recommendations put forth by Matt Round, an engineering leader at the time, including maximization of autonomy for engineering teams, adoption of REST, standardization of infrastructure, removal of gate-keeping decision-makers (bureaucracy), and continuous deployment. He also called for increasing the percentage of the time engineers spent building the software rather than doing other tasks.[24] Amazon created "a shared IT platform" so its engineering organizations which were spending 70% of their time on "undifferentiated heavy-lifting" such as IT and infrastructure problems could focus on customer-facing innovation instead.[25] Besides, in dealing with unusual peak traffic patterns especially during the holiday season, migrating services to commodity Linux hardware, and reliance on open source software already had Amazon's Infrastructure team, led by Tom Killalea,[26] Amazon's first CISO,[27] run their data centers and associated services in a "fast, reliable, cheap" way.[26]

In July 2002, Amazon.com Web Services, managed by Colin Bryar,[28] launched its first web services opening up the Amazon.com platform to all developers.[29] Over a hundred applications were built on top of it by 2004.[30] This unexpected developer interest took Amazon by surprise and convinced them that developers were "hungry for more."[25]

By the Summer of 2003, Andy Jassy had taken over Bryar's portfolio[31] at Rick Dalzell's behest, after Vermeulen, who was Bezos' first pick, declined the offer.[23] Jassy subsequently laid down the vision for an "Internet OS"[16][18][20][32] made up of foundational infrastructure primitives that alleviated key impediments to shipping software applications faster.[16][17][18][20][22] By fall 2003,[16][18] databases, storage, and compute were identified as the first set of infrastructure pieces that Amazon should launch.[16][18][25]

Jeff Barr, an early AWS employee, credits Vermeulen, Jassy, Bezos, himself, and a few others for coming up with the idea of what would evolve into EC2, S3, and RDS,[33] whilst Jassy recalls that being a result of brainstorming for about a week with "ten of the best technology minds and ten of the best product management minds" on about ten different Internet applications and the most primitive building blocks required to build them.[20] Werner Vogels puts down Amazon's desire to make the process of "invent, launch, reinvent, relaunch, start over, rinse, repeat" as fast as it could be to have led them to breakdown organizational structures with "two-pizza teams"[c] and application structures with distributed systems;[d] and that these changes ultimately paved way for the formation of AWS[22] and its mission "to expose all of the atomic-level pieces of the Amazon.com platform".[36] According to Brewster Kahle, co-founder of Alexa Internet which was acquired by Amazon in 1999, his start-up's compute infrastructure helped Amazon solve its big data problems and later informed the innovations that underpinned AWS.[37]

Jassy assembled a founding team of 57 employees from a mix of engineering and business backgrounds to kick-start these initiatives,[20][19] with a majority of the hires coming from outside the company;[20] Jeff Lawson, Twilio CEO,[38] Adam Selipsky, Tableau CEO,[39][40] Mikhail Seregine,[41] co-founder at Outschool[citation needed] among them.

In late 2003, the concept for compute,[e] which would later launch as EC2, was reformulated when Chris Pinkham and Benjamin Black presented a paper internally describing a vision for Amazon's retail computing infrastructure that was completely standardized, completely automated, and would rely extensively on web services for services such as storage and would draw on internal work already underway. Near the end of their paper, they mentioned the possibility of selling access to virtual servers as a service, proposing the company could generate revenue from the new infrastructure investment.[43][unreliable source?] Thereafter Pinkham, Willem van Biljon and lead developer Christopher Brown developed the Amazon EC2 service, with a team in Cape Town, South Africa.[44]

In November 2004, AWS launched its first infrastructure service for public usage: Simple Queue Service (SQS).[45]

![Screenshot (15)](https://user-images.githubusercontent.com/115457031/201697131-b700f773-3bde-4b95-9abe-672eff47dc28.png)
![Screenshot (16)](https://user-images.githubusercontent.com/115457031/201697162-a8b68e1a-d53f-4ed8-aea0-d378c8f2152c.png)
![Screenshot (17)](https://user-images.githubusercontent.com/115457031/201697196-f8920f71-7d65-4b24-8858-c78e5d5033ee.png)
![Screenshot (18)](https://user-images.githubusercontent.com/115457031/201697227-7f98eb7c-3511-46a6-bb5c-5389c5025e8f.png)
