# kubernetes-jan25

Prompt for CNI
---------------
you are an kuberenetes expert
I'm a begineer in kubernetes
I'm trying to install k8s using kube-adm
I want to know what are possible CNI and give me an output in tabular format with CNI, purpose and when to use

Prompt for CRI
----------------
you are an kuberenetes expert
I'm a begineer in kubernetes
I'm trying to install k8s using kube-adm
I want to know what are possible CRI and give me an output in tabular format with CRI, purpose and when to use

Installation prompt   (UBUNTU 24.04)
-----------------------------------
you are an kuberenetes expert
I'm a begineer in kubernetes
I'm trying to install k8s 1.34 using kube-adm with single master and one node
my virtual machines are in AWS and both of them are ubuntu 24.04 using CRI which is containerd and CNI which is flannel.
Give me details from system requirements to installation steps and checks to ensure k8s is working correctly
 
UBUNTU 22.04
------------

you are an kuberenetes expert
I'm a begineer in kubernetes
I'm trying to install k8s 1.34 using kube-adm with single master and one node
my virtual machines are in Azure and both of them are ubuntu 22.04 using CRI which is docker and CNI which is calico.
Give me details from system requirements to installation steps and checks to ensure k8s is working correctly

while running containerd command if errors occurs run this command
-------------------------------------------------------------------
sudo apt clean
sudo apt update --fix-missing


Understanding manifest w.r.t apiServer/cluster
-----------------------------------------------
You are kubernetes api-server. I will give you k8s manifest 
tell me what you will be doing and give me in plain english what the manifest is all about.

Understanding manifest and knowing best practices
--------------------------------------------------
you are kubernetes expert, I will give you manifest files, explain what it does and also suggest me best practices around this manifest


