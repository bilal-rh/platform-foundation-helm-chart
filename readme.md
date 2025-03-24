

platform-foundation/
├── Chart.yaml
├── values.yaml
├── templates/
│   ├── namespace.yaml
│   ├── openshift-gitops-operator.yaml
│   ├── openshift-serverless-operator.yaml
│   ├── openshift-service-mesh-operator.yaml
│   ├── openshift-pipelines-operator.yaml
│   ├── openshift-ai-operator.yaml
│   ├── node-feature-discovery-operator.yaml
│   ├── nvidia-gpu-operator.yaml
│   ├── authorino-operator.yaml
│   ├── subscriptions.yaml
│   ├── dsci-initialization.yaml
│   ├── datasciencecluster.yaml
│   ├── odh-dashboard-config.yaml
│   └── hook-check-operators.yaml
└── README.md


helm install platform-foundation ./platform-foundation --create-namespace