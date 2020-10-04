# 2020A-CR460-terraform-1
# Nouveau reposirtory pour des tests
# Nouveau repository pour utiliser d'autres fichiers (modules separes)  

### https://www.terraform.io/docs/providers/google/r/compute_autoscaler.html
### https://www.terraform.io/docs/providers/google/r/compute_instance_group_manager.html
### https://www.terraform.io/docs/providers/google/r/dns_record_set.html

* provider.tf
  * regroupe les informations du fournisseur cloud
* compute.tf
  * regroupe les informations d'instance et gestionnaires connexes
  * instances individuelles, modeles, groupe d'instance, gestionnaire du groupe, autoscaler
* network.tf
  * regroupe les ressources réseautique
  * reseau, sous-reseau, pare-feu, dns
