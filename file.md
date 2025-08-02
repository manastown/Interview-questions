Basic interview Questions


                          1. Introduce yourself
2. Statefile management
3. What is the state file and where can it be stored?
4. When will the state file be created?
5. What is state locking? Locking mechanism in Terraform?
6. Move block in Terraform — define and give example.
7. Difference between implicit and explicit dependencies (share syntax).
8. Difference between variable.tf and terraform.tfvars files.
9. Variable.tf vs variables.tf vs terraform.tfvars.
10. Type constraints in Terraform.
11. What is a module in Terraform?
12. What is a pattern module? Difference between root and child modules.
13. What are lifecycle rules in Terraform? (mention 2–3 arguments, e.g. in storage account)
14. Data block in Terraform — is it part of the state file?
15. What are data types in Terraform?
16. Difference between count vs for_each. Is count only integer? Why deletion with count is difficult?
17. What are logging levels supported by Terraform?
18. What is provisioner in Terraform? File provisioners? Null resource?
19. If you have a VM template + PowerShell script for domain join, which provisioner do you use?
20. What is the difference between provider and provisioner?
21. What is TFLint (linting) in Terraform?
22. What is a service connection in Azure DevOps? What is required to create one?
23. Deployment group vs task group in Azure DevOps
24. What are security best practices in pipelines/ADO?
25. What is a gate in Azure DevOps?
26. What are pools and agent pools? Is macOS supported as agent?
27. What is a sprint in Azure Boards? What is a work item? Difference between them.
28. What is a stakeholder in Azure DevOps?
29. Process for PR (pull request)
30. Git: what is the difference between commit and push? Also git fetch vs git pull.
31. Tools used for pipeline—e.g., YAML, GitHub Actions
32. E2E pipeline flow—explain full YAML example
33. How do you manage multiple Azure subscriptions?
34. VM vs VMSS — what’s the difference?
35. If requirement is 2 VMs + 2 databases, would you choose VM or VMSS?
36. If you have 1500 subscriptions, how to manage from ADO?
37. As an architect, how do you plan and propose infra solutions to customers?
38. Recently upgraded Terraform templates—give an example
39. What are Terraform backends? Which are you familiar with?
40. How do you encrypt the state file?
41. When you declare a variable with default value in Terraform—what argument?
42. If a VM installed Office after creation, then terraform apply again—what happens?
43. In TF, if you update a VM custom image and re-run apply—what happens?
44. Lifecycle block usage in storage scenario (duplicate of #13?)
45. What is workspace in Terraform and why use it?
46. What is terraform show?
47. What is terraform fmt?
48. What is terraform provisioners?
49. How to handle sensitive variables — if marked sensitive, how to view in state?
50. If variable values are hard-coded in VM definition, will they show in plan?
51. What is terraform download module and providers stage?
52. What is Saltener? (Possibly "splinter"? Clarify)
53. What is pipeline or which pipelines you've worked on—explain E2E flow
54. Kubernetes: stateless vs stateful
55. If a pod is pending — how to troubleshoot?
56. Docker: basics, script, volume, where images are stored
57. Bash and PowerShell scripting experience
58. Managing PVs in Kubernetes with a specific service account
59. Cluster role binding in Kubernetes
60. Terraform functions — name and examples
61. How to maintain/upgrade Kubernetes cluster
62. What is peering?
63. Availability set vs availability zone

















Persistent

Interviewer: Vinita Gupta

1.	Write Terraform code for 1 VNet with 10 subnets (without using for_each).
2.	How to assign 1000 IPs to one subnet and 500 IPs to another? Kaunsa CIDR range use karoge?
3.	Networking types in Kubernetes?
4.	Write a sample Ingress YAML file.
5.	Write a sample Deployment YAML file.
6.	What are Liveness and Readiness probes? Unmein kya difference hai?
7.	Kaise banayoge pod ko scalable? What is HPA (Horizontal Pod Autoscaler)?
8.	What is CNI and how do you use it in Kubernetes?
9.	Difference between Load Balancer and Application Gateway?
10.	Explain nodeSelector, Taints, and Tolerations in Kubernetes.
11.	Difference between a reusable workflow and a composite action in GitHub Actions?
12.	GitHub Action kya hota hai? Kaise likhte hain?
13.	For checkout, kaunsa action aur version use karte ho?
14.	Difference between jobs, steps, and actions in GitHub Actions workflow?
15.	Build metrics in GitHub Actions— aapne use kiye hain?
16.	Azure resource groups kya hain? Infrastructure management mein kaise use hote hain?
17.	Azure Monitor pe kaam kiya hai? Describe your experience.
18.	Azure mein RBAC ka role-based control kaise configure karte hain?
19.	AKS mein autoscaling Azure-native tools se kaise enable karoge?
20.	AKS autoscaling kaise kaam karta hai (internally)?
21.	Terraform state ko team mein kaise manage karte ho?
22.	Terraform se AKS cluster kaise provision karte ho, aur ACR se kaise connect karte ho?
23.	terraform init kya karta hai?
24.	terraform plan aur terraform apply mein kya farq hai?
25.	Agar state file local thi aur accidentally delete ho gayi, toh recover kaise karoge?
26.	Kubernetes mein deployed services ke secrets ya credentials kaise retrieve karoge?
27.	Kubernetes service discovery cluster ke andar kaise handle hota hai?
28.	Kubernetes mein “stateful” ka kya matlab hota hai?
29.	Terraform provisioners kya hote hain? Kaise kaam karte hain?
30.	Terraform provider kya hota hai?
31.	null_resource kya hai Terraform mein?
32.	Terraform meta-arguments kya hote hain (e.g., count, depends_on)? Examples do.
33.	Mandatory Terraform commands kya hain aur Azure DevOps mein kaise use karte ho?
34.	Agar cloud mein resource hai lekin state file mein nahi hai, to terraform plan/apply kya karega?
35.	Terraform drift kya hota hai? Usko kaise detect aur fix karte ho?
36.	Existing resource ko Terraform state mein kaise import karte ho?
37.	Aap Docker ko apne current project mein kaise use karte ho?
38.	Ek Dockerfile explain karo with example.
39.	Multi-stage Dockerfile kya hota hai? Uska use kya hai?
40.	Dockerfile mein CMD vs ENTRYPOINT kya difference hai? Practical example do.
41.	Git: fetch aur pull mein kya farq hai?
42.	Kubernetes: Deployment, StatefulSet, ReplicaSet mein kya difference hai?
43.	service.yaml kaise likhte ho aur kya use hota hai?
44.	Kubernetes mein different service types kaunse hain?
45.	Kubernetes YAMLs mein general metadata (e.g., labels, annotations) kyon aur kahan use hoti hai?
46.	Cloud & CI/CD pipeline mein credentials kaise securely manage karte ho?
47.	Aise code pushes prevent kaise karoge jo insecure code contain karte hain? (Pipeline mein security scanning)
48.	Highly available infrastructure ko deploy aur ensure kaise karte ho?
49.	Agar GitHub Action ke Azure CLI step se timeout ho raha hai, troubleshoot kaise karoge?
50.	Dev, Stage, Prod environments ke liye Terraform code ko kaise design & secure karoge?
51.	Azure Functions aur AWS Lambda ka kya use hai?
52.	Kubernetes mein monitoring kaise enable karte ho?
53.	Agar pods mein “cross loopback” error aaye, troubleshoot approach kya hogi?
54.	Terraform state file kya hota hai? Usko secure kaise karte ho?
55.	Azure & AWS mein secrets ko kaise secure karte ho?
56.	CI/CD pipelines aap kaise deploy karte ho? Organization mein kya process follow karte ho?
57.	Terraform mein HA aur security ke liye kaunse components use karte ho?
58.	PowerShell script likho jo memory check kare aur notify kare agar usage 85% se zyada ho.
59.	Terraform code: 1 VNet + 3 subnets + NSG attach to VM dynamically.
60.	Terraform code to create multiple VMs.
61.	Terraform backend config & state file ka code.
62.	Agar VM pehle portal se create kia aur fir Terraform code likha, plan/apply se kya hota hai?
63.	CI/CD pipeline process end-to-end kya hai?
64.	Pipeline trigger ka YAML code likho.
65.	Git: undo command after git add.
66.	Git: Squash kya hota hai?
67.	git clone vs git merge batao.
68.	Git staging area kya hoti hai?
69.	Hotfix branch scenario— kya steps honge?
70.	Terraform code: VNet + 2 subnets using module and map.
71.	Kubernetes pod create karne ke liye YAML likho.
72.	Terraform: Map vs List object kya hai? Kab kaun use karte ho?
73.	Bash script likho jo 5 VMs ki memory export kare.
74.	ISO 27001 kya hai? DevOps mein relevance kya hai?
75.	Terraform code likhne ke baad kya steps follow karte ho (testing, deployment)?
76.	Aap kaun kaunse Azure services pe kaam kar chuke ho?
77.	Azure Key Vault kya hai?
78.	Code mein aur cloud mein secrets kaise manage karte ho?
79.	Kubernetes mein ek namespace ke sare pods kaise list karoge?
80.	Kubernetes pods troubleshoot karne ke steps kya hain?
81.	Agar Terraform resource manual change ho gaya ho, handle kaise karoge?
82.	Manual changes ignore karna ho Terraform mein— kaise? (Lifecycle settings)
83.	Terraform-managed VM mein manually extra OS disk add hua ho— handle kaise karoge?
84.	Databases ka backup kaise lete ho (Azure/AWS)?
85.	Application Load Balancer kya hota hai?
86.	Network rule vs Application rule in Azure Firewall— kya farq hai?
87.	Classic vs Application Load Balancer in AWS— difference kya hai?
88.	SRE (Site Reliability Engineering) practices kya hote hain?
89.	Apne recent SRE project ka walkthrough do.
90.	CI/CD pipelines mein additional security kaise add karte ho?
91.	Terraform se infrastructure optimize karne ka kya scenario hai?
92.	Azure cloud mein kisi problem ko troubleshoot karne ka example do.
93.	Grafana aur Prometheus use kiye hain monitoring ke liye?
94.	Agar customer Terraform version upgrade maange, impact assessment kaise karoge?
What component you will use when creating application gateway ...complete infra frontend backend database ...and private end point , WAF 
2. What is CDN and how it works
3. Type of load balancer and there used 
4. How to configure routing rule in application gateway.
5. What you use compute services
6. What is docker file , can we create docker image without pulling an image
7. What is services in kubernetes 
8. Traffic flow to access kubernetes cluster from user .. complete flow with ingress rule 
9. What is liveness and readiness problem
10. What is statefull and demon set in kubernetes 
11. What is backend block in Terraform and why we use.
12. What is provisioner block ..give some use case where you used.
13. What is main difference between CDN and traffic manager
14. What security tools you used in azure
If we have one pipeline and we have to run same pipe line for dev test environmen ..how you do this.
16. What is the steps you will take if pipeline is running long and we have to reduce time.
17. What is hot fix in pipelines 
18. What is acr and how to push build image to acr, and how you authenticate pipeline with ACR.
19. Purpose of key vault and use case.
20. What Git conflict and git squash
Persistent :L1 first interview
3. What is terraform init and what it does
4. How does terraform connect with azure cloud 
5. Where you store statefile
6.if we created vm on portal then same write to the code the WhatsApp will happen 
7. Backend block 
8. What is git pull and merge
9. What is git clone and git push 
10. Git squash
11. Write a docker file
12. Difference between CDM and entry point 
13.we have downloaded artifects and how can you manage to 1st artifect will go on prod 2nd will go in staging and 3rd will go in main.



























Capgemini
1.	What is Git squash and Git rebase? What is the difference between them?
2.	If you are creating a VM via Terraform code and it fails, how do you roll back the changes?
3.	Is it possible to manually modify Terraform state files after deployment?
4.	What are the different variable types in Terraform? How do you define them?
5.	How are you passing values into variables in Terraform?
6.	You have two Azure subscriptions: one with an image, another with VM — how do you manage this via Terraform?
7.	How do you manage secrets using Azure Key Vault, and how do you reference them via Service Principal in Terraform?
8.	What is Python or PowerShell? How do you use it in automation? Write a loop to print numbers from 1 to 10.
9.	Can we convert a Federation Service connection into a secret as per client request?
10.	If I define a default value in variables.tf, why should I use terraform.tfvars? How is it helpful in automation?
11.	If there are three folders: prod, stage, and qa, how will you use .tfvars for each?
12.	How can we create multiple resource groups across multiple subscriptions using Terraform?
13.	How many ways can we deploy or host an application on Azure?
14.	What are the strategies you use to deploy an application using CI/CD pipelines?
15.	How do you validate your CI/CD pipeline end-to-end? If you face any conflicts, how do you resolve them?
16.	What is Azure Data Factory? How do you use and implement it in a pipeline?
17.	If a developer has created a database manually, how will you convert it into a managed SQL database through CI/CD?
18.	Have you used Azure Runbooks? If yes, where and how?
20.	How do you manage infrastructure (IaC)?
21.	What is your approach to designing a CI/CD pipeline?
22.	Which tools are you using for your CI/CD pipelines?
23.	How do you handle deployments in Kubernetes?
24.	What is the difference between Availability Zones and Regions?
25.	What is GitOps?
26.	How do you ensure security in your CI/CD or infrastructure process?
27.	How do you handle system failures or outages?
28.	Is it possible to get a public DNS and public IP using an internal load balancer?
29.	From on-premises, how do you connect to Azure Cloud? Which tools do you use for failover?
30.	What is Azure Site Recovery (ASR), and why do we use it?
31.	What is Azure Blob Storage and where do you use it?
32.	What is the use of containers in cloud deployment?
33.	Difference between Windows Active Directory and Azure Active Directory?
34.	What is Geo-targeting in AWS CloudFront?
35.	What is the difference between Continuous Delivery and Continuous Deployment?
36.	Write a YAML file for a release pipeline.
37.	How do you create a custom Docker image? Write a sample Dockerfile.
38.	What is a Kubernetes cluster?
39.	If a build fails, how do you revert the last commit?
40.	Explain your Git branching strategy.
41.	What is git rebase and when do you use it?
42.	How do you monitor Kubernetes clusters?
43.	You need to configure a Canary deployment — how will you do it?
Interviewers: Naren Reddy / Priyanka Jena
44.	Give your self-introduction.
45.	Tell me about your current project and day-to-day activities.
46.	Write Terraform code for a VNet and Subnet (basic, in Notepad).
47.	Write a basic Kubernetes Pod YAML file.
48.	What command do you use to build an application using NPM?
49.	What is a Service Endpoint in Azure?
50.	How do you refer to Key Vault secrets in GitHub Actions?
51.	What are all the DevOps tools you've worked with?






















Mirafra Software Technologies Pvt. Ltd
1.	Introduce yourself and explain your current project along with your day-to-day work.
2.	Have you worked on Jenkins and if yes, open notepad and write a CI/CD pipeline code.
3.	Have you worked on GitHub Actions and if yes, open notepad and write a CI/CD pipeline code.
4.	What is the difference between git pull and git fetch?
5.	How do you view the commit history in Git for the last 5 commits only?
6.	What is a merge conflict in Git and how do you resolve it?
7.	What is the difference between git reset and git revert?
8.	What is the purpose of the git stash command?
9.	What is the difference between git merge and git rebase?
10.	What type of branch strategy do you follow in your team?
11.	Write a Terraform code to create a virtual machine. What logic would you use if you need to add 10 VMs?
12.	What is Terraform lint?
13.	How would you deploy Terraform infrastructure through a pipeline?
14.	Do you have experience with shell scripting or Python?
15.	What are the commonly used commands or operations you perform using shell scripting?












TechRBM:

1.	I have a developed project locally with Node API, Kafka services, Zookeeper, and PostgreSQL. How do I deploy this project on Azure using a secure gateway?
2.	How do I incorporate AKS (Azure Kubernetes Service) and a Load Balancer into this deployment?
3.	What are App Services in Azure Cloud?
4.	How would you use Azure App Services to deploy an application?
5.	Explain the differences between microservices in the context of your project.
6.	What are some best practices to secure microservices communication on Azure?
7.	How would you manage data persistence for PostgreSQL in a Kubernetes environment on Azure?
8.	How to set up Kafka and Zookeeper on AKS with secure access?
9.	How do you configure the Azure Load Balancer for your AKS cluster?
10.	What is an Azure Secure Gateway, and how does it integrate with AKS?














"Altimetrik"
1. How do you Enable monitoring in AKS?
2. How do you implement zero-downtime deployments in Kubernetes?
3. How you Monitor the infra logs ?
4. Your app is not reachable via Ingress. How will you debug it?
5. how you manage the secrets using Azure services?
6. Why we using terraform?
7. How you will manage if somebody run terraform destroy command ?
8. How you manage Hardcode secrets?
9. What are Docker volumes and how are they different from bind mounts?
10. In which language you have scripting knowledge ?











Tech Mahindra - Tech Lead

1.	Introduce yourself.
2.	Do you have experience in Azure infrastructure at the administrative level, particularly in troubleshooting?
3.	Do you have experience in Docker, Kubernetes, and YAML?
4.	Scenario-based: How would you suggest to the customer whether to deploy their application on a VM or in a container?
5.	What are the components of a Kubernetes cluster?
6.	How would you deploy an application to Kubernetes?
7.	If your Terraform state file got deleted, how would you recover it?
8.	Explain the git import command.
9.	How do you create multiple resource groups at multiple locations using Terraform?
10.	How do you create a Grafana dashboard? Have you created any?
11.	How do you configure alert messages for a VM in any monitoring tool?
12.	Do you know about environment variables in Azure?
13.	What are the types of agents in Azure DevOps?
14.	What do you understand by a trigger in a pipeline?
15.	How much will you rate yourself in Python out of 5? (I’ve rated 3/5)
16.	What is OOPS?
17.	What are the 4 pillars of OOPS?
18.	Tell me what is polymorphism?
19.	Where have you used Python?
20.	Tell me which version of Kubernetes are you using?
21.	Have you deployed an AKS cluster?
22.	What are the default namespaces created after AKS deployment?
23.	Which tools are you strong in? (I’ve told them Terraform, Docker, and Pipeline)
24.	Write a script or code to deploy 100 VMs.
25.	Tell me about your current project.
26.	Explain the strategy and architecture overview of your project.
27.	Have you designed LLD and HLD? Which approach do you prefer?
28.	Have you done any certification?
29.	Suppose we have to migrate on-premise infrastructure to any cloud, how would you migrate? Explain the workflow and process.
30.	Have you worked on security solutions?
31.	How will Key Vault integrate with the pipeline?
32.	Write a Terraform code for creating 10 Linux VMs.
33.	What is the lifecycle of Terraform?
34.	We have multiple environments; how do you pass the variables? Please write the command.
35.	Please explain the complete workflow for Terraform automation.
36.	What is a module and where do we store the state file? Why do we use Blob storage in Terraform and not file share?
37.	Have you worked on Azure Functions? What is the use case?
38.	What are the options to backup data? Do you have an idea about S3 bucket and Storage Account?
39.	How can we transfer data securely from on-prem to Azure?
40.	How do you rate yourself in Terraform?
41.	What is the use of provisioners in Terraform?
42.	What is a page blob and how can we access a storage account?
43.	Have you deployed any cloud-native NVA?
44.	How proficient are you in PowerShell?
45.	Have you worked on moving resources?




















DXC Technology 

1.	What is the CI/CD flow?
2.	Do you work with infrastructure pipeline or application pipeline?
3.	What kind of pipeline do you use? Classic or YAML?
4.	What kind of strategy do you use in Git?
5.	Tell the difference between classic and YAML pipelines.
6.	What Azure services have you used?
7.	Tell the difference between Load Balancer, Application Gateway, and Traffic Manager.
8.	How do you manage different environments?
9.	Do you know about Kubernetes?
10.	What is blue-green deployment? What happens if it fails? Is there any downtime?
11.	What is an artifact?
12.	What do you use to store artifacts?
13.	Can you work with application pipelines?
14.	What language or framework do we use in frontend and backend?
15.	Can you build software with developer code and integrate it with CI/CD?
16.	Git questions: Explain pull, fetch, PR, and Git conflict with scenario-based examples.















Infosys

FIrst Rount
1-Pod me security policy kaise lagainge
2-AKS pe kaam kiya hai kya
3-Pipeline kaise banaoge terraform k through
4-SCM versioning kaise karte ho
5-Agar pod me 512 ki limit hi to kaise banaoege Pod
6-There 3 node A,B,C Agar C node ka utilizaiton 90%, or ham pod bana k deploy kar rhe hain to wo node c me hi ja rha hai to ise kaise sahi karoge
7-What is Terraform Registry
8-What is namespace
9-What is taint
10-Which Azure Service are you using
11-.tfstate file ko kaise security provide karte ho
12-Agar koe resource Azure Portal pe hai but .tfstate file me nhi hai to use kaise leke aoge .tfstate file me
13-Terraform me Module kya hot
1.	Tell me about yourself?
2.	Tell me Azure DevOps features?
3.	How do you handle secrets in CI/CD?
4.	What is the difference between Azure Repos and Azure Boards?
5.	How do you push code to Azure Repos?
6.	What kind of applications or plugins can you use in Azure DevOps?
7.	How do you provision infrastructure?
8.	Tell me key features of Terraform?
9.	Tell me the difference between terraform init, plan, and apply?
10.	Why do we use Terraform and what are its benefits?
11.	Have you worked with Azure Web App Services?
12.	Tell me about your daily routine?
13.	Do you also work with PaaS services?
14.	Tell me how you would provision a SQL database?
15.	Why do we use SQL PaaS service instead of SQL on VM?
16.	If a database is deleted, how can we recover it in PaaS?
17.	How can we connect SQL database with application? Why do we do that?
18.	Do you know about replica sets?
19.	If a new engineer comes to your team, how will you give permissions on Azure DevOps?
20.	What level of permission will you give?
21.	One developer or user is not able to connect to your production server VM, what steps will you take to troubleshoot?
22.	Tell me about Log Analytics or Application Insights?
Have you worked on disaster recovery?

Infosys FIrst Rount

1-Pod me security policy kaise lagainge
2-AKS pe kaam kiya hai kya
3-Pipeline kaise banaoge terraform k through
4-SCM versioning kaise karte ho
5-Agar pod me 512 ki limit hi to kaise banaoege Pod
6-There 3 node A,B,C Agar C node ka utilizaiton 90%, or ham pod bana k deploy kar rhe hain to wo node c me hi ja rha hai to ise kaise sahi karoge
7-What is Terraform Registry
8-What is namespace
9-What is taint
10-Which Azure Service are you using
11-.tfstate file ko kaise security provide karte ho
12-Agar koe resource Azure Portal pe hai but .tfstate file me nhi hai to use kaise leke aoge .tfstate file me
13-Terraform me Module kya hota hai and how you are using that in Terraform in different environments.

Infosys L2 Round:
1.	Tell me about yourself
2.	Tell me the CICD pipeline for your application
3.	What are the errors you got in K8s in PROD environment for your pipeline
4.	Explain ConfigMap and Secrets in k8s. share screen and write the logic.
5.	How you will integrate data in keyvault with application running in pods.
6.	Have you worked on Azure Datafactory (ADF )Pipeline.
7.	We are getting a flood of alerts for deployment issues, how you will minimize the alerts in Grafana
8.	My all jobs are running on slave 1 of Jenkins. How to migrate all jobs to slave2 ?
9.	What is CAVE in DevOps
10.	Azure application Insights
11.	Azure web app services
12.	Usage of Nat Gateway
13.	No questions from Terraform

First round: 
1- introduction.
2- GCP hierarchy.
3- questions with cloud build,registry and DR.
4- migration and best practices.
5- cloud services like: compute enginge, cloud run, function, pub-sub, triggers, vertex AI
6- core networking concept and fundamental of IAM.
7- project description and questions from it.

2nd round:
1-intro
2- GKE( deep granular questions).
3- troubleshooting from above services perspective
4- security and CDN approach.
5- scenario based question in regard of architectural view 
6- write down terraform code for VM and GKE and describe folder structure.
7- git lab and GitHub actions.
GKE deployment and network policy yaml
9- blue green strategy and its working along with yaml sample.
10- questions related with Mongodb Saas solution and integration with GCP.
Tell me about yourself
Tell me the CICD pipeline for your application
What are the errors you got in K8s in PROD environment for your pipeline
Explain ConfigMap and Secrets in k8s. share screen and write the logic.
How you will integrate data in keyvault with application running in pods.
Have you worked on Azure Datafactory (ADF )Pipeline.
We are getting a flood of alerts for deployment issues, how you will minimize the alerts in Grafana
My all jobs are running on slave 1 of Jenkins. How to migrate all jobs to slave2 ?
What is CAVE in DevOps
Azure application Insights
Azure web app services
Usage of Nat Gateway













Company -Dynpro 
Client -IBM
1-Introduce yourself .
2-what is artifact.
3.where you store your artifact .
4.what is ACR.
5.Tell me about CICD process.
6.how will you write stages in yaml CICD.
7.Do you know about keyvault.
8 .How will you fetch your secret and credentials from key vault .
9.Do you know about storage classes.
10.what is state file in terraform.
11. An application is running on VM if this VM is crases then How will you recover this VM.
12. If a resource created in Azure portal then how will you show in state file.










BETSOL - Cloud Engineer - Round 1

Tell me a brief about yourself technical experiences and tools you've used.

2. So, what are the services you've created?

3. Let me give you a scenario, we have got a requirement to deploy an application having backend not to be accessible from internet, DB not public and Frontend that to be accessible to the end users ,how will you architect this ?

4. Suppose we want to create another VM in that particular VNET , would we be able to restrict this VM to access all the other VMs in that VNET ?

5. How did you configured NSG and firewall?

6. How have you used app services? 

7. How did you actually configured custom DNS on this app service?

9.	Have you used keyvalults ? What purpose did they serve for your project use case ?
10.	10. Have you also worked on Terraform? How did you manage to store state file ?
11.	What is this state file ?
12.	Suppose I want to peer two VNETs one to be created using Terraform, another one already created on azure. How will fetch the information of VNET that is already on azure to complete this peering configuration ?
13.	Can you list down a few linux commands along with what purpose they serve ?
14.	Can you explain chmod command, how the digits decide the permission? Or is there any other way to change permission using chmod only?
15.	How did you created service principle?
16.	Can you explain me difference between RUN ,CMD and ENTRYPOINT in dockerfile?
17.	What are the services, deployment, ingress ,egress , secret have you used ?
18.	Have you used logic app or function app ?
19.	How did you give permission to the service principle to use the keyvalult ? What are different ways to assign role to the user or service principle?



Hexaware 1st Round Interviewer Name Tamilarasan

1 Tell me about your self and your roles and responsibility on previous Project?
2  What are DevOps tools you have work?
3  Can you explain your previous project u have work?
4  Can u explain any one azure DevOps pipeline which u have created?
5  Can u explain the stages and what are the jobs executed on the pipeline?
6  What are the environments and how many environments in your projects?
7  coming to pipelines I need to checkout my code from multiple repositories over to do that
8  I have multiple repositories A and repositories B when running my pipeline and deployment I need to fetch the code from both the repositories A and repositories B how we do that?
9  How the agents were configured in your environments like self hosted agent or your going VMs?
10 What are the different types of deployment strategy which use in your projects?
11 What is canary deployment?
12 What are different types of probes in Kubernetes?
13 What are health Probes in Kubernetes?
14 How are u integrate azure key vault with azure Kubernetes?







Wipro L1+L2 interview questions

1.	what are provisioners? What are advantages of runners ?
2.	Dynamic block in terraform ?
3.	Explain terraform state file ? How it helps in production environment ?
4.	Terraform import?
5.	How will you manage reusable resources in terraform ?
6.	How do you manage secrets in your pipeline ?
7.	Why you use Terraform ? why not Ansible ? Which will you choose ?

8.	What is reusable function  or workflow in github action ?
9.	What are github runners ?
10.	Have you written Dockerfile ? Please write for a web application.

11.	What is CICD ? Explain CICD pipeline? 
12.	what are the issues you faced in deployment and how you solved ?
13.	How to do rollback for application deployed kubernetes ?
14.	What happens to k8s cluster when load or traffic increases?
15.	Difference between deployment and statefullset ?
16.	What are all the errors you have faced in during deployment in k8s ?
17.	Have you worked on Jenkins ? what is shared libraries in Jenkins ?
18.	How have you managed credentials in Jenkins ?
19.	Azure load balancer ?
20.	Azure App services ? 
21.	What is the role of nodepools in AKS ?
22.	What you will suggest to customer either App services or AKS ?
23.	Can you explain a scenario where you used a service mesh in kubernetes, especially in  terms of authentication and authorisation?
24.	Have you worked on PowerShell or Shell Script ?
25.	Write a script to delete files older than 7 days ?
26.	Have you implemented Prometheus , Grafana or any other monitoring tool ?
27.	Are you aware of logging properties which are used in these monitoring tools?
28.	Are you aware of any database ?
29.	What is NoSQL DB ?
30.	What is TSDB (Time Series DB) ?
31.	How do you connect your database with your application ?






ACCOLITE

1.	What is a Terraform state file?
2.	Are you storing the state file in local or remote storage?
3.	If you are storing the state file in remote, then where and how are you storing it?
4.	Suppose you want to make changes in the state file — how can you do that safely
5.	Explain the remote backend and its purpose in Terraform.
6.	What is state locking in Terraform, and why is it important.
7.	What is the modular approach in Terraform, and how have you implemented it
8.	If infrastructure resources are already created manually, how do you import and manage them using Terraform.
9.	What are some Terraform libraries or providers you have worked with.
10.	How are you managing secrets in your infrastructure.
11.	Explain the use of Azure Key Vault and how you integrate it with your deployments.
12.	What is the difference between AKS and ACR.
13.	What is the difference between a Deployment and a StatefulSet in Kubernetes.
14.	Explain the end-to-end deployment flow to AKS using Terraform and CI/CD.
15.	How do you handle backup and disaster recovery.
16.	How do you manage local and remote codebases in your projects?
17.	Explain the basic flow of your CI/CD pipeline.
18.	What branching strategies do you follow in your team?
19.	Explain the trunk-based branching strategy.
20.	What are the security best practices you follow in your infrastructure and CI/CD pipelines.
21.	Do you know scripting or Python.









CGI interview-pratik
1.	since you have team of 7-8 member how you are managing the state file.
2.	since you told 2 person is working on terraform suppose same two person create the same resource group or else accidential delete it how you should handle it.
3.	how you are managing the state file.
4.	are you pushing the code to remote or keep it in local.
5.	why you are using terraform not other tools like bicep.
6.	what is state file.
7.	which branching strategy you were using.
8.	how you troubleshoot the issue in your vm.
9.	how you can check the cpu utilisation.
10.	have you deploy an application on window server explain all the step.
11.	explain about the monitoring tools how you check that if any issue occurs. 






















Publicisresources

1. Tell me about your self and your day to day activity
2. which tool you use for pipeline 
3. which type of agent you are using selfhosted or azure 
4. why you use selfhosted not azure based 
5. how many agent you are configuring in your current org
6. Tell me some thing suppose you configure 6 selfhosted agent in org and suppose 12 developers trigger pipeline same time how can you manage 6 agents  7.  how will mange the networking in the azure 
8. so when u create the vnet so in the vnet u creat 2 subnet one is public and one is private so how to configure it 
9. what is the internet gate way
10. what is a function app 
11. how many services are using in current org
12. how to give a reader access for comos db and what is the name of that role 
13. suppose that while we running the pipeline to the azure and is through the error that your pipeline doesn't have  authorization to run this pipeline  what could be the possible cause 
14. there is an environment in azure doveps so way we use that environments in azure devops.
15. suppose u create a data base we need to keep that DB access privately not Public so how would u ensure that  
16. what type of redundancy option you have
17. which massage services u worked on in azure








Propel Noblq

1.	Tell me brief about yourself.
2.	What is virtual network?
3.	What is subnet?
4.	What is NSG (Network Security Group)?
5.	What is a load balancer?
6.	What is application gateway, and how is it different from a load balancer?
7.	What is VMSS (Virtual Machine Scale Set)?
8.	How would you block an IP in firewall for outbound traffic?
9.	What are endpoints? What is the difference between service endpoints and private endpoints?
10.	Do you have experience in PostgreSQL?
11.	How would you take backup of PostgreSQL database?
12.	What is VNet peering?
13.	What is a virtual network gateway?
14.	How would you connect on-premises network to cloud?
15.	How would you temporarily elevate permission for a user in Azure?
16.	Difference between build and release pipeline?
17.	How do you publish artifacts?
18.	What are artifacts?
19.	What are agents in pipeline?
20.	What is private link in Azure?
21.	How do you keep secrets in pipeline?
22.	Could you explain the key components of the Kubernetes control plane and their respective roles?
23.	How would you differentiate between a Pod, a ReplicaSet, and a Deployment in Kubernetes?
24.	What is the standard approach to performing a rolling update in Kubernetes while minimizing service disruption?
25.	In what scenarios would you choose a StatefulSet over a Deployment, and why?
26.	What is the purpose of kube-proxy in a Kubernetes cluster, and how does it function?
27.	Can you describe the role of Ingress in Kubernetes and how it differs from a standard Service?
28.	How would you systematically troubleshoot a pod that is stuck in a CrashLoopBackOff state?
29.	What deployment strategies do you recommend to ensure zero downtime during application releases?
30.	How do you typically structure a CI/CD pipeline to support multiple environments such as development, QA, staging, and production?
31.	If a pipeline's unit tests fail immediately after a commit, what steps would you take to identify and resolve the issue efficiently?
32.	What methods do you use to pass artifacts or variables between stages in a CI/CD pipeline?






Accenture
1.	What is peering?
2.	What happens with the route table when you peer the virtual network?
3.	What do you understand with CAF?
4.	What is landing zone?
5.	What do you understand with azure application gateway?
6.	What is listener in application gateway?
7.	What is flow of application gateway in traffic is coming from end user?
8.	How much are you comfortable with terraform?
9.	Can you create azure application gateway with its all component via terraform?
10.	Can you create 3 virtual machine and their disk via terraform how will you approach this scenario?
11.	What do you know about devops?
12.	If I have some code and it is infra code how do you push using git what will be the commands?
13.	How do you create pipeline in azure devops?
14.	Do you know ansible/puppet?
15.	Do you have knowledge about any scripting language?
16.	Can you create end to end landing zone using terraform, there are two landing zone platform and application. What are the steps for platform landing zone via terraform?
17.	What are other devops tool you use?
18.	scenario based questions regarding private dns resolver, private dns zone and endpoint
19.	do you know python?
20.	how to patch linux and windows vms
21.	how to create linux lvm volume and some other as well.














United Layer (Unity Cloud) 

1. Tell me about yourself, day to day activities and skills you have

2. What are the cloud you've worked with ?

3. Any other cloud than Azure ?

4. What are the resources you've provisioned on azure ?

5. How do you write configuration in Terraform, tell me the architecture 

6. What are different commands you use in Terraform?

7. Explain me about different components of Terraform 

8. Tell me about workspaces in Terraform 

9. How do you manage different environments ?
10. How do you keep secrets in Terraform?

11. Can we keep secrets in local and access them ? Are they secure ?

12. What is state file? Tell me about state locking and how they are related

13. What is backend in Terraform?

14. Let me give you a requirement, I want to create a VM and then install few applications like docker ,etc. automatically .I want to use a load balancer and cluster IPs. How will you provision this ?
15. Do you have any experience with Ansible?

16. Is the data you fetch using data block from keyvalult encrypted?

17.  How did you do Containerization? What applications were you using?

18. How did you deployed the containers ? Were you using kubernetes?
19. What are the different cloud providers supported by Terraform, give me 5-6 names 

19.	What are private cloud providers supported by Terraform ?
20.	What is private module in Terraform?
1. Can you share your screen and draw k8s architecture, explain it while drawing 

2. How do you ensure High Availability?

3. If my computer goes down ,what will happen if k8s cluster is deployed?

4. Have you configured k8s in Bare metal?

5. Have you done code ?

6. What Scripting have you used ? Can you write a code to print date and time ?

7. Have you used loops in script code ?

8. Have you used ansible?

9. What security practices do you ensure while writing Terraform code ?












Hexaware
Panel - anup singh
1.	Introduce yourself.
2.	Your day-to-day activities.
3.	Explain your transition to DevOps.
4.	What are Agile ceremonies?
5.	How long is your sprint and how does it start?
6.	How many IPs are available in 192.168.1.0/32?
7.	What is Azure Bastion and what does it do?
8.	What is a Virtual Network (VPC) and how do you use a child module for it?
9.	What is VNet peering?
10.	What is Azure Key Vault? What default permissions are given to a user?
11.	What is a Service Principal and service connection?
12.	What is Azure Repos and service connection?
13.	What is a null resource?
14.	What is a data source?
15.	What is a module?
16.	You have modules for 3 environments. How do you execute the dev environment?
17.	If a storage account was created with Terraform, teams used it and now you want to modify it, what will happen?
18.	What is Terraform lifecycle?
19.	Difference between count and foreach in Terraform.
20.	Write Terraform code to create a resource group.
21.	Write Terraform code to provision Azure Key Vault secrets and how to access them in Terraform.
22.	How do you provision the whole infrastructure using Terraform?
23.	How do you execute your Terraform pipeline in Azure DevOps? (Write YAML steps)
24.	How to call a specific .tfvars file like prod.tfvars from multiple tfvars files?
25.	Where do you store Terraform state file and why prefer blob storage over file share?
26.	Write a YAML pipeline (application pipeline).
27.	What is a variable in YAML pipeline?
28.	How do you handle secrets in CI/CD pipelines?
29.	What are artifacts? How do you publish them?
30.	What are agents in pipelines?
31.	How do you deploy Node.js using Azure DevOps pipeline?
32.	How do you integrate AKS/ACS in infrastructure using Terraform?
33.	How do you deploy containers to AKS using Azure DevOps?
34.	How do you add storage to pods in Kubernetes?
35.	How do you manage different environments in CI/CD pipelines?
36.	How do you rollback in GitHub Actions?
37.	What kind of pipelines do you use—classic or YAML?
38.	What kind of branching strategy do you use?
39.	What is Docker and why do you need it if you already have VMs?
40.	Write a Dockerfile to create a custom image.
41.	What is the difference between Docker image and Docker container?
42.	Write YAML files for Kubernetes Service, Ingress, Pod, and Namespace.
43.	What is Kubernetes and explain different services in Kubernetes.
44.	What is a pod?
45.	What is ReplicaSet?
46.	How do you manage external access to services in Kubernetes?
47.	How do you reduce downtime during Kubernetes deployment?
48.	What are considerations for designing a Kubernetes cluster?
49.	What is autoscaling strategy in Kubernetes?
50.	Write some common kubectl commands.
51.	Do you have experience with scripting languages like PowerShell or Bash?
52.	Write a Bash script to find and remove old files from a VM.
53.	Write a Python script that swaps ‘a’ with ‘c’ and ‘c’ with ‘a’ in a given string.
54.	Application suddenly stops — how do you check?
55.	One developer cannot connect to production VM — what steps do you take?
56.	Scenario-based questions on database processing.
57.	How do you troubleshoot pods stuck in CrashLoopBackOff?
58.	Provide an example of resolving a conflict in a cross-functional DevOps project.
59.	How do you explain deployment to non-technical stakeholders?
60.	What is SLA in Azure?
61.	What is Harness?
62.	What is a remote backend in Terraform?
63.	What is continuous integration vs continuous deployment vs continuous delivery?
64.	What is Canary deployment and Blue-Green deployment?
65.	What is the role of cloud in DevOps?
66.	How do you migrate on-premise applications to cloud?
67.	How do you keep secrets in a pipeline?
68.	What is the difference between build and release pipeline?









Cognizant 
1.	Please introduce yourself and explain your day-to-day activities as a DevOps Engineer.
2.	What is your current organization and what is your role there?
3.	Have you worked on Kubernetes? If yes, what tasks did you handle?
4.	What is the Terraform taint command and what is its use case?
5.	What is the typical Terraform directory structure you follow?
6.	How do you write Terraform code for reusability?
7.	How do you handle zero-downtime infrastructure upgrades using Terraform?
8.	Do you have any idea about the lifecycle argument in Terraform?
9.	What is a null resource in Terraform and when do you use it?
10.	Please explain the CI/CD pipeline process in Azure DevOps.
11.	How do you integrate GitHub with an Azure DevOps pipeline?
12.	How do you create a service connection between GitHub and Azure DevOps?
13.	What Azure DevOps resources have you worked with?
14.	Have you connected two VNets in Azure? What are the different methods to connect VNets and their differences?
15.	Explain your AKS load balancer experience.
16.	How to configure network policy in Kubernetes?
17.	What are the different types of cluster storage? How do you configure cluster storage?
18.	What is the best practice for managing identity control in cluster policies?
19.	What is the difference between Azure CNI and Kubernetes CNI?
20.	Explain about logs in Kubernetes or Azure DevOps context.
21.	From a DevOps perspective, how does Azure DevOps interact with other services?
22.	What is deployment approval and gate approvals in Azure DevOps?
23.	How to design a CI/CD pipeline using Azure DevOps methodology?
24.	Explain the key concerns of microservices architecture.
25.	What is scaling in Kubernetes or infrastructure context?
26.	What is a high availability setup?
27.	What are different Disaster Recovery (DR) options available?
28.	What is ED to PC?
29.	What are multiple tenants in Azure or cloud context?
30.	What are ESC Tools?
31.	What is AKS patch management?
32.	How do you use regular expressions for redirection tools?
33.	What are common troubleshooting steps you follow?
34.	What is the difference between CNI and cluster networking?
35.	How do you configure policies of a Kubernetes cluster?
36.	What is an EKS Cluster?
37.	How do you create a Kubernetes cluster?
38.	What is VNet peering?
39.	Have you worked with Azure Front Door (AFD) and Application Performance Management (APM)?
40.	Have you worked on any databases?
41.	How did you connect a database to your local machine for testing or development?
42.	What types of queries have you used in the database? Can you give some examples?


1.Introduce yourself
2. Day to day activity 
3. Recent issue faced
4. Cicd architecture 
5. If any junior resources committing client secret how you will manage it
6. Ask me to write terraform code of any resources 
7. Terraform command
8. Where you manage ssl certificate 
9. Step to create pipeline 
10. Explain module structure of code


















EY

1.	Write a code for virtual machine to import resource group name which already exists in your cloud with the help of data block.
2.	Suppose your colleague created a resource in cloud; how do you match your Terraform code and tfstate file?
3.	How do you manage different workspaces in your Terraform?
4.	What are the best practices you follow to make resources highly available and redundant in Terraform code and block to avoid accidental removal?
5.	Have you worked on GitHub Actions?
6.	What is the lifecycle of Terraform?
7.	What is a Docker image?
8.	Have you worked on Ansible?
9.	How do you reduce the size of a Dockerfile while deploying pipeline?
10.	How do you check layers of a Dockerfile and troubleshoot?
11.	How do you troubleshoot Docker containers?
12.	Have you worked on Kubernetes?
13.	Apart from Azure side, what DevOps areas have you worked on?
14.	Have you worked on pipelines or do you have only an overview?
15.	Are you proficient with IaC tools like Bicep or Terraform?
16.	Have you worked on GitLab pipelines or Azure DevOps pipelines?
17.	Please explain your day-to-day activities for GitHub Actions pipeline.
18.	How are you deploying the environment—manually or automated?
19.	What kinds of migration have you done: refactoring or lift and shift?
20.	For refactoring, are you using Terraform?
21.	What checks do you perform before starting a migration to assess client environments?
22.	Please define the end-to-end cycle of migration.
23.	After accessing customer environments, do you directly start replication or start planning? Explain the planning phase.
24.	Suppose you have 2000 servers to migrate. How do you plan to migrate—migrate all at once or use another strategy?
25.	How do you perform dependency analysis for servers and applications?
26.	If you forgot a batch of servers during dependency analysis, would you start wave migration or something else? Which migration would you do first?
27.	Suppose a client is using on-premise environment and wants to migrate to cloud but is confused. How do you convince them to migrate? What things do you explain to move forward?
28.	What is hub and spoke, and what is the significance of hub and spoke architecture?
29.	What is transit gateway and remote gateway?
30.	Suppose you have 3 VNets: VNetA, VNetB, and VNetC. VNetA is peered with VNetB, and VNetB is peered with VNetC. Only VNetA is peered with the hub network (a separate VNet). Will VNetC be able to access hub resources?
31.	How do you design a three-tier web application on Azure? Include network and security architecture, and what Azure services you would deploy.
32.	When users try to hit the server from outside Azure, which server do they hit, and what security checks do you put in place?
33.	How do you distribute traffic if users are across the globe and need scale sets?
34.	Suppose your infrastructure has 3 tiers (frontend, application, and database). The frontend server is scaled up. How do you manage traffic on the backend and what network services can you use?
35.	What is the difference between Private Endpoint and Service Endpoint?
36.	What is the difference between CDN and Traffic Manager?
37.	What is Point of Presence (POP)?
38.	What is the significance of the Terraform statefile?
39.	What is the ideal way to store the Terraform statefile?
40.	Where do you configure the storage of the Terraform statefile?
41.	How do you handle secrets in Terraform?
42.	How do you access resources with Key Vault in Terraform?
43.	How do you link services to the service principal? For example, if the service principal has Key Vault access and you need to fetch a key from the storage account to decrypt data disks?
44.	How do you define modules in Terraform code? What is the significance of modules?
45.	Write the code for Azure Container Registry (ACR) and how to call it using a module in Terraform.
46.	What is the significance of workspace in Terraform? Why do you use workspace?
47.	What is the use of outputs in Terraform?
48.	Suppose you design pipelines and want to trigger changes on push to the main branch. What do you write in the pipeline code?
49.	What is the difference between self-hosted and Microsoft-hosted agents?
50.	What are the main advantages of using self-hosted agents?
51.	Do you know about templates in pipelines? How do you use them in YAML pipelines?
52.	Have you worked on Kubernetes services? Please explain the Kubernetes architecture.
53.	Why are we using Kubernetes? What is the function of Kubernetes?
54.	What do you understand by orchestration in Kubernetes?
55.	What is a Kubernetes cluster?











xceedance
1.	Suppose a new joiner joins the organization. What access do you give them in Azure DevOps?
2.	We have three different infrastructures and the code is ready in the artifacts repository. How do you approach deployment?
3.	Suppose there are two projects in Azure DevOps for the same VM and same app, and you want a single service connection. How would you achieve that?
4.	Suppose we have two VMs and you have to deploy a service on both at the same time. What approach would you take in a single pipeline to deploy the app simultaneously?
5.	How do you deploy a pipeline for Terraform code? What are the steps you follow?
6.	You have to add a column in a debug sheet. How will you do it in Azure DevOps?
7.	What is the code quality percentage allowed to proceed with the release pipeline?
8.	What is the difference between ADD and COPY commands in a Dockerfile?
9.	What option do you select to add an approver in Azure DevOps pipeline?
10.	Do we need a destroy pipeline for infrastructure? What is the purpose of it?
11.	What is the command to check logs of a Pod?
12.	What tool do you use for code quality check in pipelines?
13.	SonarQube uses different environments. What access do you give in Azure DevOps for your pipeline to check code?
14.	Suppose in your organization there are 10 projects, but a new developer joined. You want to give access only to 3 projects. How do you do that?
15.	How many types of user-level access are there in Azure DevOps?
16.	What is the difference between Basic level and Stakeholder level access in Azure DevOps?
17.	If you want to add more Basic users in Azure DevOps, do you need to pay Microsoft? How much?
18.	How many agents are available in Azure DevOps to run pipelines?
19.	What is the difference between Microsoft-hosted agents and self-hosted agents?
20.	If Microsoft provides only one agent and you want to run 10 pipelines, how much money do you have to pay for additional agents?
21.	How do you add a new field in the Bug template in Azure DevOps?
22.	When a user enters the correct username and password but gets an invalid credential error, what could be the issue?
23.	Suppose you want to deploy an application to 2 VMs at the same time. How would you do that using Azure DevOps pipeline?
24.	What is a service connection in Azure DevOps and how do you use it for VM deployments?
25.	Is it possible to share the same service connection across multiple projects in the same organization? How?
26.	How do you handle different environment deployments (DEV, QA, PROD) in pipelines with different credentials?
27.	Can you use Dockerfile instead of YAML for CI/CD? Explain.
28.	Suppose you have 2 containers and the second container should run only after the first one has started. How do you achieve that in Docker Compose?
29.	If all secrets (like DB name, username, passwords) are stored in Azure Key Vault, how do you fetch those in the pipeline while building a Docker image?
30.	What is the difference between COPY and ADD commands in Dockerfile?



HCL

1.	What is dependency > implicit and explicit? Share the syntax and chart.
2.	What is the move block in Terraform?
3.	What is a state file and where can we store it?
4.	When is the state file created?
5.	What is a lock file and why is it created?
6.	What is the difference between variable.tf and variables.tf?
7.	What is terraform.tfvars?
8.	What is a service connection?
9.	What are the things required while creating a service connection?
10.	What is Basic in Azure DevOps (ADO)?
11.	What is Stakeholder in ADO?
12.	What are the security best practices in ADO?
13.	What is dependency > implicit and explicit?
14.	How do you manage multiple subscriptions?
15.	What is the difference between VM and VMSS?
16.	If there is a requirement to create two VMs and two databases, which approach will you follow: VM or VMSS?
17.	Suppose you have 1500 subscriptions; how will you manage them from Azure DevOps level?
18.	As an architect, if you want to set up infrastructure, what will be your approach to provide a solution to the customer?
19.	What is a linter in Terraform?
20.	What is a task group?
21.	What is a deployment group?
22.	What is Azure DevOps?
23.	What is a sprint and work item?
24.	How can you secure Azure DevOps?
25.	What is variable.tf and terraform.tfvars?
26.	What is the output block and how do you pass this into a pipeline?
27.	If you have a Terraform code till VM and you applied terraform plan and apply but want VM result in JSON format, what is the command? (Tell me the command only)
28.	What tools are used for pipelines?
29.	What are provisioners in Terraform?
30.	If you mark a variable as sensitive in Terraform, how do you see this variable in the state file?
31.	If you pass the value hardcoded in VM, will it show in terraform plan or not?
32.	What is a move block?
33.	Will move block impact our current infrastructure or not?
34.	Give an example of a recent template upgrade in Terraform.
35.	What data types are you familiar with in Terraform?
36.	After which command is the state file created?
37.	What is the stage where Terraform downloads modules and providers?
38.	What backends are you familiar with?
39.	How do you encrypt the state file?
40.	You are creating a variable in Terraform and need to provide its default value. What argument will you declare?
41.	You have a VM created through Terraform and installed Microsoft Office after VM creation. If you run terraform apply again, what will happen to Microsoft Office?
42.	What are lifecycle rules in Terraform, and where are they declared?
43.	What are dependencies in Terraform?
44.	What are gates in Azure DevOps?
45.	Is macOS supported as an agent pool?
46.	In Azure, what is an availability set?
47.	How many types of variables are declared and stored?
48.	What is the provisioners block? How many types and when do you use it? Give examples.
49.	What is Ansible and why do we use it?
50.	Tell use cases combining Terraform and Ansible.
51.	A new feature is not present in Terraform. How would you provision it in Azure portal through Terraform?
52.	You manually created 10 VMs in different resource groups, and now want to automate it using Terraform. How do you update the state file for existing resources?
53.	Terraform backend and state file management?
54.	To validate Terraform code, do you need to execute terraform init?
55.	Share your experience in CI/CD pipelines and tools used.
56.	Have you used GitHub Actions in CI/CD?
57.	Have you worked on GitHub Actions?
58.	Do you have experience in Terraform?
59.	Rate yourself on CI/CD pipelines out of 5.
60.	Have you worked on Docker?
61.	Have you worked on Kubernetes?
62.	When do you suggest Docker and when Kubernetes for deployment?
63.	Rate yourself in Docker out of 5.
64.	Rate yourself in Kubernetes out of 5.
65.	Rate yourself in Terraform out of 5.
66.	Are you using Helm charts?
67.	Rate yourself in Helm charts out of 5.
68.	Among AWS, GCP, and Azure, which are you most comfortable with?
69.	Have you deployed Docker and Kubernetes related deployments in Azure?
70.	What Azure services have you used?
71.	Rate yourself in Azure out of 5.
72.	You have Python automated scripts to automate testing during deployment. How do you write test scripts that run on Docker containers and push the build to remote repo once tests pass?
73.	Have you used any monitoring tools?
74.	How have you used Prometheus and Grafana and for what activities?
75.	Rate yourself in Monitoring and Observability out of 5.
76.	Have you heard about vulnerability scanning?
77.	How do you integrate vulnerability scanning for automated security checks?
78.	Have you implemented any security measures or tools?
79.	Rate yourself in Security & Compliance out of 5.
80.	In Azure, have you deployed microservices with High Availability and Disaster Recovery strategies?
81.	You have 20 microservices in Docker. How do you check the health status of each service?
82.	Rate yourself in Disaster Recovery and High Availability out of 5.
83.	Have you worked on version control tools like Git? What are your daily activities?
84.	Rate yourself in Version Control out of 5.
85.	Have you worked on Dockerfiles?
86.	What scripting languages have you worked with and which are you most proficient in?
87.	Can you share your screen and open a compiler or interpreter?
88.	Rate yourself in scripting out of 5.
HCL Tech (Client name : Maruti)
Azure L3 Support
second Round interview questions
1.	Define Hub & Spoke Architecture, can you brief.
2.	How many hub VNets do you need to support 10,000 spokes?
3.	If you peering a hub and spoke vnet , what options do you select in hub sides to peer with the remote or spoke vnet?
4.	To establish the site to site connection what information do we need?
5.	What is BCDR? and what options are available in Azure?
6.	Difference between BCDR & DR?
7.	For cost optimization as a consultant or an architect what options will you provide to customer?
8.	Have you used any third party or Azure tool to minimize the cost?
9.	What types of resources you have created through terraform?
10.	Explain ASG & NSG?
11.	How do you troubleshoot when the VM status is not coming up?
12.	Azure VM Status = Running, but RDP not working (No response / timeout / unreachable). How would you troubleshoot?
13.	In pipeline if your deployment fails, how will you handle that?
14.	How would you rollback your pipeline?
15.	Do you know about well architect framework?
16.	Five pillars of the Landing Zone.
17.	Types of Load balancer. Explain them.
18.	I have a public DNS Zone & Private DNS Zone, what will be the differentiation if you see from your side?
19.	What are the Network Access Setting for storage account? explain them.
20.	Have you created private endpoint for storage account?
21.	We have VM, storage account, SQL DB, Azure App service all are running under a same subnet and private endpoint for your storage account. How will your VM recognise that storage account FQDN? 
22.	There are certain security alerts come within Azure. How would you handle those alerts?
23.	Have you created backup of the VMS, What policy you are applying for this?
24.	Suppose your one vm crashed, you are not able to access, then how will you take the backup of that vm?
25.	MABS or MARS agent for backup
26.	Backup retention policies
27.	How will you make the AKS as private?
28.	Why we are using ingress controller?
29.	Have you used retry logic in the pipeline?
30.	What are the agents that you are using to run the CI/CD pipeline?
31.	What is the advantages of self hosted agent?
32.	Do you know about well architect framework?
33.	Five pillars of the Landing Zone.











Neosoft ltd pune

1.	What are the types of load balancers?
2.	What is the difference between ASG and NSG?
3.	What is Azure Firewall?
4.	What is the lifecycle of Terraform?
5.	How do you maintain different workspaces in Terraform?
6.	Can we implement NSG on VNet, Subnet, or at Virtual Machine level?
7.	How do you reduce the size of a Dockerfile?
8.	What is the use of CMD in Docker?
9.	What does the output block in Terraform do?
10.	How do you manage manually created resources in your Terraform pipeline?
11.	Application load balancer uses which protocol?

Neosoft - first round 

12.	tell me about yourself
13.	which cloud do you use ? 
14.	Have you worked with AWS ?
15.	can we resize EBS size ?
16.	how to attach EBS in EC2 instance ?
17.	how to decrease EBS size if it underutilize ?
18.	what other services you have used in AWS ?
19.	tell me about Load balancer in AWS?
20.	tell me about cicd work flow?
21.	what is CI and what tools are you using in cicd ?
22.	what is SonarQube ? 
23.	what parameters have you set to scan code in sonarqube?
24.	do you know about Kuberentes and docker ?
25.	what is docker and container ?
26.	how to check system utilization of container ?
27.	what is Kubernetes ?
28.	how to troubleshoot in Kubernetes ?
29.	how to troubleshoot pending state of container?
30.	what is crashlookback ?
31.	what is  ooemkilled ?
32.	what is liveness and readiness probes ?
33.	what is request and limit ?




Puresoftware 
1.	tell me about yourself ?
2.	what is difference between docker and VM ?
3.	how do you deploy new update on Kubernetes and what strategy will use ?
4.	what is difference b/w cmd and entrypoint ?
5.	tell me difference b/w arm, cloud formation and terraform ?
6.	what terraform key feature ?
7.	tell me about cicd ?
8.	share screen and write YAML pipeline  and explain ?
9.	how do you manage secret in YAML?
10.	how do fix storage in Linux if it is getting full, what steps will you take to fix that ?
11.	how to check services and what steps will you take to fix if service getting failed to start ?
12.	what kind monitoring are you familiar with ?
13.	where does terraform state file stores ?
14.	how do you recover terraform state file from local if got deleted ?
15.	what deployment starategies have you worked ?
16.	what is difference b/w ingress vs loadBalancer?
17.	if we want to deploy autoscaling deployment what kind service we will use ?
18.	what strategy by default use by deployment kind ?










Xoriant - DevOps Engineer - Round 1

1. Tell me a brief about yourself and experience 

2. Can you tell me what are the plugins used in Jenkins ?

3. How to enable 2-factor authentication in Dockerhub ?

4. Can you tell me difference between Active Directory and Entra ID currently used in Azure ?

5. How do you connect master and child servers in ansible?

6. Have you worked with Openshift Containerization tool ?

7. Explain the impact of TTL (Time to Live) settings on DNS propagation and troubleshooting.

20.	What are the script have you worked with ?
21.	How is your experience with Git ?
22.	If a script fail due to permission or other issue, how will you troubleshoot it ?
23.	A critical cybersecurity threat is identified in your project’s testing phase. How would you respond to minimize the impact and ensure a secure deployment?
24.	Your organization follows Infrastructure as Code (IaC) principles to manage and provision infrastructure resources for data engineering workloads. How would you incorporate IaC practices into the CI/CD pipeline for deploying infrastructure components such as cloud compute instances, storage buckets, and networking configurations? Discuss the use of tools like Terraform or AWS CloudFormation to define, provision, and manage infrastructure resources as code.
25.	What are the services in Kubernetes? How many types are there ?



Blue Ocean - DevOps Engineer - Round 1

1.	Can you brief me about yourself and your experience.

2.	What steps do you take once you receive a requirement for a new feature development? 

3.	How do you handle different environments in pipeline?

4.	What are the security tools you are using? How are you publishing the result as you mentioned in ADO portal ? Where can these results be found after publishing?

5.	Any other GitOps tool have you worked with?

6.	What are the tools required to build docker images ?

7.	How did you do monitoring setup using Prometheus and Grafana?

8.	Can you tell me how have you configured point to site VPN setup mentioned in your resume ?
9.	Which kubernetes service are you using or have you done setup from scratch?
10.	Suppose there are 1000s of pods running on aks and your master , worker nodes are also private ,how will the end user access the application?









lifotechnologies Chennai

1)An update to a VM's  caused unexpected downtime. You decided to write a Python Script from Scratch which will update the VM, check the health and if unhealthy rollback the change. Write the script.

