# EX288

Deploy a docker project on Openshift cluster:

```bash
   oc new-project aliokan-docker-build
   oc new-app --name=echo https://github.com/yukselao/EX288#docker-build --context-dir=ubi-echo
```
