terraform {
  required_providers {
    google = {
      source  = "hashicorp/google"
      version = ">4.51.0"
    }
  }
}
resource "google_compute_instance" "default" {
  name         = "my-instance"
  machine_type = "n2-standard-2"
  zone         = "us-central1-a"
}
