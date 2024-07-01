# Docker Stop

Docker Stop is a simple script that stops all running containers on your machine.

## Installation

```bash
# clone the repository
git clone https://github.com/wesleyara/docker-stop

# enter the repository
cd docker-stop

# give permission to the script
chmod +x docker-stop.sh

# move the script to /usr/bin
sudo mv docker-stop.sh /usr/bin/docker-stop
```

## Usage

```bash
# adding crontab for run the script every reboot
crontab -e
```

Add the following line to the crontab file:

```bash
@reboot /usr/bin/docker-stop
```

## Author

<table>
  <tr>
    <td align="center"><a href="https://wesleyaraujo.dev/"><img src="https://avatars.githubusercontent.com/u/89321125?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Wesley Araújo</b></sub></a><br /></td>
  </tr>
</table>