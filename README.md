# Architectures Logicielles Java(1) (GLG203)

## Dépôt utilisé pour le projet/tutoriel du cours GLG203.

### Étapes de travail et liens

- 30/12/2017: Téléchargement du fichier [ubuntu-16.04.3-desktop-amd.ISO](http://releases.ubuntu.com/16.04.3/ubuntu-16.04.3-desktop-amd64.iso?_ga=2.141958513.275425082.1514648910-708044463.1514648910) pour créer un environnement de travail Ubuntu dans VMware Workstation. **DONE**

    ***Erreur**: This virtual machine is configured for 64-bit guest operating systems. However, 64-bit operation is not possible.
    This host supports Intel VT-x, but Intel VT-x is disabled.
    Intel VT-x might be disabled if it has been disabled in the BIOS/firmware settings or the host has not been power-cycled since changing this setting.
    (1) Verify that the BIOS/firmware settings enable Intel VT-x and disable 'trusted execution.'
    (2) Power-cycle the host if either of these BIOS/firmware settings have been changed.
    (3) Power-cycle the host if you have not done so since installing VMware Player.
    (4) Update the host's BIOS/firmware to the latest version.
    For more detailed information, see http://vmware.com/info?id=152.*
    
    ***Solution**: Accéder au bios de l'hôte et activer la technologie virtuelle.* 

   *Dans Windows 10:*
```
                        1. Navigate to settings.

                        2. Select Update & security.

                        3. Select Recovery from the left menu.

                        4. Click Restart Now under Advanced startup.

                        5. Click Troubleshoot.

                        6. Click Advanced options.

                        7. Select UEFI Firmware Settings.

                        8. Click Restart.
```
    
- 30/12/2017  : Téléchargement de [Java 9](http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html) dans VMware Workstation. **DONE**

- 30/12/2017  : Téléchargement de [Docker CE for Ubuntu](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#upgrade-docker-ce) dans VMware Workstation. **DONE**

   *Je rencontre quelques difficultés techniques à ce stage*

   ***Solution:** Utilisation de "Ubuntu Software Center" pour l'installation suite à l'erreur décrite [ici](https://askubuntu.com/questions/760034/waiting-to-install-for-ever-ubuntu-software-16-04)*
   
   *Autre erreur rencontrée et [**solution**](https://techoverflow.net/2017/03/01/solving-docker-permission-denied-while-trying-to-connect-to-the-docker-daemon-socket/).*
   
   **TEST**
   ```
   mohamed@ubuntu:~$ sudo docker run hello-world
   [sudo] password for mohamed: 
   Unable to find image 'hello-world:latest' locally
   latest: Pulling from library/hello-world
   ca4f61b1923c: Pull complete 
   Digest: sha256:445b2fe9afea8b4aa0b2f27fe49dd6ad130dfe7a8fd0832be5de99625dad47cd
   Status: Downloaded newer image for hello-world:latest

   Hello from Docker!
   This message shows that your installation appears to be working correctly.

   To generate this message, Docker took the following steps:
    1. The Docker client contacted the Docker daemon.
    2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
       (amd64)
    3. The Docker daemon created a new container from that image which runs the
       executable that produces the output you are currently reading.
    4. The Docker daemon streamed that output to the Docker client, which sent it
       to your terminal.

   To try something more ambitious, you can run an Ubuntu container with:
    $ docker run -it ubuntu bash

   Share images, automate workflows, and more with a free Docker ID:
    https://cloud.docker.com/

   For more examples and ideas, visit:
    https://docs.docker.com/engine/userguide/

   ```

- 30/12/2017   :  Téléchargement de la [vidéo](https://www.youtube.com/watch?v=caXHwYC3tq8&index=2&list=PLP0aqyZ5GFdlIIXhGEbJOndZUUqIppqED) à partir de la chaine [Cookie Connecté](https://www.youtube.com/channel/UC5cs06DgLFeyLIF_II7lWCQ/about) qui explique en moins de 10 minutes le sujet Docker. **DONE**
  
- 31/12/2017   :  Création du document PPT "Présentation" à partir de la vidéo. 

- 01/01/2018   :  Création du document PPT "Présentation" à partir de la vidéo. **DONE**

- 01/01/2018   :  Création du document PPT "Tutoriel".

- 01/01/2018   :  Voir comment utiliser [GitHub Pages](https://help.github.com/articles/what-is-github-pages/) pour la génération de la documentation.

- 01/01/2018   :  Publication du lien du projet dans l'issue/instructions de l'organisation ISSAE.


Total Hours of work: 1,5 + 2 + 2 + 3 
