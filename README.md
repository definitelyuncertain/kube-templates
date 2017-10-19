This repository contains some useful templates for job submission using Kubernetes.

The file `pod-template.yaml` contains a template for a pod that exposes all necessary resources.

The file `job.sh` is a script that is called upon creation of the pod. It simply calls
`nvidia-smi` after setting the appropriate environment variables and sends the output
to a file.
