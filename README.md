# kubernetes-demo

This is a hands-on, practical tutorial of using the different Kubernetes Components together, which will give you a big picture.

We basically create the Kubernetes infrastructure for this browser request flow:
![image](https://github.com/user-attachments/assets/85908db7-ba1e-48a8-933a-eb551e84c028)

In this project, we're going to deploy to 2 applications, **MongoDB** and **Mongo Express**, because it demonstrates really well, typical simple setup of a web application and its database, you can apply this to any similar setup that you have, so let's see how you gonna do this.
First, we are going to create a **MongoDB** pod and in other to talk to that Pod, we're gonna need a service. We are going to create an internal service, which basically means no external requests are allow to talk to the pod, only components inside the same cluster that can talk to it.

Detailed walkthrough here: https://medium.com/@onabanjo.temitayo3/complete-guide-to-setting-up-your-application-using-kubernetes-components-48bd7c980db1

