## VAUED Assignment

Work Distribution:

1. REST Service Implementation: This task involves implementing the REST service and configuring the Prometheus exporter/module. (2 Members can handle this task)

2. Prometheus Setup and Deployment: Setting up Prometheus and deploying it. (2 Members can handle this task)

3. Grafana Setup and Dashboard Creation: Setting up Grafana, creating a dashboard, and configuring alerting. (2 Members can handle this task)


Task 1: REST Service Implementation

    Choose Programming Language and Framework:
        Decide on the programming language and framework for building the REST service. Since Ballerina was mentioned as an option, you can go with that.

    Implement the REST Service:
        Members 1 and 2 should collaborate to define endpoints, handle requests, and return responses. They should also integrate Prometheus metrics instrumentation into the service code.

    Configure Prometheus Exporter/Module:
        If using Ballerina, utilize the Prometheus extension to expose metrics easily. Otherwise, use built-in exporters or libraries to expose metrics in Prometheus format.

    Testing and Documentation:
        Ensure thorough testing of the service to verify functionality and metric collection. Document the endpoints, metrics exposed, and any setup instructions needed for deployment.

Task 2: Prometheus Setup and Deployment

    Install and Configure Prometheus:
        Members 3 and 4 should install Prometheus and configure the prometheus.yml file to scrape metrics from the REST service implemented by Members 1 and 2.

    Docker/Kubernetes/Cloud Deployment:
        Deploy Prometheus using Docker, Kubernetes, or a cloud platform as specified in the assignment requirements.

Task 3: Grafana Setup, Dashboard Creation, and Alerting

    Install and Configure Grafana:
        Members 5 and 6 should install Grafana and configure it. They should add Prometheus as a data source in Grafana.

    Create Dashboard:
        Collaboratively design and create a dashboard in Grafana to visualize the metrics collected from the REST service. Ensure it provides clear and understandable insights.

    Export Dashboard to JSON:
        Export the dashboard to a JSON file as required by the assignment.

    Setting Up Alerting:
        Configure alerting rules in Grafana based on the metrics collected. Define thresholds and conditions for triggering alerts.

    Docker/Kubernetes/Cloud Deployment:
        Deploy Grafana using Docker, Kubernetes, or a cloud platform as specified in the assignment requirements.
