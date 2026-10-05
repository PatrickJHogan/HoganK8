# created HoganK8 setup

This is my current home setup for managing my k8s setup.  Partly this is just a proof of work for my skills. (as I'm assuming whoever is reading this found this with my resume). 

This github repo is the source of truth for my k8s cluster, which is currently managed via ArgoCD. Across 2 nodes, 1 is a Hetzner VPS running archlinux, and a server running in my home, also on archlinux, both running k3s.

Both servers are low power, because they don't need to be too powerful, as the actual users are only my household. Archlinux mainly because I enjoy the distribution, obviously would not be my choice for a production environment due to rolling updates meaning potential breakages, but for my home, I enjoy things breaking every now and then to keep my skills fresh.