2)You want to gradually roll out a new version of an Azure Function App using feature flags or routing rules. Write Powershell script for the same..

3)You are tasked with deploying a new version of a web application to Azure App Service using Terraform. The deployment should ensure zero downtime during rollout. Please write a code for it.













Infy architect

1.	What is your role and job in your current project?
2.	How did you create a pipeline for a Java application?
3.	Where do you store the code artifacts, and how do you deploy those artifacts on Azure Cloud?
4.	How are you setting up Azure Kubernetes Service (AKS) in your application pipeline?
5.	How do you manage sensitive information in your pipeline?
6.	How do you fetch sensitive information from Azure Key Vault to your pipeline?
7.	Can you explain the stages, tasks, and steps you defined in your application code pipeline?
8.	How do you connect your Terraform code with the Azure portal without using VS Code terminal?
9.	What is a Terraform module?
10.	Which Azure services have you worked with?
11.	How do you create a Virtual Machine in Terraform?
12.	What do you do after you have created the code for a Terraform module?
13.	What is Azure Front Door?
14.	Do you know PowerShell and Bash scripting?
15.	What is the correct answer for the workflow of Terraform?











Mphasis
1.	What is null resource in Terraform?
2.	What is the difference between providers and provisioners?
3.	What is the use of user_data in Terraform, and what is userdata.tpl? (Hint: provisioning one server from another)
4.	How are state files managed in your organization?
5.	If 20 servers are created (with specific memory, CPU & software) via Terraform and later you want to upgrade the software on all of them at once, how would you do it (using Terraform or not)?
6.	Why is the terraform taint command used?
7.	What are best practices to use Dockerfile and minimize image size?
8.	What is the difference between CMD and ENTRYPOINT in Docker?
9.	If both CMD and ENTRYPOINT are mentioned in a Dockerfile, which one takes precedence?
10.	What monitoring tools do you use? (e.g., Prometheus/Grafana)
11.	How does Prometheus work and how does it collect data?
12.	Have you worked on any configuration tools like Ansible or Puppet?
13.	What kind of servers are you managing? (e.g., IIS, NGINX)
14.	What is the hierarchy of deployment in a CI/CD pipeline?
15.	Do you have any scripting knowledge? What is your process if you're given a file to work on?
16.	Introduction
17.	What is the workflow of Terraform?
18.	What is a Tenant ID in Azure?
19.	What is Blob Storage in Azure?
20.	Which tools are you using in your project?
21.	What types of issues are you facing on a daily basis?
22.	How do you add or remove a VM in Terraform?
23.	What is a Terraform module?
24.	Do you know Docker and Kubernetes?
25.	Do you have experience working on multi-cloud environments?
26.	What are three major issues you have faced in DevOps, and how did you resolve them?
27.	How do you securely access an API in your DevOps workflow?
28.	If a resource becomes deprecated, what lifecycle management strategy or rule do you apply?
29.	How do you prevent a specific subnet from accessing an App Service?
30.	How do you use route tables in combination with a firewall to control traffic flow?
31.	How do you securely access secrets from a Key Vault?
32.	How do you access a Terraform state file locally?
33.	If a Kubernetes pod is OOMKilled, how do you troubleshoot and resolve it?




