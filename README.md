## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```bash
 helm repo add gu https://mvpworkshop.github.io/gu-charts
 ```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. 
You can then run `helm search repo gu` to see the charts.

To install the nestjs chart:
```bash
helm install cws gu/cws
```

To uninstall the chart:
```bash
helm delete cws
```
