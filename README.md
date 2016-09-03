#### psmanagcertawscertmanag
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
