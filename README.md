# full-stack-bootcamp

## Docker set up

Docker is an open-source containerization software that creates isolated environments to run an application. Hence, you develop, test, and run multiple applications on the same machine.

### Linux:

On Linux you have to install Docker by comand line. See [Docker documentation](https://docs.docker.com/engine/install/ubuntu/) in "Install Docker Engine" part or these three steps should be enought:

```sh
$ sudo apt-get update
$ sudo apt-get install docker-ce docker-ce-cli containerd.io
```

To check if installation went correct run command:

```sh
$ sudo docker run hello-world
```

### Mac:

Here are the procedures to install Docker on **macOS**:

1. Download [Docker desktop for Mac](https://hub.docker.com/editions/community/docker-ce-desktop-mac) and double-click the **.dmg** file you’ve saved. Then, drag and drop the **Docker** icon to your Applications folder.

2. Open your Applications folder and double-click docker.app. During the configuration process, you’ll be asked to enter your password.

3. Once the installation process is finished, you’ll see the docker menu in your desktop’s status bar.

## Windows:

Here’s how you can install Docker on **Windows 10 64-bit**:

1. Enable the Hyper Link-V. Try first [enable the hyper-v role through settings](https://docs.microsoft.com/pl-pl/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v?redirectedfrom=MSDN#enable-the-hyper-v-role-through-settings).

Check if your Windows fullfill [requirements](https://docs.microsoft.com/pl-pl/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v?redirectedfrom=MSDN#check-requirements)

2. Downoload [Docker desktop for Windows 10](https://hub.docker.com/editions/community/docker-ce-desktop-windows).
   Then open the Docker for **Windows Installer** file.

3. In the **Configuration** dialog window, check or uncheck the boxes based on your preferences. Click **Ok**.

4. Once the installation is finished, hit Close. You’ll see the Docker icon in the taskbar.

## Run your docker-compose.yml

In you project directory full-stack-bootcamp\$/ run comand:

```sh
$ docker-compose up
```

## visit http://localhost:8000
