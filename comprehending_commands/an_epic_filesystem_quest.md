# Challenge Name
an epic filesystem quest

## My solve
**Flag:** `pwn.college{YQ-9bpeMVtRYx2MZYzG4rVDCR4d.QX5IDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls -a
.   .dockerenv  bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
..  SPOILER     boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@commands~an-epic-filesystem-quest:/$ cat SPOILER
Congratulations, you found the clue!
The next clue is in: /usr/lib/python3/dist-packages/python3_openid-3.1.0.egg-info

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/lib/python3/dist-packages/python3_openid-3.1.0.egg-info
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/python3_openid-3.1.0.egg-info$ ls -a
.  ..  .ALERT  PKG-INFO  dependency_links.txt  requires.txt  top_level.txt
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/python3_openid-3.1.0.egg-info$ cat .ALERT
Great sleuthing!
The next clue is in: /usr/lib/R/library/translations/tr

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/python3_openid-3.1.0.egg-info$ cat /usr/lib/R/library/translations/tr/HINT-TRAPPED
Tubular find!
The next clue is in: /etc/X11/Xresources
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/python3_openid-3.1.0.egg-info$ cd /etc/X11/Xresources
hacker@commands~an-epic-filesystem-quest:/etc/X11/Xresources$ ls
REVELATION  x11-common
hacker@commands~an-epic-filesystem-quest:/etc/X11/Xresources$ ls -a
.  ..  REVELATION  x11-common
hacker@commands~an-epic-filesystem-quest:/etc/X11/Xresources$ cat REVELATION
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/drivers/gpu/drm/vmwgfx

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/etc/X11/Xresources$ cd /opt/linux/linux-5.4/drivers/gpu/drm/vmwgfx
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/gpu/drm/vmwgfx$ ls
Kconfig         vmwgfx_binding.c     vmwgfx_drv.c      vmwgfx_gmrid_manager.c  vmwgfx_msg.c            vmwgfx_shader.c           vmwgfx_va.c
Makefile        vmwgfx_binding.h     vmwgfx_drv.h      vmwgfx_ioctl.c          vmwgfx_msg.h            vmwgfx_simple_resource.c  vmwgfx_validation.c
NOTE            vmwgfx_blit.c        vmwgfx_execbuf.c  vmwgfx_irq.c            vmwgfx_overlay.c        vmwgfx_so.c               vmwgfx_validation.h
device_include  vmwgfx_bo.c          vmwgfx_fb.c       vmwgfx_kms.c            vmwgfx_prime.c          vmwgfx_so.h
ttm_lock.c      vmwgfx_cmdbuf.c      vmwgfx_fence.c    vmwgfx_kms.h            vmwgfx_reg.h            vmwgfx_stdu.c
ttm_lock.h      vmwgfx_cmdbuf_res.c  vmwgfx_fence.h    vmwgfx_ldu.c            vmwgfx_resource.c       vmwgfx_surface.c
ttm_object.c    vmwgfx_context.c     vmwgfx_fifo.c     vmwgfx_marker.c         vmwgfx_resource_priv.h  vmwgfx_ttm_buffer.c
ttm_object.h    vmwgfx_cotable.c     vmwgfx_gmr.c      vmwgfx_mob.c            vmwgfx_scrn.c           vmwgfx_ttm_glue.c
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/gpu/drm/vmwgfx$ ls -a
.               ttm_object.c         vmwgfx_context.c  vmwgfx_fifo.c           vmwgfx_marker.c    vmwgfx_resource_priv.h    vmwgfx_ttm_buffer.c
..              ttm_object.h         vmwgfx_cotable.c  vmwgfx_gmr.c            vmwgfx_mob.c       vmwgfx_scrn.c             vmwgfx_ttm_glue.c
Kconfig         vmwgfx_binding.c     vmwgfx_drv.c      vmwgfx_gmrid_manager.c  vmwgfx_msg.c       vmwgfx_shader.c           vmwgfx_va.c
Makefile        vmwgfx_binding.h     vmwgfx_drv.h      vmwgfx_ioctl.c          vmwgfx_msg.h       vmwgfx_simple_resource.c  vmwgfx_validation.c
NOTE            vmwgfx_blit.c        vmwgfx_execbuf.c  vmwgfx_irq.c            vmwgfx_overlay.c   vmwgfx_so.c               vmwgfx_validation.h
device_include  vmwgfx_bo.c          vmwgfx_fb.c       vmwgfx_kms.c            vmwgfx_prime.c     vmwgfx_so.h
ttm_lock.c      vmwgfx_cmdbuf.c      vmwgfx_fence.c    vmwgfx_kms.h            vmwgfx_reg.h       vmwgfx_stdu.c
ttm_lock.h      vmwgfx_cmdbuf_res.c  vmwgfx_fence.h    vmwgfx_ldu.c            vmwgfx_resource.c  vmwgfx_surface.c
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/gpu/drm/vmwgfx$ cat NOTE
Lucky listing!
The next clue is in: /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/gpu/drm/vmwgfx$ cd /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ ls
Main.js  SNIPPET
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ ls -a
.  ..  Main.js  SNIPPET
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ cat SNIPPET
Tubular find!
The next clue is in: /etc/java-17-openjdk/security/policy/unlimited

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ ls /etc/java-17-openjdk/security/policy/unlimited
BLUEPRINT-TRAPPED  default_US_export.policy  default_local.policy
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ cat /etc/java-17-openjdk/security/policy/unlimited/BLUEPRINT-TRAPPED
Tubular find!
The next clue is in: /usr/lib/python3/dist-packages/hamcrest/core/helpers

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ ls /usr/lib/python3/dist-packages/hamcrest/core/helpers
GIST-TRAPPED  __init__.py  __pycache__  hasmethod.py  wrap_matcher.py
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ cat /usr/lib/python3/dist-packages/hamcrest/core/helpers/GIST-TRAPPED
Lucky listing!
The next clue is in: /usr/lib/python3/dist-packages/sage/groups/additive_abelian

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Pagella/Misc/Regular$ cd /usr/lib/python3/dist-packages/sage/groups/additive_abelian
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sage/groups/additive_abelian$ ls -a
.  ..  .TRACE  __init__.py  __pycache__  additive_abelian_group.py  additive_abelian_wrapper.py  all.py  qmodnz.py  qmodnz_element.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sage/groups/additive_abelian$ cat .TRACE
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{YQ-9bpeMVtRYx2MZYzG4rVDCR4d.QX5IDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to use ls cat and cd in different scenarious under different specifications.

## References 
None
