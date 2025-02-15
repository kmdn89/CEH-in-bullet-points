## Identify the services provided by the    
  ## application layer of
   ## the cloud security control model?

### Cloud Security Control Layers

//////////////////////////////

### Information Layer

      Develop & document an

          Information Security Management Program (ISMP),

            which includes

                - administrative safeguards,
                - technical safeguards,
                - physical safeguards

        to protect information against :
          - unauthorized access,
          - modification
          - deletion.

      Some of the information layer security controls include :
              - DLP,
              - CMF,
              - database activity monitoring,
              - encryption, etc.

///////////////////////////////

### Trusted Computing

      Trust computing defines secured computational environment that implements :
      
          internal control, auditability, &  maintenance to ensure :
      
                    - availability
                    - integrity 
                   
                   of cloud operations.
                   
#### Hardware & software RoT & API's 
      
      are few security controls for trusted computing.
      
##### Roots of Trust (RoT) 
      
      - set of functions 
      
            in the trusted computing module that is
            
                  "always trusted" by the computer’s operating system (OS).

       - The RoT serves as
            
            - separate compute engine 
                    
                    - controlling the trusted computing platform cryptographic processor
                                     
                             - on the PC or mobile device
                             
                                    - it is embedded in.

         The RoT provides the functionality behind trusted computing features including
         
           -> On the fly drive encryption.
           -> Detection and reporting of unauthorized changes to the OS or programs.
           -> Detection of rootkits.
           -> Memory curtaining to prevent programs from inappropriately reading from or writing to another program's memory.

         Hardware-based digital rights management (DRM) support.

////////////////////////////

### Physical Layer

      includes security measures for :
      
          - cloud infrastructure
          - data centers
          - physical resources.

      Security entities that come under this perimeter are :
                - physical plant security
                - fences
                - walls
                - barriers
                - guards
                - gates
                - electronic surveillance
                - CCTV
                - physical authentication mechanisms
                - security patrols, and so on.

/////////////////////////

### Application Layer

      - To harden the application layer, establish 
      
            - policies that match with industry adoption security standards, 
      
                  for example, OWASP for a web application.
          
      - It should meet and comply with appropriate regulatory and business requirements.
      
      - Application layer controls include : 

                - SDLC, 
                - binary analysis, 
                - scanners, 
                - web app firewalls, 
                - transactional sec, ....
          
          
--------------------------------------------------------------------------------------------------------------------------------------------

## The components such as 

          NIDS/NIPS, 
          firewalls, 
          DPI, 
          Anti-DDoS, 
          QoS, 
          DNSSEC,  
          OAuth 
          
## are included in which of the following cloud security control layers?

#### Network Layer : 
          
          It deals with various measures and policies adopted by a network administrator to monitor and prevent illegal access, misuse, modification, or denial of network-accessible resources.
                Some of the additional network layer security controls include NIDS/NIPS, firewalls, DPI, anti-DDoS, QoS, DNSSEC, OAuth, etc.

#### Application Layer

      - To harden the application layer, establish 
      
            - policies that match with industry adoption security standards, 
      
                  for example, OWASP for a web application.
          
      - It should meet and comply with appropriate regulatory and business requirements.
      
      - Application layer controls include : 

                - SDLC, 
                - binary analysis, 
                - scanners, 
                - web app firewalls, 
                - transactional sec, ....

#### Management Layer

           This layer covers the cloud security administrative tasks, 
            
                  - which can facilitate :
                        - continued, 
                        - uninterrupted, & 
                        - effective 
                        
                     services of the cloud.
                     
           Cloud consumers should look for the above-mentioned policies to avail better services.
           
            Management layer security controls include 
                        
                        - GRC, 
                        - IAM, 
                        - VA/VM, 
                        - patch management, 
                        - configuration management, 
                        - monitoring, etc.

#### Computation and Storage

          In cloud,
            
               due to the lack of physical control of the data & the machine :
            
                  -> the service provider :
                        - may be unable to manage the data and computation
                                    and
                        - lose the trust of the cloud consumers.
          
          Cloud provider must establish policies and procedures for data storage and retention.
          
          Cloud provider should implement appropriate backup mechanisms to 
                  
                  - ensure availability & continuity of services that meet with 
                  
                        - statutory,
                        - regulatory, 
                        - contractual, or 
                        - business requirements and compliance. 
          
          some security controls in computation and storage : 
          
                Host-based firewalls, 
                HIDS/HIPS, 
                integrity & file/log management,
                encryption, 
                masking 

