# fugue-state.io
An open source project for a modular D.A.W. aimed at learning music and facilitating practice.
## Operators Manual
Do everything with declarative gitops. Use argo-cd for continuous delivery and argo-workflows for continuous integration.

### Bootstrapping
dot-files `workspace_bootstrap.sh` sets up debian dev container.

Manually apply the `fugue-state-io/terraform` terraform repository.
- Provide `github org` credentials
- Provide `digital ocean` token
- Provide `helm repo` token
Manually deploy the `fugue-state-io/helm-charts/fugue-state` argo-cd app of apps.

## Methodology
Follow proven best practices
- Accelerate Book
- 12 Factor App
### 24 Accelerate Capabilities
#### 8 Continuous Delivery Capabilities
- Use Version control for all production artifacts
- Automate Your Deployment Process
- Implement Continuous Integration
- Use Trunk-Based Development Methods
- Implement Test Automation
- Support Test Data Management
- Shift Left on Security
- Implement Continuous Delivery
#### 2 Architecture Capabilities
- Use a Loosely Coupled Architecture
- Architecture for Empowered Teams
#### 4 Product Capabilities
- Gather and Implement Customer Feedback
- Make the Flow of Work Visible through the Value Stream
- Work in Small Batches
- Foster and Enable Team Experimentation
#### 5 Lean Management and Monitoring Capabilities
- Have Lightweight Change Approval Processes
- Monitor across Application and Infrastructure to Inform Business Decisions
- Check System Health Proactively
- Improve Processes and Manage Work with Work-In-Process Limits
- Visualize Work to Monitor Quality and Communicate throughout the Team
#### 5 Cultural Capabilities
- Support a Generative Culture
- Encourage and Support learning
- Support and Facilitate Collaboration among Teams
- Provide Resources and Tools that Make Work Meaningful
- Support or Embody Transformational Leadership
### 12 Factor App
- One codebase tracked in revision control, many deploys
- Explicitly declare and isolate dependencies
- Store config in the environment
- Treat backing services as attached resources
- Strictly seperate build and run stages
- Execute the app as one or more stateless processes
- Export services via port binding
- Scale out cia the process model
- Maximize robustness with fast startup and graceful shutdown
- Keep development staging and production as similar as possible
- Treat Logs as event streams
- Run admin/management tasks as one-off processes

