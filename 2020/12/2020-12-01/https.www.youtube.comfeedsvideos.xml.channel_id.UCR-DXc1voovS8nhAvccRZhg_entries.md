# Source:Jeff Gerling, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg, language:en-US

## Kubernetes 101 - Episode 3 - Deploying Apps
 - [https://www.youtube.com/watch?v=nn9J9sWLj_w](https://www.youtube.com/watch?v=nn9J9sWLj_w)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2020-12-02 00:00:00+00:00

In this episode, we’ll learn about how to deploy apps into Kubernetes, using the Hello Go app and container image we built in episode 2. But first, I'll show you a way to create a quick cluster in the Cloud for testing, in case you're having trouble or can't install Minikube locally!

More info: https://kube101.jeffgeerling.com

Special thanks to amazee.io for sponsoring this series: https://www.amazee.io

Sponsor me on GitHub: https://github.com/sponsors/geerlingguy
Support me on Patreon: https://www.patreon.com/geerlingguy

Links:

  - Linode $100 Credit: https://linode.com/geerling
  - 50,000 Kubernetes Jobs: https://www.youtube.com/watch?v=O1iEBzY7-ok
  - Kubernetes 101 Book: https://www.kubernetes101book.com
  - Ansible for Kubernetes for $4.99: https://leanpub.com/ansible-for-kubernetes/c/mZkrcxrfmWw8
  - Episode Details: https://kube101.jeffgeerling.com/2020/episode-3-deploying-apps
  - Episode Examples: https://github.com/geerlingguy/kubernetes-101/tree/master/episode-03

#kubernetes #kube101

Contents:

00:00 - Livestream start
01:33 - K8s dev cluster in the cloud
05:50 - amazee.io shout-out
06:56 - Deploying Apps into Kubernetes
12:14 - Creating and using image pull secrets
15:44 - Exposing the Hello Go App
20:47 - Scaling the Hello Go App
30:10 - Updating the Hello Go App
36:01 - Rolling back a Deployment
40:48 - Thanks and next episode

## Kubernetes is dropping Docker support?!
 - [https://www.youtube.com/watch?v=0oVDPf8zPS0](https://www.youtube.com/watch?v=0oVDPf8zPS0)
 - RSS feed: https://www.youtube.com/feeds/videos.xml?channel_id=UCR-DXc1voovS8nhAvccRZhg
 - date published: 2020-12-02 00:00:00+00:00

Earlier today people started mentioning the news that Kubernetes 1.20 deprecated support for Docker. But what does that mean?

Kubernetes will still run Docker images just fine, since Docker images conform to the OCI standard. But Kubernetes recommends using a more lightweight container runtime, like containerd, or CRI-O, to actually _run_ containers inside a Kubernetes cluster.

So don't fret, this change likely won't affect you no matter what tools you use, unless you regularly install new Kubernetes clusters and set up Docker with them. And in that case, it should be a simple fix—install containerd instead of Docker on your Kubernetes nodes!

Support me on Patreon: https://www.patreon.com/geerlingguy
Sponsor me on GitHub: https://github.com/sponsors/geerlingguy

