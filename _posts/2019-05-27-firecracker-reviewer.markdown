---
layout: post
title:  "Firecracker Reviewer"
date:   2019-05-27 21:51:00 +0700
categories: [fireworkmes]
---

Firecracker run on KVM environment. After system run bacis command line for [KVM-installing][kvm-installing] had finished. System base must enabled VT-x/AMD-V on the bios before run KVM. Now focusing on firecracker engine built-in on container such docker engine use [Runc merge into the Containerd][compare-containerd-with-runc]. See from the Firecracker project have more feature than run on pure KVM. Firecracker-containerd able to use fireacker engine run on docker container.


<!-- {% responsive_image path: assets/images/IMG_20190528_122912.jpg  template: _includes/responsive-image.html %} -->
<p>
<picture>
	<source media="(min-width: 530px)" srcset="/assets/images/resized/530/IMG_20190528_122912.jpg" style="margin-left: 50px;">
        <img src="/assets/images/IMG_20190528_122912.jpg">

</picture>
</p>

For interesting acticle supports the Cloud developer.

1. [The Firecracker virtual machine monitor][the-firecracker-virtual-machine-monitor]
2. [Design approaches in firecracker-containerd][design-approaches-in-firecracker-containerd]
3. [Firecracker as container runtime][firecracker-as-container-runtime]
4. [Making OSv Run on Firecracker][making-osv-run-on-firecracker]

[kvm-installing]: https://www.cyberciti.biz/faq/install-kvm-server-debian-linux-9-headless-server/
[compare-containerd-with-runc]: https://stackoverflow.com/questions/41645665/how-containerd-compares-to-runc
[the-firecracker-virtual-machine-monitor]: https://lwn.net/Articles/775736/
[design-approaches-in-firecracker-containerd]: https://github.com/firecracker-microvm/firecracker-containerd/blob/master/docs/design-approaches.md
[firecracker-as-container-runtime]: https://fosdem.org/2019/schedule/event/containers_firecracker/attachments/slides/3188/export/events/attachments/containers_firecracker/slides/3188/Firecracker_as_a_container_runtime_FOSDEM2019_4_3.pdf
[making-osv-run-on-firecracker]: http://blog.osv.io/blog/2019/04/19/making-OSv-run-on-firecraker/


