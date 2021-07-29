# Dockerizing-Shiny-Applications

 Docker provides isolation to applications. Images are immutable. Running multiple instances of the same image can serve many users at the same time. All these general advantages of containerized applications apply to Shiny apps too.
 

All the general advantages of containerized applications apply to Shiny apps. Docker provides isolation to applications. Images are immutable: once build they cannot be changed, and if the app is working, it will work the same in the future. Another important consideration is scaling. Shiny apps are single-threaded, but running multiple instances of the same image can serve many users at the same time. Let's dive into the details of how to achieve this.

The .docx attached file contains the code set for this repository