MYgroup
1.	What is Azure Functions?
2.	What is NAT and what is an Application Gateway in Azure?
3.	What is a sidecar container?
4.	Can we deploy more than one container in a single pod?
5.	What is a taint in Kubernetes and why is it used?
6.	What are headless services in Kubernetes?
7.	What is a deployment set in Kubernetes?
8.	What is Docker Swarm?
9.	What is ARG in Docker and how is it used?
10.	How do you manage Terraform state files, especially when working with multiple state files?
11.	Why do you use MySQL over other databases? What are its benefits?
12.	If you are using a CIDR range like /16 and have thousands of IP addresses, what is your approach to manage them efficiently?
13.	If 150 people are using the same backend, how would you handle or recognize them individually?
14.	What is the difference between a root module and a child module in Terraform?
15.	If you don’t want to hardcode the IP address in the main.tf file, how would you manage it?
16.	What is the use of the top command in Linux?
17.	What is a StatefulSet in Kubernetes?











ParentPay

1. What is count and for each. 
2. How you do lookup in Terraform.
3. What are different type agents in pipeline.
4. What are different Azure services.
5. In Kubernetes what is ingress.
6. Introduction about yourself.
7. If you have a deprecated resource and cannot delete it . How can you migrate to a new resource which has new features. 
8. How can you change a single resource without impacting infrastructure.
9. What is Application scaling.
10. What are Branching policies.











