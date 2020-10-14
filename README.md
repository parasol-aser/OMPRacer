# OMPRacer

OMPRacer has been incorporated into Coderrect, a full fledged HPC debugging tool. Please checkout coderrect.com to download the tool (free download and use).

The OMPRacer prototype appeared in SC'20 is only provided as a binary.

The easiest way to try it out is to use our [docker image](https://hub.docker.com/repository/docker/bradswain/ompracer).

```
docker pull bradswain/ompracer
docker run -it --rm bradswain/ompracer
root@05d8f1e254af:~# ./run.sh
...
```

The full JSON reports for each project will be stored into `~/reports/report/races_{project_name}.json`.

We have also included a binary release under the [Releases](https://github.com/BradSwain/ompracer/releases) page.
The binary was built for ubuntu 18 (bionic).
