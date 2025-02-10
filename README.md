 Terraform S3 Static Website

This project automates hosting a **static website** on AWS S3 using Terraform.  
Steps to Deploy**  
1️⃣ **Clone the Repo**  

git clone https://github.com/your-username/terraform-s3-website.git
cd terraform-s3-website
  

2️⃣ **Initialize Terraform**  

terraform init


3️⃣ **Deploy the Website**  
terraform apply -auto-approve


4️⃣ **Get Website URL**  
terraform output website_url
  
Open the URL in a browser   


#Project Structure**  

terraform-s3-website/
├── website-files/   # Website files (HTML, CSS, JS)
├── main.tf          # Terraform config
├── variables.tf     # (Optional) Variables
├── outputs.tf       # Outputs the website URL
├── README.md        # Docs



## To Delete Everything**  
terraform destroy -auto-approve


###  Notes**  
- Ensure **AWS CLI is configured** (`aws configure`).  
- If **AccessDenied error**, disable **Block Public Access** in S3 settings.  
- Use a **unique S3 bucket name**.  

