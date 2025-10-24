# **Take-Home Assignment: Infrastructure as Code Challenge (Azure)**

### **Note**
**Expected Time Commitment:** 4 hours
**Deadline:** 1 week from access date
**Resources available to you:** Everything you would normally have in a workplace (internet, Copilot etc.)

### **Scenario**

Your company is preparing to host a new external web application in Azure. The application is not yet built, but leadership wants a **secure** infrastructure ready for development teams to consume. The app will have one frontend and one backend service. Your task is to **design and implement infrastructure-as-code (IaC)** to support this requirement.

You will be given high-level requirements and are expected to make reasonable architectural decisions. There is no need to deploy the IaC — focus on correctness, modularity, clarity, and security.

---

### **High-Level Requirements**

- The IaC must support **at least two environments** (e.g., cde and prod).
- Provide a single-purpose virtual network that supports a secure multi-tier application architecture. It doesn't need to support additional applications.
- You may choose the compute platform (e.g. VMs, App Services) — justify your decision.
- Provision resources sufficient to host a small web application.
- The web application will connect to a **SQL database** backend and use **Blob Storage** for static assets.
- Ensure least-privilege access.
- Ignore WAF/CDN setup.


---

### **Requirements for Your Submission**

- Use **Terraform** or **Pulumi** (your choice).
    
- Provide a **README** that includes:
    
    - Setup instructions (as if someone were to deploy it).
        
    - Your architectural reasoning: why you chose certain services or patterns.
        
    - How your design supports multiple environments.
	    
	- A list of issues you ran into and questions you had along the way (initiates feedback loop)
- Prune the file tree so the zip file has a minimal footprint