LTI Mindtree
1.	Can you tell me about your projects that you have worked on?
2.	What services have you used in Azure?
3.	How do you connect your VM with a private IP?
4.	What is VNet peering?
5.	What is the difference between a route table and a Network Security Group (NSG)?
6.	What is an Application Gateway?
7.	How is Application Gateway different from a Load Balancer?
8.	How do you patch your VM?
9.	If a vendor pushes a patch while a developer is working on a VM, how will you handle this delta patching?
10.	What is swap space in a Linux VM?
11.	Where can you find Microsoft’s updates about upcoming Azure services? Which page/website?
12.	How have you configured backups for your environment?
13.	Where are your VMs located? Which region?
14.	Where are your Disaster Recovery (DR) servers located?
15.	How have you configured your Disaster Recovery setup?
16.	How have you set up monitoring for VMs?
17.	If your VM goes above 80% CPU utilization, how will you get notified?
18.	How do you configure alerts using Azure Monitor?
19.	What is the difference between Automation Account and Function App in Azure?
20.	How do you horizontally scale your App Services in Azure?
21.	How do you access a Storage Account in Azure? How is it securely configured?
22.	How do you manage your Terraform state file?
23.	How do you access the Terraform state file from your local CLI?
24.	Give a case scenario: if a client gives a requirement to deploy a landing zone, what would your approach be?
25.	If an architect provides a High-Level Design (HLD) for Azure Virtual Desktop, how would you deploy it as the sole responsible person?
26.	After environment deployment, if access is not provided or a firewall port is closed, how would you troubleshoot connectivity issues?
27.	What challenges have you faced in the past, and how did you resolve them?
28.	In your previous organization, what were the major problems you encountered and how did you overcome them?
29.	You are given 10–15 days to deploy 4000 VMs using Terraform — how will you approach this?
30.	How do you troubleshoot a VM in Azure?
31.	What are the key services available in the Azure DevOps portal?
32.	How do you set up monitoring in Azure?
33.	How do you set up Splunk for monitoring in Azure?
34.	What is KQL (Kusto Query Language)? Can you write or explain any query used in Log Analytics?
35.	If you're unable to SSH into a VM, what steps will you take to troubleshoot and resolve the issue?
36.	How do you configure alerting in Azure DevOps?
37.	How do you collect performance or log data from a VM?
38.	If you have two subscriptions in Azure DevOps, how will you give access to new resources across them?
39.	How is KQL used in Log Analytics?
40.	.How do you troubleshoot Vm?
41.	2.What are the services of azure devops portal
42.	3.how do u set up monitoring
43.	4.how do u set up splunk and monitoring
44.	5.What is kql query . can u tell me about query in this
45.	6.If you are not able to do Ssh in Vm what steps u will take to resolve
46.	7.how do u set up alerting in azure devops
47.	8.How do you collect data from the Vm
48.	9. If you have two subscriptions on azure devops how will you give access to new resources
49.	10. What is KQL and how is it used in Log Analytics?
with L&T Mindtree
Introduction
CICD:
50.	How to create ADO global variables in Terraform
51.	Tell me complete CICD followed in ur company
52.	Why use gitops ?
Docker:
53.	Why multistage docker file?
54.	Docker networking concepts
55.	Why multistage docker file?
56.	Docker networking concepts
K8s:
57.	How did u do rolling out deployment?
58.	How did u load balancing in kubernetes? How
59.	Kubernetes Yaml files
60.	Secret management
61.	Taint & toleration
Terraform:
62.	State file management in Azure & AWS and difference in both clouds
63.	Where did u use lifecycle?
64.	Power shell scripting

