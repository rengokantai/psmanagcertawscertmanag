#### psmanagcertawscertmanag
#####2.Introduction to the AWS Certificate Manager
######Creating an SSL Certificate with ACM
input your domain, i.e
```
*.domainname.com
```
#####3.Implementing Certificates 
######ELB and Cloudfront Comparison
ELB:
- Region scope
- Integrates with EC2, Autoscaling
- No caching
- Custom listener ports
- Single origin
CloudFront:
- Global scope
- Integrates with WAF
- Caching capability
- No custom listener port
- Multiple origins

######Adding ACM Certificate to ELB
ELB->edit listeners->add port->add SSL, add ACM cert just create (first choice)

######Adding ACM Certificate to Cloudfront
distribution settings->edit->SSL certificate change 1 to 2 (Default->custom SSL
