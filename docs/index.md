## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/jomcy-amzn/jm-eks-helm/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes


Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jomcy-amzn/jm-eks-helm/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
### Observability 
Visibility is also greatly improved by tools like Prometheus, Grafana, Loki, Fluentd and Elasticsearch allowing a centralized view of all cluster workloads. Prometheus has become the standard for capturing metrics in Kubernetes. It fills the same niche as AWS Cloudwatch Metrics, Cloudwatch Alerts, Stackdriver Metrics, StatsD, Datadog, Nagios, vSphere Metrics and others.
 Helm is a template-driven system based on decentralized model for chart sharing. Kustomize is based on deep merges and other structured transforms of YAML data.

There are cases where using both is reasonable, such as feeding the output from helm template into kustomize for overlays.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

##References : 
Helm VS Kustomize 
https://codeengineered.com/blog/2018/helm-kustomize-complexity/
https://phoenixnap.com/kb/helm-vs-kustomize
Running Helm charts in AmazonEKS using cloud Formation : 
https://aws.amazon.com/blogs/infrastructure-and-automation/using-aws-cloudformation-to-deploy-software-into-amazon-eks-clusters/
https://aws.amazon.com/de/blogs/infrastructure-and-automation/using-aws-cloudformation-to-deploy-software-into-amazon-eks-clusters/
https://github.com/aws-quickstart/quickstart-helm-resource-provider

Cloud Development Kit for Kubernetes
https://github.com/cdk8s-team/cdk8s

## Tasks 
Prepare a CFn  for deploying Camunda on Amazon EKS Cluster /ECS
https://camunda.com/blog/2019/06/camunda-bpm-on-kubernetes/
https://camunda.com/blog/2015/06/deploy-camunda-bpm-docker-image-with/
https://aws.amazon.com/getting-started/hands-on/deploy-docker-containers/
Refer https://github.com/holisticon/camunda-bpm-platform-aws-terraform and create camunda in eks accelerator


1. Use https://github.com/toniblyx/prowler
2. https://github.com/aws-samples/amazon-eks-refarch-cloudformation
3. https://github.com/kubernetes-sigs/kustomize/tree/master/examples/springboot