1.	Can you tell me about your projects that you have worked on ?

2.	What services have you used of azure ?

3.	Write Azure Pipeline using YAML and explain each stages?

4.	Apart from Terraform infra what else you can automate ?

5.	Do you know any scripting?


6.	How do you connect your VM with private IP?

7.	What is application gateway? 

8.	How do you patch your VM ?

9.	What is swap space in respect to your Linux VM ?
10.	Suppose microsoft is announcing some new updates regarding azure services in future ,where will you get those updates? Which page of which website?

11.	How have you configured your backups?
12.	Where are your VMs located? Which location?

13.	Where is your DR servers located?

14.	How have you setup monitoring for VMs?

15.	How will you configure that in azure using service like azure monitor?

16.	What is difference between automation account and function app?

17.	How will you horizontally scale your app services

LTIMindTree

How do you connect your VM with private IP?

What is VNet peering?

Difference between route table and NSG?

How do you patch your VM ?

If vendor pushes a patch while developer is working on a VM ,how will you handle this delta patching?

What is swap space in respect to your Linux VM ? 

Suppose Microsoft is announcing some new updates regarding azure services in future ,where will you get those updates? Which page of which website?

How have you configured your backups?
Where are your VMs located? Which location?

Where is your DR servers located?

How have you configured your DR?

How have you setup monitoring for VMs?
Where is your DR servers located?

How have you configured your DR?

How have you setup monitoring for VMs?

Suppose your VM goes above 80% cpu utilization, how will you get notified?

How will you configure that in azure using service like azure monitor?

What is difference between automation account and function app?

How will you horizontally scale your app services ?

How do you access storage account? How it is configured securely?

How do you access the state file from your local machine cli ?
Questions:

1.	So, can you tell me about your road trip, responsibilities, your regular activities?
2.	Coming to the CICD pipeline, so did you get a chance to create a pipeline from the scratch or it was you who were maintaining the pipeline?
3.	While creating a pipeline, what are the different agents we have in Azure DevOps to run those pipelines?
4.	Tell me about Self-hosted and Azure-hosted Agent? what is the difference between them and in which scenario we can use these agents?
12.	I want to create a virtual machine in a resource group, my resource group already exists in the Azure portal. Configuration file should actually refer to that existing resource group and then want to create a VM set. So, how can you make that reference in your main.tf file?
13.	I want to create almost around 50 storage accounts for my project requirement. With almost same SKU. So, how can you do that in your configuration file?
14.	Where in the main.tf I am having the location value as in east US and also I am having a variable.tf where I am giving a default value as in west US and also we are having a terraform.tfvars file. Under the location value While you are applying the terraform so what variable value will it take?
15.	What are the workspaces in terraform?
16.	I have my VM with the standard V2 series and I have to upgrade that to a V series. So, how will you do that and what will you do to reduce the downtime of the VM and what happens to the application in that VM?
17.	We need to deploy a web app which actually requires high availability and scalability So, in this case, how will you design your VM infrastructure?
18.	What is the difference between site-to-site and point-to-site VPN connection?
19.	While creating a storage account what are the different types of tiers we can able to choose?
20.	I have to create an alert, so if my application which is posted in my VM is down, I want my group to get notified. How will you configure this?










