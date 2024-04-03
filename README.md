# terraform-kubernetes-namespace
module "namespace" {
  source = "AnastasiaZinych/namespace/kubernetes"
  name   = "test"
  labels = {
    environment = "dev"
  }
  annotations = {
    managed_by = "terraform"
  }
}
