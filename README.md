imagepurger
===========

This is a simple tool to get the image count on Kubernetes compute nodes
down, so `kubectl get nodes -o json` doesn't lie about whether images
are present or not.
