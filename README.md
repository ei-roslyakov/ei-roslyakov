## Hi, I'm Yevhenii Rosliakov 👋
<p><em>DevOps Engineer</em></p>

```python
#!/usr/bin/python3
import pprint
class DevOps:
    def __init__(self):
        self.full_name = "Yevhenii Rosliakov"
        self.role = "DevOps Engineer"
        self.location = "Kraków, Poland"
        self.languages_spoken = {"en_US", "uk_UA", "ru_RU", "pl_PL"}
        self.skills = {
            "Code": {"Python", "Bash"},
            "Cloud": {"AWS", "Azure", "GCP"},
            "OS": {"Debian/Ubuntu", "Amazon Linux", "Windows"},
            "CI/CD": {"Jenkins", "GitHub Actions", "GitLab CI", "Travis CI", "JFrog Artifactory", "ArgoCD"},
            "CM": {"Ansible", "Vagrant", "Packer", "Helm", "Consul"},
            "IaC": {"Terraform", "Terragrunt"},
            "Monitoring": {"ELK", "EFK", "Prometheus", "Grafana", "Alertmanager", "Loki", "Datadog", "Amazon CloudWatch", "Fluent Bit", "Fluentd"},
            "Containers": {"Docker", "Docker Compose", "ECS", "Kubernetes", "Helm", "Nomad"},
            "Web servers": {"Nginx", "Apache", "HAProxy"},
            "Security": {"SOC2", "OPA", "Vault", "Trivy", "OpenVPN", "Fail2Ban", "Nessus"},
            "Messaging & Caching": {"Redis", "RabbitMQ"},
            "Databases": {"MongoDB", "PostgreSQL", "Snowflake"}
        }
        self.certifications = {
            "AWS": {
                "AWS Certified SysOps Administrator - Associate": "Issued September 2025",
                "AWS Certified Solutions Architect – Associate": "Issued Jun 2021",
            },
            "Terraform": {
                "HashiCorp Certified: Terraform Associate (002)": "Issued Jan 2022"
            },
            "Kubernetes": {
                "CKA: Certified Kubernetes Administrator": "Issued Jul 2023"
            }
        }
        self.experience_years = 7
        self.specialization = [
            "Multi-cloud Kubernetes solutions",
            "High-availability systems",
            "Disaster recovery",
            "Infrastructure automation",
            "SOC2 compliance",
            "Cost optimization"
        ]
        
    def __repr__(self):
        return pprint.pformat(self.__dict__, indent=4)
        
    def __str__(self):
        return self.__repr__()

if __name__ == "__main__":
    me = DevOps()
    print(f"Hello world from {me.full_name}. Some details about me:\n{me}")
```

### Feel Free to Contact me.....
<p align="center">
    <a href="https://www.linkedin.com/in/yevhenii-rosliakov"><img alt="linkedin" width="10%" style="padding:5px" src="https://img.icons8.com/clouds/100/000000/linkedin.png"/></a>
</p>
