# K8S Folding at home

This is a kubernetes configuration to run folding@home.
Based on [yurinnick/folding-at-home](yurinnick/folding-at-home) image.
Related reddits [here](https://www.reddit.com/r/Folding/comments/fdtrxy/yet_another_docker_image/) and [here](https://www.reddit.com/r/homelab/comments/fdtwhv/foldinghome_with_docker/)

## Installation

Inside the project folder run the following:

```bash
kubectl apply -k .
```

## Usage

* (currently not working) Control plane is available at `your-node-address`:30330
* (currently not working) UI interface is available at `your-node-address`:30396