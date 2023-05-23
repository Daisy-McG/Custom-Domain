![Banner](assets/images/banner.png)

# Add Custom Domain to Github Pages

A quick guide on how to add a custom domain to a github pages website.


## Deploy Website

Deploy the project to github pages:

- Go to your main repository settings
- Click settings
- Click the 'pages' tab on the left
- Under 'branch', select main
- Click save

## DNS Records

Update DNS records on domain provider to point to github:

| Type         | Host | Value                 |
| --------     | ---  | --------              |
| A Record     | @    | 185.199.108.153       |
| A Record     | @    | 185.199.109.153       |
| A Record     | @    | 185.199.110.153       |
| A Record     | @    | 185.199.111.153       |
| CNAME Record | @    | github-user.github.io |

**NB: Depending on the domain provider, it may take several hours for this to be updated.**