Nav India - OnPrem Infra Engineer - Round 1


1. Can you introduce yourself?

2. Go ahead with the project use case.

3. How did you handle deployments on onprem?

4. How much would you rate yourself in Linux out of 10 ? (6.5/10 in my case)

5. What does touch command do ?

6. What will happen if I use touch command on an existing file ?

7. How would you print some middle lines from a log file?

8. Which command would you use to print how many number of lines are there in a file?

9. What are permissions in Linux ?

10. Where do you store users password in Linux ?

11.	Have you used docker? What is docker?
12.	What is difference between run, start and exec command?
13.	How would you automatically start a docker container if it get crashed?
14.	How would you copy a file from container to the host machine?
15.	 Have you used docker swarm ?
16.	Suppose I've created a container and I want to map a drive of a windows VM to the container and a linux VM also, how would you do it ? I don't want to use cloud for this.
17.	What are services you've used in k8s?
18.	What is the difference between ClusterIP and Load balancer ?






Wissen technology

Panel - Sunny Gupta

1. Write resource group code using for each ?
2. Tfsate file
3. How to make connections between two vnet. Other than vnet peering is there any other way.
4.  Write provisioner code ?
5. Write terraform code ?
6. Let suppose one vnet have 3 subnet and each subnet have one vm. VM1, VM2, VM3. I want to ping VM1 to VM2 but traffic should reach from VM3 to VM1 then VM2. How will you configure ?
7. Terraform block code ?
8. Create resources group using variable and what are ways to assign value ?
9. What is Azure firewall
10. Difference between azure load balancer and application gateway
11. S2S and P2S difference
12. VPN gateway architecture 
13. Developer make changes in code  not showing in terraform plan but deployed on cloud









DB Schenker

1.	How are you doing today
2.	Tell me about yourself
3.	What all resources you have worked on Azure, how you deploying all these
4.	Terraform state
5.	Difference between Terraform init, plan and apply
6.	What is disaster recovery? How you handle the disaster recovery in Azure?
7.	Have you performed any disaster recovery?
8.	Multiple engineer working on same state file, will they get any error?
9.	Suppose server is hosted in availability zone 1, if breach happens what preventive steps should users take to avoid this in Azure?
10.	How to increase the data disk in Azure
11.	I have 100 GB disk, I want to add 50 GB more — how?
12.	Suppose you are working in a feature branch and you are merging it to main branch — how do you resolve conflict?
13.	Suppose teammate accidentally deletes unmerged commit and main branch — how you recover it?
14.	Suppose teammate accidentally deletes unmerged commit and feature branch — how you recover it?
15.	How you recover the lost work?
16.	What is Jenkins file
17.	What all the tools you used in Azure DevOps
18.	Have you performed in-place OS upgrade? What are prerequisites and how you done?
19.	Suppose you restart a server, server got hung and from the serial console it stuck on dracut emergency shell — how you resolve the error?
20.	How do you resolve the kernel panic error?
21.	What steps you take if getting error access denied while creating IAM role?
22.	Suppose user is not able to do SSH in Azure VM — what steps you will take to resolve the issue?
23.	How you automate the patching in Azure?
24.	What is Satellite server, how you do?
25.	What is the role of Azure Update Management?
26.	Difference between Azure Load Balancer and Application Gateway?
27.	Suppose you have a URL, and user is trying this URL but getting 503 error — how you resolve?
28.	Have you worked on Azure App Services? What is it? Why is it used?
29.	What is variable group?
30.	How do you handle the deployment roll back in Azure DevOps?
31.	How do you handle the multiple environment in Azure DevOps?
32.	Do you know what is blue-green deployment in Azure?





Celebal Technology
1.	Tell me about yourself
2.	What all tools you have used in DevOps?
3.	What are the components/services Azure DevOps provide?
4.	What is the difference between CI and CD?
5.	What is VNet?
6.	Difference between Git and TFVC?
7.	What is artifacts?
8.	Difference between Azure DevOps and Jenkins?
9.	What are the benefits of Azure DevOps over Jenkins?
10.	What is branch policy?
11.	What is service hooks?
12.	What are the security features available in Azure DevOps?
13.	What is build definitions?
14.	How to manage dependency?
15.	What is the purpose of pipeline artifact?
16.	What are the different types of trigger?
17.	How do you implement rollback in Azure DevOps?
18.	What is IAC?
19.	What is blue-green deployment?
20.	What types of projects have you done? What types of domains?
21.	What is the lifecycle of DevOps engineer?
22.	What is peer programming?
23.	Architecture of DevOps
24.	What is sudo concept?
25.	Do you know postmortem in DevOps?
26.	Can you explain the "left to reduce failure" concept in DevOps?
27.	How can you ensure a script runs every time the repository gets a new commit through git push?








Locktown
1.	Tell me about yourself
2.	Can you explain a little about application pipelines, what tools you worked with, and describe every stage?
3.	How do you handle secrets?
4.	How do you handle the approvers and check?
5.	Have you worked on Terraform? How do you manage the state file?
6.	Apart from blob storage, where else can the state file be found?
7.	Suppose some resources were deleted from the Azure portal, what is drift?
8.	Terraform deployment failed midway — how do you recover it?
9.	Terraform apply command failed — how do you resolve it?
10.	On Azure side, what all services have you worked on?
11.	How do you handle core rules in blob storage settings? What is the purpose of that?
12.	Have you worked on virtual machines? What types of applications have you deployed?
13.	How do you build React frontend application in your pipelines?
14.	Let's say you did a deployment on Friday and on Monday suddenly the application stops working — what are the troubleshooting steps?











Metacube
1.	Tell me about yourself
2.	List down the services of Azure you have worked on
3.	Difference between point-to-site and site-to-site VPN
4.	Have you heard about NSG? Suppose I create one NSG and apply it to NIC of VM in virtual network —
5.	I created another NSG at subnet level for the same VM — which NSG gets priority?
6.	One NSG port 22 allow, another NSG port 22 block — can I SSH from my system?
7.	What is defined in NSG? In inbound rules, what do we define?
8.	What is Azure Bastion?
9.	What are the types of storage accounts in Azure?
10.	Storage account tier — what is that? Difference between hot and cool?
11.	Accidentally deleted the state file and some resources exist in Azure — how do you manage the resources?
12.	I deleted the state file and want to attach tags to resources in portal — how would you do that?
13.	In null resource block, what will you mention? Write the code of null resource.












Citius Technology

1.	What is this job for, and why do you think you are the right fit for it?
2.	What is your work style? How do you typically approach your tasks?
3.	Can you describe your current role, especially in operations and automation?
4.	What are the main roles and responsibilities in CloudOps (operations)?
5.	How do you perform patching?
6.	What is the process you follow to deploy patches in a production environment?
7.	Do you have experience with Bash scripting? Please explain.
8.	What are some common troubleshooting commands you use? (Give only the exact commands.)
9.	Do you have experience with Azure monitoring? How do you set it up?
10.	What is a host in computing or cloud terminology?
11.	Where are you using YAML files? Why are YAML files used?
12.	What resources have you created in Azure?
13.	How do you collaborate with your team? How do you handle or lead a team?
14.	Can you give examples of Standard Operating Procedures (SOPs) you’ve created or followed? Explain.
15.	When do you usually handle releases, and what challenges have you faced during release cycles?
16.	Can you troubleshoot a DNS issue? For example, if vikram.com is not showing in Google, how would you approach this?
17.	Which users are allowed to use a subscription? How do you manage and assign access to users in Azure?
18.	Where do you see yourself in the next 5 years?
19.	What skills have you added or improved in the past few years?
20.	Why are you looking for a change in your current role? What repetitive tasks are you currently doing that you want to move beyond?







Evalueserve
1) introduction 
2) what is module
3) where you save  statefile 
4) can we save statefile on other place except backend storage
5) how we send code 1 terraform to other terraform
6) what is the diff in validate and fmt
7) write script memory > 90 and copy from one server to another server
8) what is the flow of terraform
9) what is ci cd 
10) which agent are u use in azure devops
11) what is pod in docker
12) write a terraform code of vm









Avigna.ai
1. Tell me about yourself.
2. Roles and responsibilities, team size.
3. What azure services have you worked on.
4. How will you do deployments in AKS. What is imagepull secret.
5. How will you do deployment in Azure Webapps..both microservices and monolithic deployment.
6. 5 linux commands.
7. How will you troubleshoot if in app insigh your rest api is throwing "connection refused" while connection to sql instance 
8. What is private endpoint.
9. Why you want to switch?











All Infinite
1. How to take backup of a SQL Server database using SQL query.
2. customer table and customer transation how will fetch particular customer (65)transcation deatile.
3. some production data rollback database.
   4. How to check security and vulnerabilities
   5. if any vulnerabilities is there how to fix it in database.
   6. Have u used application pipline
   7. which os  you using linux, window.Any script language       you are using. 
  8. Mutual Authentication Between Load Balancer and Backend?
9. How Many Domains Can Azure Front Door Handle?
10. Have you used tsql query?











Glorious Insight
1) what is azure function 
2) what is keyvault
3) what is AKS and ICS
4) what is loadbalancer
5) what are the type of loadbalancer
6) introduction
7) what is Types of availability zone support












Publicis Sapient


1.	What is agent-based and agent-less monitoring?
2.	What is a landing zone in cloud architecture?
3.	What is hub and spoke architecture in Azure?
4.	What is Azure Arc and how is it used?
5.	What are the types of storage available in Azure?
6.	What is the difference between Blob Storage and File Storage in Azure?
7.	What are the types of disks in Azure?
8.	Tell me about your recent project.
9.	What is a Virtual Network (VNet) in Azure?
10.	How are you balancing traffic in the cloud?
11.	How many types of load balancers are there in Azure?
12.	What is priority in a Network Security Group (NSG) rule?
13.	What is the difference between a Service Endpoint and a Private Endpoint?
14.	How do you securely access your cloud resources?
15.	What is Azure Bastion and why is it used?
16.	What are NSG (Network Security Group) rules in Azure?
17.	How do you restrict access to any service on a specific resource?
18.	What network topology have you worked with?
19.	How do you connect an on-premise application to the cloud?
20.	Where do you store your Terraform state file?
21.	What is the lifecycle block in Terraform?
22.	If you run a pipeline and it fails after apply, and you’re stuck in a Terraform lock state, how will you resolve the issue?
23.	If you are calling a variable from Key Vault but do not want to mention it in the pipeline or Terraform code, how would you handle it?
24.	We have Dev, Prod, and Staging branches. We want to trigger a pipeline only when the Dev pipeline passes 90%. Write a condition in YAML for this.
25.	Write a shell script that sends an alert email if a VM disk reaches 80% full.






CitiusTech

1. Introduce your self
2. How do you manage banckend state management
3. describe a real time scnario where you used terraform configuration to minimize the complexity of your code
4. What issues you faced while migrating your infrastructure to Kubernetes cluster
5. 1 question realted to Pulumi , I cannot recall exactly
6. How do you manage running parallal jobs in Azure Devops
7. How do you manage alerting using Prometheus and Grafana
8. wHat is lifecycle in terraform
9. What are the basic troubleshooting you have done in terraform
10. How to manage reuasbility and maintenability of configuration in terraform
11 .There was one coding question related to AWS in terraform incorporating DR and IAM . I cannot recall the exact question









Parentpay

1. introduce yourself
2. Can you ping one vm in one vnet with anther vm in another vnet.
3. How can you create the connectivity between them.
4. If the vms are in different subscriptions how will you achieve the same.
5. Difference between owner , reader and contributor rights.
6. What is service connection and service principle
7. If there are 1000 blob containers in 1 storage account, how will you migrate them to another storage account.
8. What is backend state management
9.if you have an sql block in terrafrom which has deprecated and you want to change it but there is already some data in the current sql database , how will you achieve it
10. I I want to read the details of keyvault , what role should be assigned to me
11. how to import secrets in keyvault in your pipeline.
12. Any other way you can achieve it other than variable groups.
13. What is deployment group in azure pipeline
14.Tell me the entire workflow in azure piepline.
15. What is multi stage pipelines
16. Have you worked on kubernetes
17.what can you use as a backend pool in a load balancer
18 Do you have any experince with alert monitoring tools
19.extensions in azure pipeline



Ntt Data

1 .intro
2. Difference between git revert and reset
3. Difference between git fetch and git pull
4. Difference between COPY and ADD
5.If you are having any issue in a container how can you check and troubleshoot it
6. Suppose I am working on a feature branch and you are working on a different feature branch, now I want to merge these 2 feature branches together , how will I achieve it
7. Can you tell me the command to create a container from an image
8. Write a dockerfile and explain it
9. We are working on a banking project so, we do not have direct access to internet, how will you execute npm install
10. Explain workflow of pipeline
11. How can we enter inside a particular container.
12. What does tflint do
13. What is the linux command to compress a file
14.git rebase






Dover

1.	Tell me about your education, work experience, and day-to-day activities.
2.	Have you heard about Dover before?
3.	Which cloud platforms do you have experience with? Have you worked with any others beyond your primary one?
4.	Do you have experience in Terraform? How would you rate yourself out of 10?
5.	What resources have you provisioned using Terraform?
6.	Tell me about the Terraform state file — what it is and how it works.
7.	If you were to create an AKS cluster using Terraform, what would be your high-level approach?
8.	Have you worked on Kubernetes?
9.	What is a Network Security Group (NSG) in Azure?
10.	In Kubernetes, what are masters, nodes, and pods? Can you briefly explain the AKS cluster design?
11.	What are node pools in AKS?
12.	How do you monitor logs for an AKS cluster?
13.	Have you worked on any monitoring tools? Which ones?
14.	Suppose there’s an application deployed on Azure App Services and it goes down (as informed by a customer) — how would you troubleshoot it?
15.	Can you share a recent incident from your current project where something broke in production? How did you resolve it, and what preventive measures did you take?
16.	How many environments (e.g., dev, test, staging, prod) have you managed?
17.	Are you available to work in shifts and be on-call?
18.	What is your notice period? Since your colleagues were released in 30–45 days, are you also expecting the same?
19.	Have you worked on cost optimization in cloud projects?








