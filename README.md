## Hi, I'm Yevhenii Rosliakov 👋

<p><em>Senior DevOps Engineer at <a href="https://sigma.software/">Sigma Software</a></p>

```python
#!/usr/bin/python3
import pprint


class DevOps:
    def __init__(self):
        self.full_name = "Yevhenii Rosliakov"
        self.role = "DevOps Engineer"
        self.languages_spoken = {"en_US", "uk_UA", "ru_RU"}
        self.skills = {
            "Code": {"Python", "Bash"},
            "Cloud": {"AWS"},
            "OS": {"Linux"},
            "CI/CD": {"Jenkins", "GitHubActions", "Travis CI"},
            "CM": {"Ansible", "Vagrant", "Packer"},
            "IaC": {"Terraform", "Terragrunt"},
            "Monitoring": {"ELK", "EFK", "Prometheus", "Grafana", "Blackbox", "Amazon CloudWatch"},
            "Containers": {"Docker", "Docker Compose", "ECS", "Kubernetes", "Helm"},
	    "Web servers": {"Nginx", "Apache"}
        }
        self.certifications = {
            "AWS": "https://www.credly.com/badges/9a34c826-acb7-45fe-a232-ca980e3781aa",
            "Terraform": "https://www.credly.com/badges/d1d294a1-80a6-4946-ab7c-4ace8bfb58e5",
            "Kubernetes": "In progress"
        }

    def __repr__(self):
        return pprint.pformat(self.__dict__, indent=4)

    def __str__(self):
        return self.__repr__()


if __name__ == "__main__":
    me = DevOps()
    print(f"Hello world form {me.full_name}. Some details about me:\n{me}")

```

### Feel Free to Contact me.....
<p align="center">
	<a href="https://www.linkedin.com/in/eugene-roslyakov-a64a92151"><img alt="linkedin" width="10%" style="padding:5px" src="https://img.icons8.com/clouds/100/000000/linkedin.png"/></a>
</p>
