---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}

# Welcome to my Blog !! 

Just humbly sharing a few things about **Cloud Computing**, **Machine Learning** , **Application Modernization**, **IBM i** & **DevOps** .  All based on customer projects, as a Pre-Sales Cloud/AI Architect @ the IBM Systems Center, Montpellier.

Content will be enriched continuously, stay tuned!  and feel free to contact me for complementary information, pptx files, live demos or questions! benoit.marolleau@fr.ibm.com

[![IBMi App Mod ](/assets/M3.png)](https://ibm.ent.box.com/v/appmod-ocp-power-demo1 "Modernization with OpenShift : replatforming ")

## Application Modernization Journey in the multi Cloud era

### App Modernization & Red Hat - MOP Assets (Presentations, Videos) on Open Source / Cloud Paks / Red Hat OpenShift 
Examples of [modernisation use cases & assets presentation](https://ibm.box.com/v/ibmi-modernization-assets2020)  & [Modernization Introduction](https://ibm.box.com/v/ibmi-modernization-intro) (September 2020) 
- [Illustration #1 (video) ](https://youtu.be/fHZjQiXSICQ)  Infrastructure Modernisation & Ops efficiency by automation - Infrastructure as code , Ansible/ CP4MCM  
- [Illustration #2 (video) ](https://www.youtube.com/watch?v=tdStP9Ck4dU) Leverage your existing estate,  DevOps efficiency : Monolith to Microservice & Integration with Micro-Service Apps. 
[Transformation Advisor / Replatforming](https://ibm.ent.box.com/v/appmod-ocp-power-demo1) demo pptx (traditional WebSphere on IBM i to OpenShift)
- [Illustration #3 (video)](https://www.youtube.com/watch?v=QemqAzpyJPc) Enrich / Augment your apps with Micro-services , API integration, AI with Watson, containerized ML - H2O, CP4D  

- Why Open Source & OpenShift ? : [Original version](https://ibm.box.com/v/ocp-opensource-ibmi)  and [Version 2: Reloaded](https://ibm.box.com/v/why-ocp-ibmi-reloaded) : focus on traditional environments (AIX/IBM i), CP4MCM, CP4Apps & micro-service journey

- Why Ansible ? [Business Value of Ansible and IBM i on IBM Systems Mag](https://ibmsystemsmag.com/Power-Systems/10/2020/automation-ansible-ibm-i)
- Integration / API Mgt :  [Web Services / API Management on IBM i](https://ibm.box.com/s/1yh6odomylwxwurs7yycf1dw1r7vj1go) : Node-RED/ LoopBack on IBM i , Cloud Pak for Integration.   

## Ops & Infrastructure Modernization - Assets (Presentations, Videos)
[IBM i - Infrastructure Modernization](https://ibm.box.com/s/kwb33pjykxbjvui3f379if7eckiizvqz)  What's new : Business Continuity (PowerHA, Db2 Mirror) ,  Cloud Computing (IBM Cloud..)
[IBM i on IBM Cloud](https://ibm.ent.box.com/v/psvs-focus-ibmi) - Deep Dive (Offering, HA/DR, Backup) -  [Demonstration](https://youtu.be/RywSfXT_LLs) (video)

## MOP Design Workshops - How can we help you? 

Example of previous [workshops](https://ibm.box.com/s/peor234x7hms4lfhiwy4ay9dd37pz05g) on similar subjects (focus IBMi here, on specific customer use case) 

 
## 1 - Latest Content
-  July 2020 - Open Source , OpenShift & App Modernization : [Why OpenShift and OCP for IBM i modernization?](https://ibm.box.com/v/ocp-opensource-ibmi) 
-  June 2020 - Cool Presentation & Demo - [Augment your Apps with H2O Driverless AI, Scikit-Learn & Machine Learning on IBM i](https://ibm.box.com/v/machinelearning-ibmi)

### Power Systems in the Multicloud Era - Video Series 2Q2020

-  Get Started with IBM Cloud Power Virtual Server & AIX/IBM i : [Video](https://youtu.be/RywSfXT_LLs)
-  Automation with Terraform, IBM Cloud Pak for MCM   [Video](https://youtu.be/fHZjQiXSICQ)
-  June 2020 - [Introduction to Power Virtual Server, Deep Dive , HA/DR & Object Storage backup](https://ibm.box.com/v/psvs-focus-ibmi)
-  June 2020 - [IBM i Integration](https://ibm.box.com/v/ibmi-api-integration) : Web Services, Node-red, Loopback, APIM, Cloud Pak for Integration intro

## 2 - Machine Learning

-  IBM i & Machine Learning : [Demonstrations Summary](https://ibm.box.com/s/kgi29tk40bzbq4ofsyu2drb55glcrqk8)  (details below)

-  IBM ML Solutions Overview: [Watson ML, PowerAI, Paks, H2O on POWER9 - focus IoT Predictive Maintenance](https://ibm.box.com/s/7paum9h4klekmadyldu9f3fo2v4j1hvp)

### Accelerated Auto ML with H20 Driverless AI - Focus on IBM i/AIX - Sept/Oct 2019 **
Live Talk in IBM Tech University Las Vegas (Oct 10th) , Prague (Oct 24th) [PowerVUG webinar](http://ibm.biz/PowerVUG) (Oct 16th)

- [Video on Youtube (PowerVUG Channel)](https://youtu.be/QemqAzpyJPc)
- [PowerVUG Presentation](http://public.dhe.ibm.com/systems/power/community/aix/PowerVM_webinars/89_Smarter_apps_with_ML_and_H2O.pdf)
- [Demo Presentation H2O & IBM i/AIX](https://ibm.box.com/v/ibmi-dai-demo-deck)
- [Demo Video H2O & IBM i/AIX](https://ibm.box.com/v/ibmi-dai-demo)
- [Demo Link on the IBM WW Demo Portal](https://www.ibm.com/systems/clientcenterdemonstrations/faces/dcDemoView.jsp?demoId=3282)

### IBM i , AI & Watson Studio / Watson Machine Learning
A first step to AI with IBM i Apps, using Open Source technologies for Machine Learning, and DSX aka IBM Watson Studio

A sample jupyter notebook here to illustrate the use of WML from a Python Notebook: https://github.com/bmarolleau/gosales-ibmi

- Presentation: 
[![Watson Studio WML intro - AI IBM i ](/assets/dsx-ibmi.jpg)](https://ibm.box.com/v/ibmi-opensource-watsonstudio "Watson Studio WML intro - AI IBM i")
- Soon you'll see how to use Driverless AI & PowerAI Vision from IBM i for creating a recommendation engine or other augmented apps using Open Source on i. 

### Get Started with IBM Cloud & AI , Watson IoT , IBM Watson
The Labs I created & use for Tech Sales on-boarding sessions,  IBM Cloud & Watson days in Universities & engineering schools. 
- IBM Cloud & Watson Day Labs  http://ibmcloud-watson-day.mybluemix.net/   

### **Watson Studio** & **Watson Studio Local**  with an IoT/ Predictive Maintenance example:   
  - Presentation:  
 [![Watson Studio intro - hybrid Cloud IoT ](/assets/dsx-iot-1.jpg)](https://ibm.box.com/v/iot-watsonstudio-maximo "Watson Studio intro - hybrid Cloud IoT")
 
  - Demo  https://ibm.ent.box.com/v/power-iot-dsx-video-mp4  

## 3 - Cloud, Kubernetes, OpenShift & IBM Cloud Paks, Multi-cloud : Application Modernization

### [Why Containerize your Apps? K8s, Multi-cloud Introduction](https://ibm.box.com/v/containers-modernization-K8s)

### [IBM Cloud Paks Value](https://ibm.box.com/s/5ifo3pvhn9tr249qwplccowwppm9wwvd)
- Presentation on the Demo Portal  :  https://ibm.box.com/v/icp-ibmi-modernization
- Video: A "Foundation" scenario using IBM Cloud Private, PowerVC & CAM for Multi Cloud automation & IaaS  , soon enriched with CI / CD.

[![IBM Cloud Private, PowerVC & CAM](/assets/videoCAM-ICP-IBMi.png)](https://ibm.box.com/v/ibmi-powervc-cam-icp-demo1 "IBM Cloud Private, PowerVC & CAM ")
 
  - Terraform & CAM sample code here 
	  -  https://github.com/bmarolleau/IBMPower/tree/master/OpenStack/terraform/hcl/single-vm-deploy


### IBM Cloud Private and K8s for AI - Deep Learning, AIVision & Driverless AI as a Service 
- Presentation Private Cloud for AI :  Behind the Scenes **Work in progress
https://ibm.box.com/v/icp-private-cloud-for-ai

### Prototyping with Purpose: Node-RED 

- To get started with Node-RED, refer to my web site http://ibmcloud-watson-day.mybluemix.net/     
- For ease of use, I wrote this Db2 for i in Node-RED :    https://flows.nodered.org/node/node-red-contrib-db2-for-i
- This tutorial (IBM i or other platforms) for  [Node-RED & Db2 for i with Watson](https://ibmcloud-watson-day.mybluemix.net/files/Lab.Node-RED-SocialDashboard.pdf)
- Reference docs: 
  - First of all, an excellent article for installing Node-RED on IBM i  https://developer.ibm.com/tutorials/i-running-node-red/
  - https://github.com/IBMDeveloperUK/NodeRED-for-AI-flows/blob/master/ibmi/ibmi-nodered.md


## 4 - Miscellaneous Presentations & Demos

### [PowerAI Vision 1.1.4 Intro & Demo](https://ibm.box.com/shared/static/jttt4e31boksoaph1b8hlh1vgk6nmb33.pdf)

###  COMMON Europe Congress - May 2019**  
[Watson Machine Learning - IBM i use cases and demos](https://ibm.box.com/shared/static/6s3d03gpp1on6rc2e18nk7s2n15kvtuy.pdf)

### Presentations & Demos from the Université IBM i - May 2019**  
[Université IBM i 2019](./UII2019.md)

### Private AI Architecture  -  PowerAI-WML
[![Private AI with PowerAI ](/assets/POWERAI-WML-Private-AI-Architecture.jpg)](https://ibm.box.com/s/gpa8bgzjokmtc84ierigfc0jpg85tlnh "PowerAI WML directions ")

### **Driverless AI & ICP on POWER9** 
  - Presentation :  [AI to do AI](./public/presentations/H2O_Driverless_AI_on_Power-_AI_to_do_AI_AA.pdf)
  - First demonstration:

[![Private AI with ICP, h2o.ai Driverless AI on POWER9/NVLink ](/assets/h2odai-video.jpg)](https://ibm.box.com/v/h2odai-power-demo1 "h2o.ai Driverless AI on POWER9 video 1 ")


## Contact 
benoit.marolleau@fr.ibm.com   