# checklist

- demo for mec: 3 node cluster with gpu
  - 3 node
  - gpu offline
  - nic bond
  - macvlan + ipam
  - vGPU, https://docs.nvidia.com/datacenter/cloud-native/kubernetes/anthos-guide.html#install-the-gpu-operator
    - https://github.com/AliyunContainerService/gpushare-scheduler-extender
    - https://github.com/Deepomatic/shared-gpu-nvidia-k8s-device-plugin
    - https://github.com/NTHU-LSALAB/KubeShare
    - https://github.com/NVIDIA/k8s-device-plugin/issues/169
    - https://github.com/awslabs/aws-virtual-gpu-device-plugin
    - https://github.com/tkestack/gpu-manager
  - openshift custom release
    - for cert rotate
      - https://github.com/openshift/cluster-kube-apiserver-operator/
    - for scheduler extender
      - https://github.com/openshift/cluster-kube-scheduler-operator
      - we need user to access registry.ci.openshift.org/ocp/4.6:base first
    - cilium  
  - cnv ha test.
- nexus image list.
  - https://community.sonatype.com/t/how-can-i-get-a-list-of-tags-for-a-docker-image-akin-to-the-docker-hub-list/3210
  - good nexus ansible project
    - https://gitlab.consulting.redhat.com/fsi-automation/osp-ocp-disconnected
- Promtail + Loki + Grafana
  - https://grafana.com/oss/loki/
- rh342: https://role.rhu.redhat.com/rol-rhu/app/courses/rh342-7.2
- rh415: https://role.rhu.redhat.com/rol-rhu/app/courses/rh415-7.5
- rh442: https://role.rhu.redhat.com/rol-rhu/app/courses/rh442-8.0
- ocs course: https://learning.redhat.com/totara/program/view.php?id=324
- cmcc edge spec excel fine tune
- book
- ebpf learning and self tool
- rhcsa, rhce
- coreos install package, mco, ostree
  - or build self version ocp release
- do280?
- rhel, https://lab.redhat.com/
- multus + sriov
- pam / techito
- promethus rules
- rhel8 learning: https://role.rhu.redhat.com/rol-rhu/rhz/rhls/course/rh354-8.0/pr01
- lms, fuse: https://learning.redhat.com/totara/program/view.php?id=90
- lms, amq, https://learning.redhat.com/totara/program/view.php?id=97
- https://zh.d2l.ai/
- demo data grid
- https://grafana.com/grafana/plugins/jdbranham-diagram-panel

soft:
- ppt
- english
- japanes


abanden:
- offline https://www.erdemo.io/gettingstarted/
- offline: https://redhat-developer-demos.github.io/knative-tutorial/knative-tutorial/index.html
- offline: https://github.com/sa-mw-dach/manuela


done:
- ocp update api server cert, https://docs.openshift.com/container-platform/4.6/security/certificates/api-server.html
- ovn 4.2 tp, ipv6
  - begin in ocp 4.4
- operator sample 不正常，很多镜像没有，需要查一下  https://github.com/openshift/cluster-samples-operator
  - gave up
- etherpad
- squash registry
- kvm port redirect
- nic bound
- cnv offline
- github clone tool
- maven cache tool
- py install cache tool?
- ignition, nic bond
- ignition, macvlan fix (seperate machineconfig)
- ignition, volumn, raid, strip
- quay
- lms cloud native, https://learning.redhat.com/totara/program/view.php?id=104
- macvlan + default route change
- for edge cloud, sichuan, test macvlan+multus on 4.2
- lms, 3scale, https://learning.redhat.com/totara/program/view.php?id=47
- lms, dm, https://learning.redhat.com/totara/program/view.php?id=98
- haproxy support tcp
- 4.3, rh sso integration: https://access.redhat.com/documentation/en-us/red_hat_single_sign-on/7.3/html/red_hat_single_sign-on_for_openshift/tutorials#OSE-SSO-AUTH-TUTE
- 4.3 code ready workspace
- docker registry, default read only, adm can update, https://mindtrove.info/control-read-write-access-docker-private-registry/
- 4.3 kubevirt image, win10 disk image
- IMPORTANT: ocp registry with passwd
- Python 人工智能入门 4399, https://classroom.udacity.com/nanodegrees/nd089-cn-basic/dashboard/overview
- 机器学习工程师 6399
- catalog source restart bug: https://bugzilla.redhat.com/show_bug.cgi?id=1815957
- english 4150
- ccn upgrade to ansible version
- 4.3 promethus add kube:admin as admin to grafana
- 4.3 ceph s3 backend, https://medium.com/@two.oes/openshift-4-in-an-air-gap-disconnected-environment-part-3-customization-4b315dd17316
- 4.3 add infra label, and control router placement
- 4.3 gpu, check rhel and rhel coreos case, https://developer.ibm.com/storage/2020/02/10/enabling-and-monitoring-nvidia-gpus-on-openshift-4-for-ai-workloads-a-step-by-step-guide/
- 4.3 tool image, with iperf, nginx, tcpdump, ipmaddr, pkgen ....
- 4.3 eth0 calico https://docs.projectcalico.org/getting-started/openshift/installation.
- review sichuan testing plan, csi? ask
- cicd / techito?
- rhu: https://learning.redhat.com/course/view.php?id=899
- ocs 4.*
- scc profile, cap, selinux test case try
- ccn bug fix and test again. shandong training.
- lms, What's New from the BUs 2020: https://learning.redhat.com/totara/program/view.php?id=172
- sichuan testing plan.
- ocp 4.6, bm ipi disconnect
- demo ansible: https://github.com/ansible/workshops
- demo ccn upgrade to 4.6
  - spec:
  lookupPolicy:
    local: false
  dockerImageRepository: registry.access.redhat.com/ubi8/openjdk-11
- chrome bing wall pic new tab, https://codingcat.cn/ataraxia/


