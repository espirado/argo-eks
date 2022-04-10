# sample-deploy-to eks using argo cd

# Step 1
 - Create Eks Environment using Cloudformation 
     # Tools
         - AWS cli - To interact with aws API
         - Git - source control management 
         - kubectl - interact with EKs cluster
     # Set up 
     ![Environment ](images/template1-designer.png)
       - Networking 
           - Virtual Private Cloud (VPC), Internet Gateway (IGW), Route Table, Routes, Subnets and Security Groups (SG)

       - AWS EKS Cluster - IAM Cluster (Control Plane) Role, provision EKS  Control Plane, IAM Node Group Role and provision Node Group
            - node group are workers           





