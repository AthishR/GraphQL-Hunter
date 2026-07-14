# GraphQL-Hunter
GraphQL-Hunter is an advanced reconnaissance framework that discovers hidden GraphQL endpoints through JavaScript crawling, robots.txt analysis, sitemap parsing, and 35+ common paths. Unlike traditional tools that just guess common directories, it thinks like a human researcher, finding endpoints buried in client-side code and configuration files.

## ⚡ Quick Install
```bash
git clone https://github.com/YOUR_USERNAME/GraphQL-Hunter
cd GraphQL-Hunter
pip install -r requirements.txt


##🎯 Basic Usage

# Basic scan
graphql-hunter example.com

# Deep recon with JavaScript crawling
graphql-hunter example.com --js

# Full hunt with all methods
graphql-hunter example.com --all-methods --threads 50 --output report.json

# With proxy (Burp Suite)
graphql-hunter example.com --js --proxy http://127.0.0.1:8080
