# Rollout

Setup a development environment with rollout.

Any Linux/OSX system should be able to curl/wget a tarball and rollout.

### Usage

`curl -SLO https://rollout`  
`rollout # this should be on $PATH after initial rollout tarball`

### What this includes

- ./bin folder of scripts that should be executable e.g
  - rollout (setup the environment)
  - rollout-sshagent (run sshagent, even without systemd)
