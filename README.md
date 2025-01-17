![OpenShift - Wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/OpenShift-LogoType.svg/100px-OpenShift-LogoType.svg.png)![Angular - PRESS KIT](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLHZ7_lKApQX-3zDkXMVG029QBcaAc4F8sq9z7O7P5mw&s)

**Angular:**

The Developer Sandbox for Red Hat OpenShift is a free-to-use OpenShift instance for you to experiment with OpenShift for your use cases. Development of dynamic and responsive web applications has evolved into a fundamental requirement. Node.js and Angular stand out as formidable technologies capable of crafting these applications with finesse. Our workflow involves the creation and deployment of applications directly from GitHub onto an OpenShift sandbox environment.

Follow these steps to start your sandbox instance and deploy your Angular app:
1. Create a Sandbox account using [this link](https://developers.redhat.com/developer-sandbox).
2. Once you have the account, click on **Start using your sandbox**.
3. Give it a few seconds, and your sandbox instance will load up.
4. Make sure you're in the Developers perspective in OpenShift sandbox.
5. On the left side menu, click on **+Add**.
6. Select **Import from Git**.
7. Specify your Git repo URL: [https://github.com/redhat-developer-demos/Angular-openshift-example.git](https://github.com/redhat-developer-demos/Angular-openshift-example.git).
8. It will detect the Dockerfile from the git repository. If the Dockerfile is in a subdirectory that case we have to define a path.
9. In the 'Resource Type' field, please choose either **Deployment** or **Serverless Deployment** (default option).
10. Click on **Create**.
11. You will now be directed to the Topology view, and the application will commence deployment. Please allow approximately one minute for the deployment process to complete. While it is in progress, you will have the opportunity to monitor the logs.
12. Once it’s done deploying, you can click on the ***↗*** OpenURL button to see the UI of your Angular application running on OpenShift.

Congratulations! You've successfully deployed a basic Angular application on the OpenShift sandbox environment, all without the need for intricate configurations. 