Altud

1.	Have you recently worked with Kubernetes and Azure PaaS?
2.	How do you maintain container security in Kubernetes deployment?
3.	How do you ensure the images used in your containers are secure and not vulnerable?
4.	What tools can you use to scan for code vulnerabilities or follow best practices in infrastructure as code?
5.	Can you provide examples of linting tools used in Terraform?
6.	What does TFLint do in Terraform?
7.	How do you handle blueprint deployments in Kubernetes?
8.	Is there a master step configuration in Kubernetes?
9.	What do you understand by rolling deployments in Kubernetes?
10.	How do you achieve rolling deployments?
11.	After deployment, if a pod goes down, how do you ensure the website is not affected? How do you handle rollbacks and troubleshooting?
12.	Can you list common errors due to which Kubernetes pods don't come up post deployment?
13.	What are common causes for Kubernetes pods getting stuck in loopback or crashloop errors?
14.	How do you resolve Kubernetes deployment issues using pod logs?
15.	What challenges do you face when deploying AKS using Terraform?
16.	If your AKS cluster is private and subnet IPs are exhausted, how do you handle that situation?
17.	Can you increase the IP range of an existing subnet in Azure?
18.	What is a pod distribution budget in AKS?
19.	What is the difference between a deployment and a stateful set in Kubernetes?
20.	What does a Pod kind component do in Kubernetes?
21.	What is a Persistent Volume Claim (PVC) in Kubernetes?
22.	If a container is facing performance issues, how do you check its CPU and memory usage?
23.	What command can be used inside a container to monitor performance?
24.	Have you ever upgraded an AKS cluster using Terraform?
25.	What types of application migrations have you handled recently?
26.	How do you migrate a function app to AKS?
27.	What tools have you used to migrate on-prem infrastructure to Azure?
28.	How do you call a shared Terraform module from multiple repositories in Azure DevOps pipelines?
29.	If the shared repository is private, how do you authenticate and pull code in a CI/CD pipeline?
30.	What is the difference between self-hosted and Microsoft-hosted agents in Azure DevOps?
31.	If a VM or web app is private, can you use a Microsoft-hosted agent for deployment? Why or why not?
32.	How do you ensure a specific pipeline runs only on a Windows agent when using a shared agent pool?
33.	What approach do you take to set up CI/CD for 20+ .NET backend microservices?
34.	What would you do differently if you had 100+ microservices instead of 20?
35.	Have you worked with reusable templates in Azure DevOps?
36.	How do you securely access secrets from Azure Key Vault during CI/CD?
37.	If migrating CI/CD from Azure DevOps to Jenkins or GitHub Actions, how do you handle the lack of built-in templates?
38.	What is a deployment group in Azure DevOps?
39.	What is an environment in Azure DevOps?
40.	What is an approval gate in Azure DevOps?
41.	What happens if your Terraform state file gets corrupted?
42.	How can you recover a corrupted Terraform state file without using Azure Storage Account?
43.	What is the .terraform.tfstate.backup file, and how can it be used?
44.	What is the Terraform import command used for?
45.	Have you worked with Helm charts?
46.	What types of applications have you deployed previously?
47.	Where (VMs, PaaS, AKS) were the applications deployed?
48.	How do you distribute load across applications deployed in VMs?
49.	What is the difference between a Load Balancer and an Application Gateway in Azure?
50.	What does a Web Application Firewall (WAF) do?
51.	How will you use a Web Application Firewall (WAF) if your organization is using a third-party firewall like Palo Alto or Zscaler, and you don’t want to use Azure Firewall?
52.	Is the only difference between Azure Application Gateway and Load Balancer the fact that one operates at Layer 7 and supports WAF?
53.	Can Application Gateway distribute traffic based on content, and is that feature available in Load Balancer?
54.	Suppose you have a private storage account and a private VM deployed in the same subnet. When you try to access the storage account from the VM, you get a 403 Forbidden network error. How would you troubleshoot this issue?
55.	What could be the possible causes for the VM not being able to access the storage account, even though they are in the same subnet and NSG rules are correct?
56.	Are you familiar with Private DNS zones in Azure?
57.	Could a missing or incorrect Private DNS record cause the issue where the VM cannot resolve the storage account endpoint?
58.	Have you worked with Azure App Services?
59.	What are deployment slots in Azure App Service?
60.	Have you worked with Azure SQL Database?
61.	What is the difference between Azure SQL Database and SQL Elastic Pool?
62.	Have you worked on upgrading services (e.g., AKS upgrades)?
63.	Which services are you most experienced with in terms of monitoring and configuration?
64.	Which tools are you primarily using (e.g., Terraform, Azure DevOps, Git)?


















Opstree
1.	Introduce yourself
2.	What is your day-to-day activity?
3.	What kind of defects do you get?
4.	Explain the latest defect. How did you resolve it? How do you ensure it doesn't happen again in the future?
5.	What kind of infrastructure have you provisioned into Azure Cloud?
6.	What is the difference between Application Gateway and Azure Front Door?
7.	What is Terraform Workspaces?
8.	How do you provision any infrastructure using Terraform?
9.	What is the data block in Terraform?
10.	How do you handle secrets in Terraform?
11.	Rate yourself in Terraform.
12.	What is the difference between App Services and a Service Principal?
13.	What is App Services?
14.	How much experience do you have in Linux?
15.	How do you check memory and CPU usage in Linux?
16.	Rate yourself in Linux.
17.	Explain a Kubernetes cluster.
18.	What resources have you deployed using Kubernetes (K8s)?
19.	What is the difference between Deployment and ___? (Note: Question seems incomplete)
20.	What are Services in Kubernetes?
21.	How do Services work in Kubernetes?
22.	What is RBAC (Role-Based Access Control)?








UST Global
1. git project size is very huge 20 gb how reduce size how to better way maintain and lot of conflict happening in how to avoid this type issue, what is your suggestion(repo model).
2. How to maintain distributed repo model.
3. what is better branching strategy and avoid the conflict (tool or plugin)and don't want to solve manual conflict issue.
4. In our CI pipeline take to much time for run. how Speed Up CI Pipelines .
5. junior by mistake changed in testing environment but that is for dev environment how to correct.
6. Is it possible to create jenkins job and run it.












Accolite Digital

1.Introduce yourself and brief your project and day to day responsibilities 
2. Terraform lifecycle
3. ⁠diff between terraform taint and destroy command.
4. Write Yaml file for VM creation using ado pipeline
5. what is SonarQube.
6. Monolithic vs Microservices
7. Docker all commands with their use case.
8. K8s architecture and create a yaml for policy control. PV and PVC.
9. Diff between different load balancer you used in azure.
10. Components of different load balancers.
11. vnet peering vs express route
12. write code for log analytic and diagnostic using terraform.
13. dierrent types of quer editor in azure monitoring
14. what role you assigned in K8.
15.  docker swarm vs K8 
16. Explain all 3 git merge, git rebase, and git stash.
17. What is the difference between head, head^, head~1, head~2, and head@{1}
18. You accidentally committed sensitive data (like a password). How do you remove it completely from Git history
19. What is the .git folder structure and what are key files inside it
20. You did a rebase and now your history is messed up. How do you recover
21. How does Kubernetes integrate with cloud-native services like Azure
22. What is a NetworkPolicy and how does Kubernetes enforce it.


 
Vlink
1.	Your task is to design a generic pipeline which can be used for Java Spring Boot microservices application — how would you approach dockerizing the application and deploying it to AKS?
2.	Which build tool is used for Java applications, and how do you push the Docker image to Azure Container Registry (ACR)?
3.	How do you design a CI/CD pipeline for a .NET application?
4.	Write a Dockerfile from scratch and explain each step.
5.	How do you deploy an application to AKS (Azure Kubernetes Service)?
6.	Secrets are stored in Azure Key Vault — how do you retrieve them in your CI/CD pipelines?
7.	If your source code is in one Azure repository and your pipeline YAML is in another, how do you reference the source code repo in your pipeline?
8.	What is the Terraform state file?
9.	If the Terraform state file is accidentally deleted, how do you troubleshoot or recover it?
10.	You have multiple providers in Terraform like Azure and AWS — how do you manage these providers in your Terraform code?
11.	During which step is the provider plugin downloaded in Terraform?
12.	How do you check running processes in Linux?
13.	How do you kill a process in Linux?
14.	How do you check if a port is open in Linux?











Xebia

1. Introduce yourself with your education background, work experience 
2. Tell me about your project 
3. How have you deployed your projects? Dockerfile and CICD pipeline? Or how?
4. Have you done setup for monitoring, creating dashboard and all ?
5. If I have to create 2 VM ,one in azure another in AWS, can we do it using a single code and applying terraform command at once?
6. What is self hosted agent ?












intelliswift
1.	Introduce yourself.
2.	What is a Storage Account lifecycle in Azure?
3.	What is Azure HLD (High-Level Design)?
4.	How do you manage Terraform for multiple environments (e.g., dev, staging, prod)?
5.	How do you provide input to create hundreds of VMs using Terraform?
6.	If a pod is in Pending state, how do you troubleshoot and fix it?
7.	If a pod shows CrashLoopBackOff or ImagePullBackOff, how do you troubleshoot and fix it?
8.	Share your screen and open Notepad. Write a basic pod.yaml file.
9.	How do you break or unlock a Terraform state file if it is locked due to a failed operation?
10.	How do you manage communication between two storage accounts without using VPN or Load Balancer?
11.	What is UDR (User Defined Route) and how is it used in Azure networking?
12.	How do you provide security to a Virtual Machine in Azure?
13.	What is the command to check logs of a Kubernetes pod?
14.	Can you explain how to manage a branching system in Git?
15.	If both you and I raise a Pull Request (PR) and mine gets merged first, how do you handle your PR to avoid conflicts and proceed?
16.	What security tools can be implemented in a CI/CD pipeline to ensure code quality and vulnerability scanning?
17.	If a CI/CD pipeline fails, how do you troubleshoot and fix it?
18.	What is the difference between NSG (Network Security Group) and UDR (User Defined Route)?














Bajaj Technology Client round
1.What is Web app and how to deploy a  application and how  to reduce the cost of application in webapp??
2.how to create webapp by using terraform tool and manually??
3.how to develop pipelin for deployement of infra by using IAC tool??
4.what is the azure devops portal why we use and how to  create pipeline in portal??
5.what is the difference between classic pipeline and yaml pipeline  which is best ??
6.how to optimize the cost in azure portal??
7.suppose you are deploying a  feature and suddenly you faced a issue and what will your approach to resolve this issue??
8.how to write deploy a  application in AKS cluster ??
9.what is ADF how to uze is azure ??
10.what is the Service principal and service connection??
















PWC


✅ Round 1: Screening Round (30 minutes)
i.	Walk me through your current project architecture and your role in it.
ii.	Which DevOps tools have you worked with in the last 2 years?
iii.	What AWS services have you used in production?
iv.	How do you expose a Kubernetes application to external traffic?
v.	What is the purpose of a NAT Gateway?
vi.	How do you check running processes in Linux?
vii.	What command would you use to find files larger than 100MB?
viii.	What is the difference between Deployment and StatefulSet in Kubernetes?
ix.	What is a ConfigMap, and how is it different from a Secret?
x.	How do you check network connectivity between two servers?
xi.	Describe your experience with CI/CD pipelines.
Round 2: Technical Round (60 minutes)
- You have an application in Account A that needs to access an S3 bucket in Account B. How would you configure this?
- Write a Dockerfile for a Node.js application with multi-stage builds.
- How do you handle Terraform state file corruption?
- Your EC2 instance in a private subnet needs to download packages without NAT Gateway. What alternatives exist?
- How do you debug a container that has exited?
- You need to import an existing AWS VPC into Terraform. What are the steps?
- How would you implement blue-green deployment in Kubernetes?
- How do you manage secrets in Terraform without hardcoding them?
- What's the difference between COPY and ADD commands in Dockerfile?
- How would you implement cross-account resource provisioning using Terraform?
- How would you handle secrets in a Docker container for a PHP application connecting to MySQL?
- An S3 bucket was created via Terraform, but someone manually added a policy. How do you handle this drift?
- How do you implement network policies to restrict pod-to-pod communication in Kubernetes?
- Write a Python script to backup all files older than 30 days from a directory.
- Your company's cloud costs are increasing rapidly. - How would you approach cost optimization without impacting performance?
- How would you set up geolocation-based routing using AWS services?
- A critical production Kubernetes cluster is experiencing multiple issues. Pods are stuck in ImagePullBackOff, some pods are being evicted, and users are reporting 503 errors from the application. What troubleshooting process will you follow, and how can to avoid this in the future?

✅ Round 3: Behavioral Round
- How do you handle a situation where you're asked to work on a technology you have no experience with?
- Describe a time when you had to work with tight deadlines and limited resources.
- Tell me about a mistake you made in production and how you handled it.
- Describe the most challenging technical problem you've solved in your career.
- How would you convince stakeholders to adopt a new technology or process?
Tell me about a time when you had to learn a new tool quickly to solve a business problem
















AXIEVE 
1st round  questions
What is the difference between Linux and Unix?
Can you write a bash script example?
What is the difference between an Availability Set and an Availability Zone in Azure?
What are the day-to-day activities in cloud infrastructure management?
Can you describe the end-to-end infrastructure provisioning process?
What is a multi-stage Dockerfile, and how is it used?
What types of issues do you face when working with Docker?
What is Azure Service, and what are its different types?
What is virtualization, and how does it work?
What issues are commonly faced in Docker?




















ITC Infotech

	1.	Tell me about yourself.
	2.	Explain the structure of a Kubernetes Cluster.
	3.	How do you check the status of a Pod?
	4.	What is the role of a Kubernetes Controller?
	5.	What is an Availability Set and Availability Zone in Azure?
	6.	Explain Fault Domain and Update Domain.
	7.	How do you pull a Docker image?
	8.	How do you build a Docker image?
	9.	If an issue occurs in a container, how do you troubleshoot it?
	10.	Explain the concept of Virtualization.




















