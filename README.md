# TagPolicy


1. Create a service layer application that must do the following:
	a. Scans AWS critical resource types like EC2, RDS, S3, Lambda, ELB, DynamoDB, ECS, EKS to validate required tags. The required tags are:
		 i. BusinessUnit = Production 
		ii. Enviroment = Production
		iii. Application = Tag Compliance Metrics
		iv. ApplicationOwner = Matthew Panek
		v. ResourceOwner-CostCenter = HQIT
		vi. Name = Compliance-Tag
		vii. General
		
	b. Calculates and returns the tag compliance across all services
	c. But it can also return tag compliance by individual service
	d. And can list out the worst tags by compliance and the worst services by compliance
	e. Recommend tag corrections for non-compliant resources


2. Create a Single‑page HTML Tag Compliance Scorecard
Must include:
Overall compliance %
🟢 >90%
🟡 70–90%
🔴 <70%
Compliance by service (bar or table)
Worst-compliant service
Top missing tags
Worst‑performing services
Most frequently missing tags
Summary statistics
2. CSV Export of Non‑Compliant Resources
Include for each resource:
ARN
Service type
Missing tags
Existing tags
Recommended tag corrections
