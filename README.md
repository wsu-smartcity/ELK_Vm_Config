![wsu cyber](pirate.jpeg)

# WSU ESIC ELK+Beats Setup Spec

This repo contains specs/configs for the set-up of the ELK stack and beats, for general maintenance. Now that the bare-metal
setup is known, it would be nice to deploy it as a docker image, but its not really necessary and
having direct access to the server is much easier.
* ELK_Design_Spec.docx: Details of the setup of ELK, beats, vms, etc
* /logstash_configs: The logstash configs that configure each shipper, in /etc/logstash/conf.d/