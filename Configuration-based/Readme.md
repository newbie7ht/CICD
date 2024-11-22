/my-repo
  ├── src/
  ├── .code-scan-config.yaml
  ├── Dockerfile
  └── README.md


How It Works:
The readYaml step loads the .code-scan-config.yaml file into a Groovy map.
Configuration values (e.g., repo_url, branch, scan_type) are stored in variables or environment variables for use in later stages.
The pipeline dynamically adapts based on the loaded configuration.


Benefits of Automatic Detection
Ease of Use: Teams simply include .code-scan-config.yaml in their repository, and the pipeline adjusts automatically.
Scalability: Works across multiple repositories and teams without requiring hardcoded parameters in the pipeline.
Flexibility: Teams can modify their configurations without altering the pipeline.


