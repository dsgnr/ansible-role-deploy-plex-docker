# Ansible Role: Deploy Plex with Docker

[![Build Status](https://travis-ci.org/dsgnr/ansible-role-deploy-plex-docker.svg?branch=master)](https://travis-ci.org/dsgnr/ansible-role-deploy-plex-docker)

This role installs the Plex Docker container.

## Requirements

None.

## Role Variables

- vault_plex_claim_id: The claim ID retrieved from plex.tv/claim
- plex_db_store: Where the Plex database is stored
- plex_transcode_store: Where the Plex transcode store is located
- plex_data_store: Where the Plex media is stored

## Dependencies

None.

## Example Playbook

    - hosts: all
      become: true
      
      roles:
        - deploy-plex

## License

GNUv3

## Author Information

This role was created by [Dan Hand](https://danielhand.io).

