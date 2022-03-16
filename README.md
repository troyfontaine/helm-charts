# Helm Charts

A collection of customized helm charts.  Adds support for additional functionaity in some cases, provides a helm chart where no official one exists in others.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add troyfontaine https://troyfontaine.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
troyfontaine` to see the charts.

To install the splunk-operator chart:

    helm install my-splunk-operator troyfontaine/splunk-operator

To uninstall the chart:

    helm delete my-splunk-operator
