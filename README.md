### Terraform Notes  

#### **Concepts**  
- **Science fiction term for making an atmosphere habitable** → **Terraforming**  
- **Tool from HashiCorp** → **Terraform**  
- **Purpose** → Manage infrastructure on the cloud, maintain, and manage the state  

#### **Prerequisites**  
- AWS CLI must be configured  
- Run the command:  
  ```bash
  aws configure
  ```
  - Enter AWS credentials  
  - Verify configuration:  
    ```bash
    aws configure list
    ```  

#### **Terraform Commands**  
- **Validate syntax**  
  ```bash
  terraform validate
  ```  
- **Format code**  
  ```bash
  terraform fmt
  ```  
- **Check impact of the changes**  
  ```bash
  terraform plan
  ```  
- **Apply changes**  
  ```bash
  terraform apply
  ```  

#### **Additional Features**  
- **Using Variables** → Allows dynamic configuration  
- **Adding an S3 Bucket** → Store Terraform state files
