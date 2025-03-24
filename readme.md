

platform-foundation/
├── Chart.yaml
├── values.yaml
├── templates/
│   ├── namespace.yaml
│   ├── subscriptions.yaml
│   ├── dsci-initialization.yaml
│   ├── datasciencecluster.yaml
│   ├── odh-dashboard-config.yaml
│   └── hook-check-operators.yaml
└── README.md


helm install platform-foundation ./platform-foundation 