Orion Innovation First Round
1- He asked about Python scripting.

2- He also asked about Terraform – Azure Data services and Modules.

3- There were some questions related to pipelines, like how you would integrate Terraform code with a pipeline.

4- He asked about GitHub and GitHub Actions.

5- He asked about Ansible – specifically, just like there are modules in Terraform, what are modules in Ansible?

6- What are Roles in Ansible?




















schnelltechnocraft

1	What is management group and why we need multiple subscripition and management groups
2	There is any limit for subscription in a management group?
3	What is hub n spoke model what would you do in order to create this model
4	If there are 3 vnets vnet1 is hub and other two are spoke will they communicate?
5	What is disaster recovery and how will you design it end to end
6	what is RPO RTO?
7	How can I achieve resource provision from the portal should be denied but how can I provision them?
8	How will you deploy a landing zone and vms in different subscription from terraform? What is the best approach?
9	Lets suppose you have 100 machines in which 50 windows and 50 linux we need to implement monitoring for them, what would you do?
10	Do we need any agent for the azure monitor to install on vms? Are we going to do manually?


















Tcs round 1
i.	how to do rollback in azure devops if pipeline fails
ii.	explain multistage pipeline
iii.	statefullset
iv.	ansible
v.	what is replica set
vi.	release and build pipeline difference
vii.	backend block
viii.	Availability set and zone difference 
ix.	Backend block share your screen write
x.	Web application gateway and load balancer difference

TCS: Hyderabad.

Terraform:
1. Resource block. If I change the name of the resource block, what will happen.
2. If a RG is created using Terraform. If inside the resource block, I change the name from RGname1 to RGname 2. How can I retain both in Azure.
3. What is import block.
4. What are some terraform state commands?
5. Have you used dynamic block, give example?
6. Have you used map(object) variable, how you used it?
7. Explain for each, with map(object).
8. How will you call resource group as a variable inside variable block of VM?

Docker and Pipeline:
1. Which pipeline you used?
2. Explain pipeline.
3. Can you write pipeline of docker commands?
4. How will you ensure security of contents of docker file (like tfsec)?
5. How will you reduce docker file image size?
6. Tell me docker commands you have used to deploy image on ACR?
7. How will you access ACR in pipeline to deploy application?
8. In GitHub Actions, is there a way to store some artefacts, like we have build artefacts in Azure Pipeline?
Kubernetes:
1. How can you create a pod in a particular node?
2. What is stateful sets, deamon sets?
3. Can you run K8s in pipeline?
4. How can you do log analytics of K8s cluster?
5. How many maximum nodes can be in a cluster?
6. How does scaling work?

























Damco

1.	What are the deployment slots in the Azure services?
2.	Difference betweem Application gateway & Cloud Front
3.	Difference betweem Application gateway & Frontdoor
4.	Suppose in pipeline we save the artifacts for longer period. how we will do that?
5.	What are the main components of Azure devops?
6.	What is difference between build & release pipeline?
7.	What is the service connection in Azure Devops?
8.	What is deployments group in Azure Devops?
9.	Difference between Azure hosted & self hosted agent.
10.	What are the main components of control plane of the K8s cluster?
11.	How will you expose your services externally.
12.	What is stateful set?
13.	What is config map and how we use it?
14.	Difference between config map & secrets?
15.	How do you connect your Kubernetes cluster using Azure CLI?
16.	Suppose you have a 3 tier architecture, can you tell me what are the components you are going to use in k8s along with securities?
17.	What is Daemonset?
18.	What is the difference between variables & Parameters in K8s?


















ITC - infotech - AKS L3 Role - first round

1.	Tell me about your brief introduction only professional
2.	What kind of permission you have in your company on AKS part?
3.	how do we upgrade version of cluster ?
4.	suppose we have 1000 nodes and we have to complete upgrade in 2hours ? Is it possible how can we achieve 
5.	Tell me about imagepulloff error and how will you troubleshoot
6.	what is crashloopback and how will you troubleshoot?
7.	if you have to upgrade the application version , what steps will you do and update ?
8.	how do you connect cosmos db with AKS cluster?
9.	suppose we have storage account and file share - how will connect with VM ?
10.	do you know about DR & recovery services ?
11.	what option we get in storage account to high availability ?
12.	rate yourself in Kubernetes ?
13.	rate yourself in Linux ?
14.	rate yourself in Azure services?
	1.	Tell me about yourself.
	2.	Explain the structure of a Kubernetes Cluster.
	3.	How do you check the status of a Pod?
	4.	What is the role of a Kubernetes Controller?
	5.	What is an Availability Set and Availability Zone in Azure?
	6.	Explain Fault Domain and Update Domain.
	7.	How do you pull a Docker image?
	8.	How do you build a Docker image?
	9.	If an issue occurs in a container, how do you troubleshoot it?
	10.	Explain the concept of Virtualization.










AXIEVE 1st round  questions
What is the difference between Linux and Unix?
Can you write a bash script example?
What is the difference between an Availability Set and an Availability Zone in Azure?
What are the day-to-day activities in cloud infrastructure management?
Can you describe the end-to-end infrastructure provisioning process?
What is a multi-stage Dockerfile, and how is it used?
What types of issues do you face when working with Docker?
What is Azure Service, and what are its different types?
What is virtualization, and how does it work?
What issues are commonly faced in Docker?
1). Write a bash script to check the service status and if down ,start it.
2). Write a Docker File to pass the values or user info for container.
3). Rolling updates in k8s : explain
4). Write 20 linux commands that you use mostly in daily basis.
5). Blue-green deployment 
6). If pod has any issue like autostart issue,how to fix it and Write yaml for this.
7). Bash vs sh difference.
8). Config map ?














IBM - DevOps Engineer - Round 1

1. Briefly tell me about yourself 

2. How do configure pipeline for different environments?

3. How do you do rollback?

4. Suppose there are two developers creating merge conflicts in same feature branch , how will you resolve? What are the preventive measures will you take such that it doesn't happen in future?

5. You have got requirement for creating some resources on Azure using ado pipeline, how will you do this ? Tell me from scratch.

6. How do you manage secrets in ADO pipeline?

7. Share your screen and write Dockerfile to build an image for any application.

8. Suppose you are getting CrashLoopBackOff error while deployment of a pod ,how will you troubleshoot it ?

26.	How will you scale an application running on k8s ?
27.	How will you do deployment rollback in k8s ?
28.	How will you do deployment rollback in ADO pipeline?
29.	Have you worked on Jenkins ?







EPAM


1.	Implementing hub and spoke model in Azure.
2.	On-premises to Azure connectivity
3.	Scenario on Azure Front door, Application Gateway and Traffic manager.
4.	Scenario on Azure RBAC, Azure PIM 
5.	Storage accounts and key vaults 
6.	How to give access on VM for certain time?
7.	Difference between NSG and ASG
8.	Difference between NSG and Firewall
9.	Manage identity
10.	Write a Virtual network code.
11.	How to create resources using Terraform modules, explain?
12.	Scenario on Terraform output/refresh/.
13.	Scenario on State commands and lookup function. 
14.	Foreach and lookup function use cases
15.	Terraform work flow
16.	What is backend block.
17.	Scenario on Rolling upgrade strategy in AKS.
18.	Networking in AKS 
19.	Helm and its configuration, write and explain.
20.	Scenario based on Taint toleration and node affinity.
21.	Security and access in AKS
22.	Probes and its use case in AKS
23.	Write a docker file.
24.	Difference between CMD and ENTRYPOINT
25.	Difference between COPY and ADD
26.	Write a k8s deployment file
27.	Write and explain sample script in any language like python, bash, PowerShell.
28.	Write down Yaml pipeline and explain the concept of conditioning and depends on in that pipeline.
29.	Scenario based on Agent pools and runners.
30.	Scenario based on branching and deployment strategies.
31.	Questions on tools like sonarQube, Veracode , fortify etc
32.	Scenario based on End-to-end Pipeline setup for any tech application in Azure Devops
33.	Scenario based on Variable groups, library and Deployment groups in Azure Devops
34.	Scenario based on writing `Pipeline in Gitlab and Github Actions
35.	How to define secret in pipeline.
36.	How to connect key vault in pipeline.
37.	1. Tell me about yourself and project 
38.	2. Azure recovery service 
39.	3. How are you storing backups 
40.	4. How are you connecting backup and virtual machine
41.	5. How you can connect 2 azure services 
42.	6. How are you providing RBAC permission to VM when using azure key vault
43.	7. Types of the azure key vault rbac roles
44.	8. Private endpoint scenario based, why using 
45.	9. Type of load balancer and which one using 
46.	10. Front door load balancer workflow and the backend  sevies
47.	11. Nsg and asg difference , if vm are created in different regions then one asg can work ?
48.	12. Blob container having connection with database, i have the access owner and wanted to make database public then how you prevent 
49.	13. How to Variable in pipeline 
50.	14. How to use two repository in one pipeline 
51.	15. We have 3 stage then How to skip 2nd stage
52.	16. Docker file about layer concept 
53.	17. Multistage Docker file explained with scanrio based 
54.	18. Terraform state file refresh 
55.	19. Count and for each 
56.	20. For each ot dynamic block 
57.	21. Move block in terraform 
58.	22. Scanrio based questions for Module






COFORGE

	1. Intro
	2. How you reduce the downtime and deployment time.
	3. Difference between highly available and highly scalable environment
	4. How State lock works and it's advantage.
	5. What are the resources you have created on azure.
	6. Is there any difference in load balancer and application gateway if yes then what and share use cases.
	7. Why don't we use the application gateway in backend and vice versa.
	8. How we use the Vertical and horizontal scaling and use cases. 
	9. If someone modify the code in config file in Terraform what will happen after apply command
	10. Did you face any problem while working on terraform
	11. How you work on Modules in terraform 
	12. How you deploy java application in pipeline.
	13. How you deploy infra pipeline tell the steps.
	14. How you deploy SonarQube and why?
	15. How you deploy the artifacts in application pipeline with Kubernetes.
	16. How you access the storage a/c with a different Vnet resources.
	17. How you can communicate two diff Vnets
	18. Difference between CMD and ENTRYPOINT
	19. How you manage the git conflict
	20. What is difference between git pull and merge.
2nd Round - Coforge
1. Tell me about backend block
2. What is local Exec and remote Exec and use case.
3. How you create service connection
4. Docker file
5. Difference ADD and COPY command





















Volkswagen Group Technology
   
  >Your team is experienced a warning that the rtifactory storage limit nearing the capacity as a skoda base image maintainer you have to address the issue without disrupting the Ongoing development ,how you will resolve the issue.
	Ø  How do you make sure compliance in skoda base images.
	Ø Have u used sonar cube anytime.
	Ø What are the steps we have to follow to secure the container images
	Ø How to integrate user base images with cicd pipeline
	Ø When you run export DOCKER_CONTENT_TRUST=1 what will happen.
	Ø Development team warns to integrate UBI(user base  interface) to their existing cicd pipeline ,explain how integration will be accomplished 
	Ø How jenkins files will use the UBI image
	Ø If you want to secure powershell scripts that manages scoda based images to prevent the other jobs execution so what are best pratices you have to follow
	Ø Any vulnerability assessment you do for images you have create
	Ø What is PODman
	Ø Whenever you restart the container using podman and you have to persist the data what is the approach you have to follow.
	Ø To list the dependencies in a Docker environment ,you can write a bash script that check for common package managers and list the installed packages.















Hitachi - First Round

1.	Your Terraform state file is locked, what steps will you take to resolve it?

2.	Why does the Terraform state file get locked, especially when there is only one agent working?

3.	What is terraform import and how do you use it?

4.	What is a null_resource in Terraform and when do you use it?

5.	Explain the purpose of terraform validate and terraform plan commands.

6.	What is etcd in Kubernetes?

7.	What is the difference between a ReplicaSet and a DaemonSet in Kubernetes?

8.	What are different deployment strategies in Kubernetes?

9.	How will you schedule a Pod to run on a particular node in Kubernetes?
10.	How will you schedule a Pod to run on a particular node in Kubernetes?

11.	If we are already using Docker, why do we need Kubernetes?

12.	What is Ingress in Kubernetes?

13.	You have two microservice-based applications, how will you expose them externally?

14.	What are Kubernetes namespaces and why do we use them?

15.	If a namespace is deleted, how can you recover the resources or handle that situation?

16.	What are some commonly used Docker commands?

17.	How do you use Docker Compose?

18.	What is the difference between Docker Compose and a Dockerfile?

19.	Explain a typical CI/CD workflow for an application.

20.	What is Checkmarx and how is it used in CI/CD?

21.	You mentioned SAST tools, do you also have experience with DAST tools?

22.	Have you worked on Azure PaaS services like MySQL, SQL Server, or Cosmos DB?

23.	What are IAM roles and how do you implement least privilege access?

24.	What are Azure Policies and how are they used?

25.	What types of storage services are you familiar with in Azure?

26.	Are you familiar with Python scripting, PowerShell scripting, or Azure Functions?

27.	Which monitoring tools have you worked with? Are you familiar with Azure Monitor?
28.	Have you worked on Azure PaaS services like MySQL, SQL Server, or Cosmos DB?

29.	What are IAM roles and how do you implement least privilege access?

30.	What are Azure Policies and how are they used?

31.	What types of storage services are you familiar with in Azure?

32.	Are you familiar with Python scripting, PowerShell scripting, or Azure Functions?

33.	Which monitoring tools have you worked with? Are you familiar with Azure Monitor?
































Sonata

1	what the essential things required to do with ADO?	1st level interview Scheduled - Sonata Software.

2.  self hosted agent(1-Linux=Source-used for CI & 2-Server=Destination-used for CD), Service Connection
3. What the additional policy need to setup with ADO?

3	Tell me the build and deploy pipeline?
4	what the other things are required on ADO, apart from service connection, service principal, agent connectivity?		

5	What the use of artifact and test plan in ADO?		

6	what the things required to provisioning the aks cluster?		

7	how to expose your aks cluster on public?		

8	how to do monitoring of your aks cluster?		

9	how to connect your monitoring VM through your clsuter privately?


