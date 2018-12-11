# Panel Discussion

## Questions:

* What have you seen in the real world. Biggest mistakes
  * Security as an afterthought
  * no root containers (ever at all)
  * challenge to keep up with the change right now
* user namespaces
  * allows root container through isolation. Breaking out of the container would result in the priv becoming user 5k. The real problem is that fs contexts don't support it and probably can't.
  * podman (user namespacing tool?)
* why do we have multiple fs?
  * what needs to be an oci image?
  * shoudln't be tied to a specific fs, we should experiment
  * 

* k8s ra ra. evolving quickly
  