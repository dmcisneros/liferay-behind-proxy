🚨 **Liferay & Reverse Proxy Configuration Masterclass!** 🚨

If you've ever struggled with **mixed content errors** or **broken links** when deploying Liferay behind Nginx or Apache, the problem lies in the headers.

Properly setting up a Reverse Proxy (HTTPS termination) requires telling the backend (Liferay) the client's true protocol and domain using **X-Forwarded headers**.

This detailed guide explains:
 ✅ How Liferay uses **web.server.forwarded** properties.
 ✅ Configuration for **Dual Access** (Proxy & Tomcat Direct).
 ✅ Configuration for **Proxy-Only Access** (Enhanced Security).
 ✅ Ready-to-use snippets for **Nginx** and **Apache** to handle HTTPS and header injection.

I wrote a detailed article explaining the configuration scenarios, why they matter, and included a complete, working **Docker Compose example** .

📄 ** Read the full article:**
[ https://github.com/dmcisneros/liferay-behind-proxy](https://liferay.dev/b/comprehensive-guide-to-configuring-liferay-behind-a-reverse-proxy-nginx-apache-)

If you're working with production deployments, security, or DXP clustering, this resource will save you hours of testing and troubleshooting 😉

#Liferay #DXP #DevOps #ReverseProxy #Nginx #Apache #DockerCompose #SystemAdministration
