1. Create a disk on google cloud: gcloud compute disks create geth-testnet --zone xxx --size 150 --type pd-standard

2. Fill in the values in chart/values.yaml

3. Install the Helm chart: make install_chart

4. Upgrade deployment: make upgrade_deployment
