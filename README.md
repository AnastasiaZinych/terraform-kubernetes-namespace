# terraform-kubernetes-namespace

module "namespace" {
  source  = "AnastasiaZinych/namespace/kubernetes"
  name = "test"
}