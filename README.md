# AwsLamdaRDSLayer
Java Lamda connecting to RDS and using layer to store mysql jar file

# 
Create RDS 
Create lamda (same VPC as RDS)
Create IAM Role with access to RDS , VPC
Create a lamda layer wthich will have mysql.jar file

#

inside pom.xml the mysql dependency is provided as it will be taken care by layer at runtime