----------------------------------------------------------------------------------------------------------------------------
## Which of the following mechanisms 
##        should be incorporated into the cloud services 
##                  to facilitate networks and resources 
##                            to improve the response time of
##                                      a job with maximum throughput?

 #### Cloud load balancing :
 
           process of distributing workloads and computing resources in a cloud computing environment.
 
 #### Load balancing 
 
          allows enterprises to manage application or workload demands by allocating resources among multiple computers, networks, or servers.
 
 #### Cloud load balancing 
 
          involves hosting the distribution of workload traffic and demands that reside over the Internet.

 -------------------------------------------------------------------------------------------------------------------------------
## Which of the following categories of security controls strengthens the system against incidents by minimizing or eliminating vulnerabilities?

 #### Preventive Controls:    
 
             These controls strengthen the system against incidents, probably by minimizing or eliminating vulnerabilities.
             Example: Strong authentication mechanism to prevent unauthorized use of cloud systems.

 #### Deterrent Controls: 
 
          These controls reduce attacks on the cloud system.
          Example: Warning sign on the fence or property to inform adverse consequences for potential attackers if they proceed to attack
 
 #### Detective Controls: 
 
          These controls detect and react appropriately to the incidents that happen.
                     Example: Employing IDSs, IPSs, etc. helps to detect attacks on cloud systems.
 
 #### Corrective controls: 
 
          These controls minimize the consequences of an incident, probably by limiting the damage.
                     Example: Restoring system backups.

---------------------------------------------------------------------------------------------------------------------------------------------------
## Which of the following categories of security controls minimizes the consequences of an incident by limiting the damage?

#### Corrective controls: 
          
          These controls minimize the consequences of an incident, probably by limiting the damage.
                      Example: Restoring system backups.

#### Deterrent Controls: 

          These controls reduce attacks on the cloud system.
                    Example: Warning sign on the fence or property to inform adverse consequences for potential attackers if they proceed to attack

#### Preventive Controls: 

          These controls strengthen the system against incidents, probably by minimizing or eliminating vulnerabilities.
                     Example: Strong authentication mechanism to prevent unauthorized use of cloud systems.

#### Detective Controls: 
          
          These controls detect and react appropriately to the incidents that happen.
                    Example: Employing IDSs, IPSs, etc. helps to detect attacks on cloud systems.

------------------------------------------------------------------------------------------------------------------------------------------------------
## Which of the following protocols is used for secure information passage between two endpoints?

#### Secure sockets layer (SSL) :
           
           computer networking protocol 
           
                    for securing connections between network application :
                              - clients & servers 
           
                    over an insecure network, 
                              such as the Internet.
                              
          However, TCP, UDP, and FTP are a type of network protocol.

-------------------------------------------------------------------------------------------------------------------------------
## Which of the following is NOT a best practice for cloud security?

#### Provide unauthorized server access using security checkpoints

Some of the Best Practices for Securing Cloud
?	Enforce data protection, backup, and retention mechanisms
?	Enforce SLAs for patching and vulnerability remediation
?	Vendors should regularly undergo AICPA SAS 70 Type II audits
?	Verify one’s cloud in public domain blacklists
?	Enforce legal contracts in employee behavior policy
?	Prohibit user credentials sharing among users, applications, and services
?	Implement secure authentication, authorization, and auditing mechanisms
?	Check for data protection at both design and runtime
?	Implement strong key generation, storage and management, and destruction practices
?	Monitor the client’s traffic for any malicious activities
?	Prevent unauthorized server access using security checkpoints
?	Disclose applicable logs and data to customers
?	Analyze cloud provider security policies and SLAs
?	Assess security of cloud APIs and also log customer network traffic

Providing unauthorized server access using security checkpoints 
                    
                    is not a good practice 
                    
Preventing unauthorized server access using security checkpoints 
                    
                    is a good practice for cloud security.

--------------------------------------------------------------------------------------------------------------------------------------
## Detective security controls 
          
          detect & react appropriately to the incidents that happen on the cloud system.

## Which of the following is an example of detective security controls?

#### Employing IDSs and IPSs

Explanation:

                  Detective controls: 
                        
                              These controls detect & react appropriately to the incidents that happen.
                  
                  For Example, employing 
                  
                        IDSs, IPSs, and so on 
                   
                   helps to detect attacks on cloud systems.
-----------------------------------------------------------------------------------------------------------------------------------------
## In which of the following cloud security control layers do the security controls DNSSEC, OAuth operates?

#### Network layer
The network layer deals with various measures and policies adopted by a network administrator to monitor and prevent illegal access, misuse, modification,
 or denial of network-accessible resources.
Some of the additional network layer security controls include :
                    
                    NIDS/NIPS, 
                    firewalls, 
                    DPI, 
                    anti-DDoS, 
                    QoS, 
                    DNSSEC, 
                    OAuth, 
