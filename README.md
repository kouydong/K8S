# vagrant
- vagrant로 Oracle VM Virtual BOX의 노드 자동 생성 환경 설정 파일입니다.
- This is a configuration file in Vagrant Software, creating VMs in VM Virtual BOX which is made by Oracle.
- vagrant download <https://www.vagrantup.com/downloads>
- VM virtual Box downlode <https://www.virtualbox.org>

- 환경 설정 파일의 정보는 아래와 같습니다
- The information for the configuration is as below.
---

- Vagrantfile : 마스터 노드와 서브노드를 자동으로 배포하기 위한 소스 코드가 포함되어 있습니다.(Ruby Programning)
- Vagrantfile : Node for Master and Sub is automatically deployed to use a vagrantifle.(Ruby Programming)
---

- Config.sh : 셀 스크립트로 마스터 노드에 자동으로 배포 되며 네트워크 테스트를 위해 퍼미션을 변경합니다.
- Config.sh : Node for master is automatically deployed to change the permission to make a test for network in Linux
---

- install_pkg.sh : 마스터 노드 및 서브노드에 자동으로 배포 되며 EPEL 및 VIM 설치를 진행합니다.
- install_pkg.sh : Node for Master and Sub is automatically deployed to install EPEL and VIM in Linux
---

- ping_test.sh : 마스터 노드에 자동으로 배포 되며 서브노드별 네트워크 핑 테스트를 진행 합니다.
- ping_test.sh : Node for Master is automatically deployed to make ping tests for each sub node.
---

If you have any questions please let me know ASAP.
