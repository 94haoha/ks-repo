# ks-repo
A Repo for Demo KubeSphere

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add hao-helm https://94haoha.github.io/ks-repo

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> hao-helm/<chart-name>

To uninstall the chart:

    helm uninstall my-<chart-name>
