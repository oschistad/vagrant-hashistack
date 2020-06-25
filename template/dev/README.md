# Development template for `fredrikhgrelland/hashistack`

This template can be used as a base image for developing services on the hashistack.
If you found this in `fredrikhgrelland/vagrant-hashistack`, you may be interested in this separate repository [vagrant-hashistack-template-dev](https://github.com/fredrikhgrelland/vagrant-hashistack-template-dev)
Documentation on [parent repository](https://github.com/fredrikhgrelland/vagrant-hashistack#usage).

## Change configuration of hashistack

- consul `conf/consul/99-override.hcl`
- nomad `conf/nomad/99-override.hcl`
- vault `conf/vault/99-override.hcl`

You may edit the `99-override.hcl` or add you own.
Any valid configuration added to these directories will be added and lexically merged.