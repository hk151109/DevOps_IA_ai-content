Quick deploy (GCP)

- This service runs Flask on port 5001.
- Build & deploy to GKE via Cloud Build using cloudbuild.yaml.
- Substitutions to set when triggering:
  - _GKE_CLUSTER, _GKE_ZONE
