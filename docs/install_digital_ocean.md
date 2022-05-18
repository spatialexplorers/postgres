https://github.com/supabase/postgres/wiki/Digital-Ocean

```sh
$ export DO_TOKEN=your_digital_ocean_token
$ export REGION=your_chosen_region
$ export SNAPSHOT_REGIONS=your_chosen_snapshot_regions
```

```sh
$ packer build \
  -var "do_token=$DO_TOKEN" \
  -var "region=$REGION" \
  -var "snapshot_regions=$SNAPSHOT_REGIONS" \
  digitalOcean.json
```
