# Assignment 4 — Deploy EpicReads Portfolio Website via Nginx

Part of the DevOps Micro Internship (DMI) Cohort 3 with Agentic AI

---

## Purpose

In this assignment, you will deploy a static portfolio website on an Ubuntu VM using Nginx. You will download the website template, add your ownership proof in the footer, deploy the files to the Nginx web root, and verify the website is publicly accessible via a browser.

---

# Task 0 — Pre-flight Check

## Goal

Verify the Ubuntu VM and Nginx are ready for deployment.

### Evidence

#### Screenshot 0 — Output of `sudo systemctl status nginx --no-pager` showing Active (running)

Add your screenshot here.
<img width="799" height="414" alt="--no-pager" src="https://github.com/user-attachments/assets/51c270e7-72f7-4a51-9613-11700ac79c2a" />

---

# Task 1 — Get the Website Source Code

## Goal

Download and extract the portfolio website template.

### Evidence

#### Screenshot 1 — Output of `ls -la` showing the extracted project folder

Add your screenshot here.
<img width="596" height="232" alt="ls-la" src="https://github.com/user-attachments/assets/86ead41d-e8a2-487c-8003-896b393370d3" />

---

# Task 2 — Add Ownership Proof (Anti-Copy Change)

## Goal

Update the website footer with your deployment details.

### Evidence

#### Screenshot 2 — Nano editor open with the updated footer showing your Full Name, Group, Week, and Date

Add your screenshot here.
<img width="974" height="294" alt="footer" src="https://github.com/user-attachments/assets/2de4f05b-9b04-4a99-be3c-d709cf186de6" />

---

# Task 3 — Deploy Website via Nginx

## Goal

Deploy the portfolio website to the Nginx web root.

### Evidence

#### Screenshot 3 — Output of `sudo nginx -t` showing configuration test successful

Add your screenshot here.
<img width="630" height="67" alt="-ttt" src="https://github.com/user-attachments/assets/b424c3b1-7dee-4814-b938-c2b63215b6c8" />

---

#### Screenshot 4 — Output of `ls /var/www/html` showing deployed website files

Add your screenshot here.
<img width="805" height="107" alt="ls-var-www-html" src="https://github.com/user-attachments/assets/7aad85cc-553b-4b91-a47b-bd420c65e446" />


---

# Task 4 — Verify Website is Live

## Goal

Verify the deployed website is publicly accessible and the footer contains your details.

### Evidence

#### Screenshot 5 — Output of `curl ifconfig.me` showing the server's public IP address

Add your screenshot here.
<img width="663" height="48" alt="curl-ifconfigme" src="https://github.com/user-attachments/assets/e569af33-96d0-4ff7-a17b-75cead2afe55" />

---

#### Screenshot 6 — Browser showing the live website with your Full Name and deployment details in the footer

Add your screenshot here.
<img width="774" height="187" alt="deployby" src="https://github.com/user-attachments/assets/992158a0-0c23-4f6c-80f1-871049a2e7e1" />

---

# Task 5 — Mini Real DevOps Operational Check

## Goal

Verify the deployed website and Nginx service are healthy.

### Evidence

#### Screenshot 7 — Output of `systemctl is-enabled nginx`

Add your screenshot here.
<img width="782" height="63" alt="is-enabled" src="https://github.com/user-attachments/assets/9cc3d31c-4381-4f53-89c4-24568ec0c092" />

---

#### Screenshot 8 — Output of `curl -I http://localhost` showing 200 OK

Add your screenshot here.
<img width="772" height="184" alt="curl-I-http" src="https://github.com/user-attachments/assets/1c473ee5-8e04-40e4-a5d2-20e95cafd0e3" />

---

# LinkedIn Post (Mandatory)

## Evidence

#### LinkedIn Post URL

Paste your LinkedIn post URL here:

`Add your URL here`

---

#### Screenshot — Published LinkedIn post showing the live website with your Full Name in the footer

Add your screenshot here.

---

# Submission Instructions

- Add all required screenshots in your submission
- Full name must be visible in required screenshots
- Ownership proof in the footer is mandatory
- Do not expose sensitive information (keys, passwords, account IDs)

---

# Completion Checklist

- [ ] Screenshot 0: Nginx service status (active/running)
- [ ] Screenshot 1: Website files downloaded and extracted
- [ ] Screenshot 2: Footer updated with Full Name, Group, Week, and Date
- [ ] Screenshot 3: Nginx configuration test successful
- [ ] Screenshot 4: Website files deployed to /var/www/html
- [ ] Screenshot 5: Public IP retrieved
- [ ] Screenshot 6: Live website accessible in browser with footer details
- [ ] Screenshot 7: Nginx enabled on boot
- [ ] Screenshot 8: Local HTTP response returns 200 OK
- [ ] LinkedIn post published and URL submitted
- [ ] Full Name visible in all required screenshots
- [ ] No sensitive data exposed

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.

---

## 📌 Resources

- 🌐 DMI Official Website: https://pravinmishra.com/dmi  
- 🎓 DevOps for Beginners (Udemy): https://www.udemy.com/course/devops-for-beginners-docker-k8s-cloud-cicd-4-projects/  
- 🎓 Agentic AI DevOps with Claude Code: https://www.udemy.com/course/ultimate-agentic-ai-devops-with-claude-code/  
- 🎓 DevOps with Claude Code: Terraform, EKS, ArgoCD & Helm: https://www.udemy.com/course/devops-with-claude-code-terraform-eks-argocd-helm/  
- ▶️ YouTube Playlist: https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 Pravin Mishra (LinkedIn): https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 CloudAdvisory (LinkedIn): https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) Cohort 3 — Agentic AI Track.*
