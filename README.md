Minimal example for syncing a folder in github to hydroshare resource.  This example syncs files in the `notebook` directory to a HydroShare Resource.

To reuse this workflow, copy `.github/workflows/hs_sync.yaml` to your git repository at the same location (the name of the yaml can be different but the workflow needs to be in the `.github/workflows/` directory.

The workflow depends on 2 variables and 1 secret.  Below is a screenshot of where to set these within github (Settings->Secrets and variables -> Actions). 

Variables:
- HYDROSHARE_USERNAME
- HYDROSHARE_RESOURCE_ID

Secret:
- HYDROSHARE_PASSWORD

<img width="1651" alt="image" src="https://github.com/sblack-usu/hs-git-sync-example/assets/35820390/8aa1f545-b833-435e-a26e-649af3671f45">
